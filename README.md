# Blog Của Tôi

Blog cá nhân về phát triển phần mềm, xây dựng với Next.js 16 và ShadCN/UI.

## Tech Stack

- **Framework:** [Next.js 16](https://nextjs.org) (App Router, Turbopack)
- **UI Components:** [ShadCN/UI](https://ui.shadcn.com) (Radix UI + Tailwind CSS)
- **Styling:** [Tailwind CSS v4](https://tailwindcss.com) (CSS-first config, OKLCH colors)
- **Theme:** [next-themes](https://github.com/pacocoursey/next-themes) (light/dark mode)
- **Language:** TypeScript
- **Icons:** [Lucide React](https://lucide.dev)

## Project Structure

```
app/
├── layout.tsx          # Root layout with ThemeProvider
├── page.tsx            # Trang chủ
├── globals.css         # Tailwind v4 theme tokens
├── blog/page.tsx       # Trang blog
└── about/page.tsx      # Trang giới thiệu
components/
├── Header.tsx          # Responsive header with mobile sheet nav
├── Footer.tsx          # Site footer
├── ThemeProvider.tsx    # next-themes provider wrapper
├── ThemeToggle.tsx     # Light/dark mode toggle
└── ui/                 # ShadCN/UI components
lib/
├── config.ts           # Site metadata & author info
└── utils.ts            # Utility helpers (cn)
```

## Getting Started

```bash
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) to view the site.

## Scripts

| Command         | Description              |
| --------------- | ------------------------ |
| `npm run dev`   | Start dev server         |
| `npm run build` | Production build         |
| `npm run start` | Start production server  |
| `npm run lint`  | Run ESLint               |
