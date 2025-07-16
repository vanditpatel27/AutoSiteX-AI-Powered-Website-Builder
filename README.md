# AutoSiteX-AI-Powered-Website-Builder

AutoSiteX is an AI-driven website builder that simplifies the process of creating beautiful, responsive websites. Designed to assist users with little or no coding experience, AutoSiteX generates ready-to-use HTML/CSS/JS templates based on user inputs.

This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
```

Open [http://localhost:3008](http://localhost:3008) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Publish your e2b template

```bash
e2b template build --name template-name --cmd "/compile_page.sh"
```

name must be unique

