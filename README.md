# create-boot

## Scaffolding Your First Web App Project

> **Compatibility Note:**
> Vite requires [Node.js](https://nodejs.org/en/) version 14.18+, 16+. However, some templates require a higher Node.js version to work, please upgrade if your package manager warns about it.

With NPM:

```bash
$ npm create boot@latest
```

With Yarn:

```bash
$ yarn create boot
```

With PNPM:

```bash
$ pnpm create boot
```

Then follow the prompts!

You can also directly specify the project name and the template you want to use via additional command line options. For example, to scaffold a Vite + Vue project, run:

```bash
# npm 6.x
npm create boot@latest my-vite-app --template vite

# npm 7+, extra double-dash is needed:
npm create boot@latest my-vite-app -- --template vite

# yarn
yarn create boot my-vite-app --template vite

# pnpm
pnpm create boot my-vite-app --template vite
```

Currently supported template presets include:

- `vite`

You can use `.` for the project name to scaffold in the current directory.
