## WonderMod (PaperMod fork - theme for Hugo)

<p align="center">
  <img src="https://raw.githubusercontent.com/wonderfall/hugo-WonderMod/master/.github/assets/web-capture.jpeg" title="WonderMod" alt="WonderMod image">
</p>

### What is this?
WonderMod is a fork of an original theme for [Hugo](https://gohugo.io/) called [PaperMod](https://github.com/adityatelange/hugo-PaperMod) (made by adityatelange). Since PaperMod isn't interested in a few changes such as **removing inline JavaScript**, which I personally require to harden my websites, I decided to maintain my own fork (I didn't want to keep overwriting a bunch of files as a fork workflow is much cleaner). Don't expect a ton of changes, and unless you know me, you probably don't want to use WonderMod.

When implementing new features, I try to do as much as I can with pure CSS code instead of adding new JavaScript code. I'd like to keep the JavaScript part minimal and that's why WonderMod should be totally usable when disabling JavaScript. WonderMod is also designed with strong CSP headers in mind: no inline JavaScript or style, no calls to third-parties.

**This fork is regularly synced with upstream changes from [PaperMod](https://github.com/adityatelange/hugo-PaperMod).** A merging workflow was chosen since rebasing WonderMod's changes every time could be less efficient. As such, commit history is a bit messy, but upstream changes will be merged on a best effort basis.

### Main changes
Current "main" changes are as follows:
- Remove inline JavaScript ([2528906](https://github.com/Wonderfall/hugo-WonderMod/commit/2528906a38a1ca8a50b3e3a74ffcf9a01a0483a7))
- Improved YouTube shortcode ([4dc3bee](https://github.com/Wonderfall/hugo-WonderMod/commit/4dc3bee5477b6d22ce830faa13375f4c2e6a216b))
- Built-in Chroma instead of client-side syntax highlighting with HLJS ([841141](https://github.com/Wonderfall/hugo-WonderMod/commit/8411411a671785d098ffff9323b064acc0c16cb4))
- Responsive Table of Contents with side display support ([2303605](https://github.com/Wonderfall/hugo-WonderMod/commit/230360552b44a8e45496da76ae539a63ad0a3f5a))
- Responsive "hamburger" menu for mobile ([723ac4f](https://github.com/Wonderfall/hugo-WonderMod/commit/723ac4f5c68180b816ebf1dce26839fd3db02ab3))
- Simple reading progress bar ([13876be](https://github.com/Wonderfall/hugo-WonderMod/commit/13876beb0afd9d535890e82af459e639064650f1))
- Bunch of CSS and other changes (see [commit history](https://github.com/Wonderfall/hugo-WonderMod/commits/master))

### Credits
Additional credits:
- [PaperModX](https://github.com/reorx/hugo-PaperModX/) by reorx

### Configure
Most of the installation process and settings are shared with the original PaperMod, so check out [their documentation](https://github.com/adityatelange/hugo-PaperMod/wiki/Installation). One noticeable difference though is that in order to enable syntax highlighting, you have to add this to your `config.yml` :

```
markup:
    highlight:
        style: dracula
        noClasses: false
        guessSyntax: true
```

---

## FAQs / How To's Guide 🙋

Read Wiki For More Details => **[PaperMod-FAQs](https://github.com/adityatelange/hugo-PaperMod/wiki/FAQs)**

---

## Social-Icons/Share-Icons 🖼️

Read Wiki For More Details => **[PaperMod-Icons](https://github.com/adityatelange/hugo-PaperMod/wiki/Icons)**

---

## Release Changelog 📃

Release ChangeLog has info about stuff added: **[Releases](https://github.com/adityatelange/hugo-PaperMod/releases)**

---

## [Pagespeed Insights (100% ?)](https://pagespeed.web.dev/report?url=https://adityatelange.github.io/hugo-PaperMod/) 👀

---

## Support 🫶

-   Star 🌟 this repository.
-   Help spread the word about PaperMod by sharing it on social media and recommending it to your friends. 🗣️
-   You can also sponsor 🏅 on [Github Sponsors](https://github.com/sponsors/adityatelange) / [Ko-Fi](https://ko-fi.com/adityatelange).

---

## Special Thanks 🌟

-   [**Highlight.js**](https://github.com/highlightjs/highlight.js)
-   [**Fuse.js**](https://github.com/krisk/fuse)
-   [**Feather Icons**](https://github.com/feathericons/feather)
-   [**Simple Icons**](https://github.com/simple-icons/simple-icons)
-   **All Contributors and Supporters**

---

## Stargazers over time 📈

[![Stargazers over time](https://starchart.cc/adityatelange/hugo-PaperMod.svg?background=%23ffffff00&axis=%23858585&line=%236b63ff)](https://starchart.cc/adityatelange/hugo-PaperMod)
