# 1.0.0 (2023-11-19)


### Bug Fixes

* **badges:** calc min and compression sizes ([0f0bd68](https://github.com/cshawaus/lite-youtube/commit/0f0bd6833304d0950a2ba1fc86b86ef7fb626774))
* clean up dom define, do not double stamp attr ([451769c](https://github.com/cshawaus/lite-youtube/commit/451769c6b56f5c40fcb35c2beb26663bd29ff774))
* **css:** change activation header precedent for hiding ([#9](https://github.com/cshawaus/lite-youtube/issues/9)) ([d8149fc](https://github.com/cshawaus/lite-youtube/commit/d8149fcabe4840620fabb2e67d334e733affb010))
* **height:** remove min-height, use 16:9 default to make it easier ([#2](https://github.com/cshawaus/lite-youtube/issues/2)) ([345976f](https://github.com/cshawaus/lite-youtube/commit/345976fe3258b9bb77de1dee5783abec0fae2dcb))
* **iframe:** loader missing flag check ([#8](https://github.com/cshawaus/lite-youtube/issues/8)) ([ff5ae2d](https://github.com/cshawaus/lite-youtube/commit/ff5ae2d8c317568479f883046db5b4233fc3c805))
* intersection observer injection no longer autoplays ([#35](https://github.com/cshawaus/lite-youtube/issues/35)) ([9bec0c9](https://github.com/cshawaus/lite-youtube/commit/9bec0c947e11ce48c966e3b53275ca19751b29ba))
* missing attrchange for playlistid ([f8a0646](https://github.com/cshawaus/lite-youtube/commit/f8a0646dbb85051630a0539b508f9d25876c7fbc))
* **package:** Make the package a valid ES module ([#76](https://github.com/cshawaus/lite-youtube/issues/76)) ([d3de76b](https://github.com/cshawaus/lite-youtube/commit/d3de76b5602eb368d5fb0a2bfa05f8b5af887a92)), closes [#75](https://github.com/cshawaus/lite-youtube/issues/75)
* **placeholder:** placeholder position with mis-aligned with text-align at parent ([#44](https://github.com/cshawaus/lite-youtube/issues/44)) ([90b64f3](https://github.com/cshawaus/lite-youtube/commit/90b64f350970a7e9abf426d6822be7274d4f159d))
* play button cursor type ([#63](https://github.com/cshawaus/lite-youtube/issues/63)) ([02a0d6e](https://github.com/cshawaus/lite-youtube/commit/02a0d6e0dd8712033dc81a5b1453e558a827b033))
* **preload:** prevent multiple rules in multi-instance scenario ([#69](https://github.com/cshawaus/lite-youtube/issues/69)) ([e85e5b1](https://github.com/cshawaus/lite-youtube/commit/e85e5b1717bf7c58b19a43945e5a8a8e42a0e3e8))
* resolve dead case path, add observe and coverage ([#95](https://github.com/cshawaus/lite-youtube/issues/95)) ([50c254b](https://github.com/cshawaus/lite-youtube/commit/50c254b579e92c39488af4b70a7240f96ba36eeb))
* **safari:** fixed style within shadow fails on Safari ([#4](https://github.com/cshawaus/lite-youtube/issues/4)) ([81e5be9](https://github.com/cshawaus/lite-youtube/commit/81e5be98f8b391a31b127d6450aebc4fa8c2ba25))
* **test:** resolve test errors with latest accessibility PR ([972a8f6](https://github.com/cshawaus/lite-youtube/commit/972a8f6271a50c2501c6d51ee578416571324662))


### Features

* add liteYoutubeIframeLoaded event for iframe load ([#39](https://github.com/cshawaus/lite-youtube/issues/39)) ([a870383](https://github.com/cshawaus/lite-youtube/commit/a870383f2968dffca1d48cfda1e32595d46087f5))
* add params option for yt query params ([c2be735](https://github.com/cshawaus/lite-youtube/commit/c2be7352dc4b410a386f69b8f62bfaa56a8b0f1f))
* add playlist loading support ([#40](https://github.com/cshawaus/lite-youtube/issues/40)) ([10ea534](https://github.com/cshawaus/lite-youtube/commit/10ea534880d71001424b0ada88e744704952b44a))
* add poster quality attr ([#36](https://github.com/cshawaus/lite-youtube/issues/36)) ([dc569a3](https://github.com/cshawaus/lite-youtube/commit/dc569a333424c72e9e6479c51e4113d66683d798))
* add shadow dom parts support ([9d0c32a](https://github.com/cshawaus/lite-youtube/commit/9d0c32a7291589678d8f79fe3f272d064626d6d3))
* add youtube-nocookie bool attr ([#38](https://github.com/cshawaus/lite-youtube/issues/38)) ([e23de5b](https://github.com/cshawaus/lite-youtube/commit/e23de5b0a70fb92ec933b0fd8d3e109e1fdef090))
* **autoload:** use intersection observer to auto-load on scroll ([06f4eb3](https://github.com/cshawaus/lite-youtube/commit/06f4eb3978e8de61b6a86051d83abe80734b989a))
* convert to typescript ([#10](https://github.com/cshawaus/lite-youtube/issues/10)) ([a2c4977](https://github.com/cshawaus/lite-youtube/commit/a2c497772a80265588fa600ed7ea59b47d4181d7))
* **core:** add YouTube Shorts-style mobile embed interaction ([#67](https://github.com/cshawaus/lite-youtube/issues/67)) ([ce2a16e](https://github.com/cshawaus/lite-youtube/commit/ce2a16ea646323a0769cb6dd5d4dc1d45e3eed1c))
* **csp:** add support for csp nonce to inline style ([#68](https://github.com/cshawaus/lite-youtube/issues/68)) ([b255b5d](https://github.com/cshawaus/lite-youtube/commit/b255b5d701004769bfdca4e1b729f3e0472bd947))
* **img:** add webp placeholder support ([9cd57b5](https://github.com/cshawaus/lite-youtube/commit/9cd57b5be7969f2f1fb1ff3f19b60d2175f540f9))
* **locale:** add aria and locale title ([#1](https://github.com/cshawaus/lite-youtube/issues/1)) ([4b6a91b](https://github.com/cshawaus/lite-youtube/commit/4b6a91bd95703a6a57abffd32268894ec9a8a8d2))
* **logo:** switch to official youtube logo ([#82](https://github.com/cshawaus/lite-youtube/issues/82)) ([68acaf8](https://github.com/cshawaus/lite-youtube/commit/68acaf89e5ac638c9a6feeb851788359ef576d2b))
* **poster:** add posterloading for img lazy load ([66e8751](https://github.com/cshawaus/lite-youtube/commit/66e87517acb09f48a8387124b0e8cb21b00e940a))
* **shadowdom:** lets shadow dom this thing ([036a100](https://github.com/cshawaus/lite-youtube/commit/036a10056bb10786baa265ba92acf0125dd0905e))
* **time:** add video start time attr ([#6](https://github.com/cshawaus/lite-youtube/issues/6)) ([aa68aae](https://github.com/cshawaus/lite-youtube/commit/aa68aae034ffa27cd41eb9b7522bb2f775bb7ff7))
