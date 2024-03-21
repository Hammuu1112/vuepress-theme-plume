# vuepress-theme-plume

<p align="center">
<img src="https://github.com/pengzhanbo/vuepress-theme-plume/raw/main/preview/plume.svg" width="200px" alt="vuepress=theme-plume" />
</p>

[![npm version](https://img.shields.io/npm/v/vuepress-theme-plume?color=32A9C3&labelColor=1B3C4A&label=npm)](https://www.npmjs.com/package/vuepress-theme-plume)
[![npm download](https://img.shields.io/npm/dy/vuepress-theme-plume?color=32A9C3&labelColor=1B3C4A&label=downloads)](https://www.npmjs.com/package/vuepress-theme-plume)
![peer dependency](https://img.shields.io/npm/dependency-version/vuepress-theme-plume/peer/vuepress?color=32A9C3&labelColor=1B3C4A)
![GitHub License](https://img.shields.io/github/license/pengzhanbo/vuepress-theme-plume?color=32A9C3&labelColor=1B3C4A)

一个简约的，干净的，容易上手的 vuepress 主题，适用于博客和文档。

开箱即用，仅需少量配置即可使用，让您更专注于 内容的创作，更好的表达你的想法，形成你的知识笔记。

内置了丰富的强大的功能，旨在让内容更具有表现力。

## Features

- 💻 响应式布局，适配不同的屏幕尺寸
- 📖 博客 & 文档
- 🔗 自动生成文章永久链接
- ⚖ 支持多语言
- 🔑 支持 全站加密、部分加密
- 👀 支持 搜索、文章评论
- 👨‍💻‍ 支持 浅色/深色 主题 （包括代码高亮）
- 📠 markdown 增强，支持 代码块分组、提示容器、任务列表、数学公式、代码演示 等

### [查看文档](https://plume.pengzhanbo.cn/)

## Install

``` sh
# npm
npm i vuepress-theme-plume
# or pnpm
pnpm add vuepress-theme-plume
# or yarn
yarn add vuepress-theme-plume
```

## Usage

``` js
// .vuepress/config.ts
import { defineUserConfig } from 'vuepress'
import { plumeTheme } from 'vuepress-theme-plume'

export default defineUserConfig({
  theme: plumeTheme({
    // theme config
  })
})
```

### `plumeTheme(options)`

__options__ : `PlumeThemeOptions`

[查看 options 详细说明](https://plume.pengzhanbo.cn/config/basic/)

## LICENSE

[MIT](https://github.com/pengzhanbo/vuepress-theme-plume/blob/main/LICENSE)
