---
# try also 'default' to start simple
# theme: seriph
theme: apple-basic
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
# background: https://cover.sli.dev
# some information about your slides, markdown enabled
title: 'Neovim: An introduction'
# apply any unocss classes to the current slide
# class: font-mono
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# https://sli.dev/guide/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/guide/syntax#mdc-syntax
mdc: true
layout: statement
class: font-mono
---

# NeoVim
# An introduction

---
layout: statement
class: font-mono
---

# (<span class="color-blue">Neo</span>)(<span class="color-green">Vim</span>)

---
class: font-mono
---

# The **Vim** part

- Text editor
  - 🧠 with **mnemonic** keyboard shortcuts
  - ⚡ providing a **fast** editing experience
  - and a steep learning curve :)
- It's not
  - all-in-one software like emacs
  - IDE
    - even though pepole like to try to make it so
- [(but can be used to solve advent of code problems...)](https://www.youtube.com/watch?v=P7yTg1SdNNQ&ab_channel=denvaar)

<style>
strong {
  @apply color-green
}
</style>

---
class: font-mono
---

# The **Neo** part

- On top of vim
- Configuration via Lua
  - Simple to read and write
  - Fully fledged programming language
- Modern language stuff like auto completion, go to definition, syntax highlighting...
  - Almost anything you can find in VS Code
- (for me) Fuzzy search of files, file contents, help docs
  - (via a plugin)

<style>
strong {
  @apply color-blue
}
</style>

---
class: font-mono
---

# Why not stick to VS Code and avoid headaches?
- True, it offers everything a developer needs
- Can also be configured in many aspects
- ...but I want more...
- (...and it's slow to open)

---
class: font-mono
---

# **My** editor

- I want...
    - _speed of typing_
    - to use the mouse as less as possible
    - to add custom functionality 
    - to have control on more things that happen while developing

<style>
strong {
  @apply color-blue
}
</style>

---
class: font-mono
---

# Demo time
