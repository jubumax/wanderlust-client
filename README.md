<div align="center">

# 🌍 Wanderlust

The client-side application of **Wanderlust**, built with Next.js and TypeScript.

🔗 **Live URL:** [wanderlust-jubumax.vercel.app](https://wanderlust-jubumax.vercel.app/)

</div>

---

## Description


Wanderlust is a modern travel-focused web application that helps people discover destinations, explore travel ideas and plan their next adventure. The frontend is built with the Next.js App Router, with a fast, responsive and clean user interface. This repository contains the **client side** of the project.

## Key Features

- Explore travel destinations with a clean, intuitive interface
- Easy navigation across pages with Next.js App Router
- Modern UI built with reusable shadcn/ui components
- Smooth, polished user experience
- Fully responsive design for mobile, tablet and desktop
- Fast performance with server-side rendering and optimized fonts

## 🛠️ Tech Stack

| Category      | Technology |
| ------------- | ---------- |
| Framework     | Next.js    |
| Language      | TypeScript |
| UI Components | shadcn/ui  |
| Linting       | ESLint     |
| Font          | Geist      |
| Deployment    | Vercel     |

## Project Structure

```
wanderlust-client/
├── public/                     # Static assets
├── src/                        # Application source code
├── components.json             # shadcn/ui configuration
├── eslint.config.mjs           # ESLint configuration
├── next.config.ts              # Next.js configuration
├── package.json
└── tsconfig.json
```

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) 18.18 or later
- npm, yarn, pnpm or bun

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/jubumax/wanderlust-client.git
   cd wanderlust-client
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Set up environment variables**

   Create a `.env.local` file in the project root:

   ```env
   NEXT_PUBLIC_API_URL=http://localhost:5000
   ```

4. **Run the development server**

   ```bash
   npm run dev
   ```

   Open [http://localhost:3000](http://localhost:3000) in your browser.


## Contributing

Contributions, issues and feature requests are welcome!

1. Fork the project
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m "Add amazing feature"`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request


---

© 2026 Wanderlust — [@jubumax](https://www.linkedin.com/in/jubumax) • All rights reserved