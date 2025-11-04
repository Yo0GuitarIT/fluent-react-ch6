---
# You can also start simply with 'default'
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://cover.sli.dev
# some information about your slides (markdown enabled)
title: 流暢的 React - CH6
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# apply unocss classes to the current slide
class: text-center
# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: fade-out 
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
# open graph
seoMeta:
  # By default, Slidev will use ./og-image.png if it exists,
  # or generate one from the first slide if not found.
  ogImage: auto
  # ogImage: https://cover.sli.dev
fonts:
  sans: JetBrains Mono
  serif: JetBrains Mono
  mono: JetBrains Mono
css: style.css
hideInToc: true
---

## Tech Book Community
## 《流暢的 React : 建構快速、高效、直覺的 Web 應用程式》

### CH6: 伺服器端的 React 

導讀人：Yo0
筆記工：Weii

<div @click="$slidev.nav.next" class="mt-12 py-1" hover:bg="white op-10">
  Press Space for next page <carbon:arrow-right />
</div>

<div class="abs-br m-6 text-xl">
  <button @click="$slidev.nav.openInEditor()" title="Open in Editor" class="slidev-icon-btn">
    <carbon:edit />
  </button>
  <a href="https://github.com/Yo0GuitarIT/fluent-react-ch6" target="_blank" class="slidev-icon-btn">
    <carbon:logo-github />
  </a>
</div>

---
src: ./pages/introduction.md
---

---
src: ./pages/6-1.md
---

---
src: ./pages/6-2.md
---

---
src: ./pages/6-3.md
---

---
src: ./pages/6-4.md
---

---
src: ./pages/6-5.md
---

---
src: ./pages/6-6.md
---

---
src: ./pages/conclusion.md
---

