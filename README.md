[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/git/external?repository-url=https%3A%2F%2Fgithub.com%2Fcuongdphan%2Fnextjs-typescript-tailwindcss-boilerplate)

# Next.js + TypeScript + Tailwind CSS

Boilerplate for Next.js, TypeScript, Tailwind CSS

- **[ESLint][eslint]**
- **[Prettier][prettier]**
- **[Absolute Imports][absimp]** - Next.js
- **[JIT mode][jitmode], [Typography plugin][typoplug]** - Tailwind CSS
- **[Build-time imports][btimp]** - PostCSS
- **[Renovate][renovate]**

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.tsx`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.tsx`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

## License

[MIT](LICENSE)

[eslint]: https://eslint.org/docs/user-guide/getting-started
[prettier]: https://prettier.io/docs/en/index.html
[absimp]: https://nextjs.org/docs/advanced-features/module-path-aliases
[jitmode]: https://tailwindcss.com/docs/just-in-time-mode
[typoplug]: https://tailwindcss.com/docs/plugins#typography
[btimp]: https://tailwindcss.com/docs/using-with-preprocessors#build-time-imports
[renovate]: https://docs.renovatebot.com/
