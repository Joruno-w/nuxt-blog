<div align="center">
  <h1>Nuxt 3 Blog</h1>
</div>

site style form [antfu.me](https://antfu.me/), But base on [nuxt3](https://nuxt.com/)

## 💡Features

- Nuxt3 technology stack, ssr rendering, more friendly to seo
- Adapt to mobile end layout
- Page loading, dark mode transition animation Simple and elegant
- Use markdown as article format
- Tag Category View Function
- Article search function
- Integrate website configuration to reduce the mental burden of modification
- Comment function based on [Giscus](https://giscus.app/zh-CN)
- Site browsing statistics based on [51.LA](https://v6.51.la/)

## 🔎Setup
Make sure to install the dependencies:
```
pnpm install
```
open dev serve

```
pnpm dev
```

## 📖Usage

You should modify the following files

- site.config.ts - base site config
- content - your article folder
- `pages\p\[...post].vue` - comment config, to [Giscus](https://giscus.app/zh-CN)
- statistics code - site data statistics code, can be deleted if not needed
  ``` ts
  // nuxt.config.ts
  script: [
    // ⬇ can be deleted
    {
      src: 'https://xxxxx',
    },
  
  ]
  ```

## Icon
- [icon-park-outline](https://icones.js.org/collection/icon-park-outline)
- [simple-icons](https://icones.js.org/collection/simple-icons)
