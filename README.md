Modified versions of original `Nuxt Image` v0

- Add `density` support to config and component: With it NuxtImage will automatically generate src-set for screens with dps. Eg: `density: '1 2'` will generate `src-set` with 1x and 2x variants

TODO:
- Add `responsive` flag to automatically generate all src-set + densities values based on sizes
- Build in npm register, not in a repo

***

[![@nuxt/image](./docs/public/cover.jpg "Nuxt Image")](./docs/public/cover.jpg)

[![npm version][npm-version-src]][npm-version-href]
[![npm downloads][npm-downloads-src]][npm-downloads-href]
[![Checks][checks-src]][checks-href]
[![Codecov][codecov-src]][codecov-href]

- [📖 &nbsp;Read Documentation (v0)](https://image.nuxtjs.org)
- [▶️ &nbsp;Play online](https://githubbox.com/nuxt/image/tree/v0/example)

---

**Note:** This branch is for **Nuxt 2** compatible module. Checkout [`v1` branch](https://github.com/nuxt/image/tree/v1) for **Nuxt 3** support. ([Announcement](https://github.com/nuxt/image/discussions/548))

---

### Contributing

- Clone this repository
- Enable [Corepack](https://github.com/nodejs/corepack) using `corepack enable`
- Install dependencies using `yarn install`
- Use `yarn dev` to start [playground](./playground) in development mode.

## 📑 License

Published under the [MIT License](./LICENSE)

<!-- Badges -->
[npm-version-src]: https://flat.badgen.net/npm/v/@nuxt/image
[npm-version-href]: https://npmjs.com/package/@nuxt/image
[npm-downloads-src]: https://flat.badgen.net/npm/dm/@nuxt/image
[npm-downloads-href]: https://npmjs.com/package/@nuxt/image-edge
[checks-src]: https://flat.badgen.net/github/checks/nuxt/image/v0
[checks-href]: https://github.com/nuxt/image/actions
[codecov-src]: https://flat.badgen.net/codecov/c/github/nuxt/image
[codecov-href]: https://codecov.io/gh/nuxt/image
[license-src]: https://img.shields.io/npm/l/@nuxt/image.svg
[license-href]: https://github.com/nuxt/image/blob/v0/LICENSE
