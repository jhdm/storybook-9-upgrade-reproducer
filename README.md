# Reproducer for Storybook 9 Issues

**Issue**: storybook upgrade added `eslint-plugin-storybook` version `9.0.12`, but probably should be `^9.0.12` (with caret).

**Reporoducer**:

Start with `storybook-8` branch.

```sh
git checkout storybook-8
```

Upgrade:

```sh
npx storybook@latest upgrade
```

## Scaffold Info

Previously installed Storybook 8 like this:

```sh
npx storybook@8 init
```

Initial Vite Vue scaffold was created by,

```sh
npm init vite@latest storybook-9-upgrade-reproducer --template vue
```

This template should help get you started developing with Vue 3 and TypeScript in Vite. The template uses Vue 3 `<script setup>` SFCs, check out the [script setup docs](https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup) to learn more.

Learn more about the recommended Project Setup and IDE Support in the [Vue Docs TypeScript Guide](https://vuejs.org/guide/typescript/overview.html#project-setup).
