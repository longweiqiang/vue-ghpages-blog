# vue-ghpages-blog

[![GitHub release][github-release-image]][github-release-url]
[![JavaScript Style Guide][linting-image]][linting-url]
[![Dependency Status][daviddm-image]][daviddm-url]
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fviko16%2Fvue-ghpages-blog.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Fviko16%2Fvue-ghpages-blog?ref=badge_shield)

✏️ A blog based on GitHub Pages built with Vue.js 2 + webpack 3.

一个依赖 GitHub Pages，无需本地生成的静态博客，使用了 Vue.js 2 组件开发，webpack 3 打包。

## [DEPRECATED] 不再维护！！

- I've switched my blog project to [VuePress](https://vuepress.vuejs.org/). And this repository is no longer maintained. If you like the theme, you can try [vuepress-theme-simple](https://github.com/viko16/vuepress-theme-simple).
- 我已经将自己的博客程序迁移为 [VuePress](https://vuepress.vuejs.org/)，这个库也不再维护。如果你喜欢这个主题，可以试试 [vuepress-theme-simple](https://github.com/viko16/vuepress-theme-simple)，原汁原味~

![Post Screenshots](https://cloud.githubusercontent.com/assets/5064777/19349059/a815395c-9183-11e6-97c3-56514acf0f1d.png)

## Features

- Vue 2 / Vue-router / axios
- webpack 3 / Babel 6 / Stylus
- No need to generate locally ( now using [TravisCI](https://travis-ci.org) )
- Hosting on GitHub Pages
- SessionStorage cache

## Develop

**Note:** `src/config.js` points the configurations of my personal blog. **If you fork this repository, modify it first.**  😳

```bash
# Install dependencies
npm install
# Develop with hot reload
npm run dev
# Lint and Test
npm test
```

## Vue 1.x version

For the Vue 1.x version, please see the [vue-1 branch](https://github.com/viko16/vue-ghpages-blog/tree/vue-1). 

## About My Workflow
- All the posts are stored in [viko16/writings](https://github.com/viko16/writings), while [`src/config.js`](src/config.js) points it.
- When I push the code to `develop` branch, [TravisCI](.travis.yml) will deploy `gh-pages` automatically.

## License

MIT © [viko16](https://github.com/viko16)


[gitter-image]: https://badges.gitter.im/viko16/vue-ghpages-blog.svg
[gitter-url]: https://gitter.im/viko16/vue-ghpages-blog?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge
[github-release-image]: https://img.shields.io/github/release/viko16/vue-ghpages-blog.svg?style=flat
[github-release-url]: https://github.com/viko16/vue-ghpages-blog/releases/latest
[linting-image]: https://img.shields.io/badge/Linting-eslint--plugin--vue-brightgreen.svg?style=flat
[linting-url]: https://github.com/vuejs/eslint-plugin-vue
[travis-image]: https://img.shields.io/travis/viko16/vue-ghpages-blog/develop.svg
[travis-url]: https://travis-ci.org/viko16/vue-ghpages-blog
[daviddm-image]: https://david-dm.org/viko16/vue-ghpages-blog.svg?theme=shields.io
[daviddm-url]: https://david-dm.org/viko16/vue-ghpages-blog

[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fviko16%2Fvue-ghpages-blog.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2Fviko16%2Fvue-ghpages-blog?ref=badge_large)