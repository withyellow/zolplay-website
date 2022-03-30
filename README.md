# A Monorepo for Zolplay Website.

![Zolplay Banner](apps/web-cn/public/og-image.jpg)

[Zolplay Website](https://zolplay.com) - International site

[佐玩官方网站](https://zolplay.cn) - 国内官网

## What's inside?

It includes the following packages/apps:

### Apps and Packages

- `web`: Website for international audiences.
- `web-cn`: Website for hosting in China only.
- `config`: `eslint`, `prettier` and other configurations.
- `tsconfig`: `tsconfig.json`s used throughout the monorepo.
- `ui`: a shared React component library for all our web applications.

### Tools

This turborepo is built by these amazing tools:

- [TypeScript](https://www.typescriptlang.org/) for static type checking
- [ESLint](https://eslint.org/) for code linting
- [Prettier](https://prettier.io) for code formatting
- [Turborepo](https://turborepo.org) for managing the monorepo
- [Next.js](https://nextjs.org/) for building the web apps
- [pnpm](https://pnpm.io/) for managing the packages
- [TailwindCSS](https://tailwindcss.com/) for styling the web apps
- [Framer Motion](https://framer.com/motion/) for composing animations
- [Liveblocks](https://liveblocks.io/) for real-time presense
- [Zustand](https://github.com/pmndrs/zustand) for React state management

## Setup

To install all dependencies, run the following command:

```bash
pnpm i
```

### Build

To build all apps and packages, run the following command:

```bash
pnpm build
```

### Develop

To develop all apps and packages, run the following command:

```bash
pnpm dev
```
