<p align="center">
<a href="https://github.com/vueuse/vueuse"><img src="https://raw.githubusercontent.com/vueuse/vueuse/main/packages/public/logo-vertical.png" alt="VueUse - Collection of essential Vue Composition Utilities" width="300"></a><br>
Collection of essential Vue Composition Utilities
</p>

<p align="center">
<a href="https://www.npmjs.com/package/@vueuse/core" target="__blank"><img src="https://img.shields.io/npm/v/@vueuse/core?color=a1b858&label=" alt="NPM version"></a>
<a href="https://www.npmjs.com/package/@vueuse/core" target="__blank"><img alt="NPM Downloads" src="https://img.shields.io/npm/dm/@vueuse/core?color=50a36f&label="></a>
<a href="https://vueuse.org" target="__blank"><img src="https://img.shields.io/static/v1?label=&message=docs%20%26%20demos&color=1e8a7a" alt="Docs & Demos"></a>
<img alt="Function Count" src="https://img.shields.io/badge/-156%20functions-13708a">
<br>
<a href="https://github.com/vueuse/vueuse" target="__blank"><img alt="GitHub stars" src="https://img.shields.io/github/stars/vueuse/vueuse?style=social"></a>
</p>

<p align="center">
  <a href="https://cdn.jsdelivr.net/gh/antfu/static/sponsors.svg">
    <img src='https://cdn.jsdelivr.net/gh/antfu/static/sponsors.svg'>
  </a>
</p>

## 🚀 Features

- 🎪 [**Interactive docs & demos**](https://vueuse.org)
- 🕶 **Seamless migration**: Works for  Vue3 (composition api)
- ⚡ **Fully tree shakable**: Only take what you want, [bundle size](https://vueuse.org/export-size)
- 🦾 **Type Strong**: Written in [Typescript](https://www.typescriptlang.org/), with [TS Docs](https://github.com/microsoft/tsdoc)
- 🔋 **SSR Friendly**
- 🌎 **No bundler required**: Usable via CDN
- 🔩 **Flexible**: Configurable event filters and targets
## 🦄 Usage

```ts
import { useMouse, usePreferredDark, useLocalStorage } from '@vueuse_ts/core'

export default {
  setup() {
    // tracks mouse position
    const { x, y } = useMouse()

    // is user prefers dark theme
    const isDark = usePreferredDark()

    // persist state in localStorage
    const store = useLocalStorage(
      'my-storage',
      {
        name: 'Apple',
        color: 'red',
      },
    )

    return { x, y, isDark, store }
  }
}
```

Refer to [functions list](https://vueuse.org/functions) or [documentations](https://vueuse.org/) for more details.

## 📦 Install

```bash
npm i @vueuse/core
```
### CDN

```html
<script src="https://unpkg.com/@vueuse/shared"></script>
<script src="https://unpkg.com/@vueuse/core"></script>
```

It will be exposed to global as `window.VueUse`

## 🧱 Contribute

See the [**Contributing Guide**](https://vueuse.org/contributing)

## 🌸 Thanks

This project is heavily inspired by the following awesome projects.

- [streamich/react-use](https://github.com/streamich/react-use)
- [u3u/vue-hooks](https://github.com/u3u/vue-hooks)
- [logaretm/vue-use-web](https://github.com/logaretm/vue-use-web)
- [kripod/react-hooks](https://github.com/kripod/react-hooks)

And thanks to [all the contributors on GitHub](https://github.com/vueuse/vueuse/graphs/contributors)!

## 👨‍🚀 Contributors

### Financial Contributors on Open Collective

<a href="https://opencollective.com/vueuse"><img src="https://opencollective.com/vueuse/individuals.svg?width=890"></a>

## 📄 License

[MIT License](https://github.com/vueuse/vueuse/blob/main/LICENSE) © 2019-PRESENT [Hirsch Adway](https://github.com/hirschadway)
