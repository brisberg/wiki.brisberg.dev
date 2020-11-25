---
weight: 1
title: "Themes"
---

# Themes

Themes are packages of templates, css, and javascript used by the Hugo engine to produce a Static Site. There are many popular themes to choose from highlighted on [Hugo Themes](https://themes.gohugo.io).

Below are my notes and observations on the few with which I am familiar.

## Minimal

[Minimal](https://github.com/calintat/minimal) is a simple, clean interface and a reasonable amount of features.

[nikitavoloboev](https://nikitavoloboev.xyz) uses it for his home site and I am following in his example to using it for my own [home site][brisberg.dev].

## Book
[Book](https://themes.gohugo.io/theme/hugo-book/) is a minimalist theme specialized for documentation websites.

Book has many of the features ideal for a Knowledge Wiki:

- Flexible, tree-based navigation menu
- Simple and effective [shortcodes](https://github.com/alex-shpak/hugo-book#shortcodes)
- Table of Contents for each page
- Git Integration for calculating last edit time and one-click editing.
- Integrated Search using [flexsearch](https://github.com/nextapps-de/flexsearch)
- Light/Dark Theme

I can currently using this theme for my [Knowledge Wiki](https://wiki.brisberg.dev).

## Zdoc
[Zdoc](https://themes.gohugo.io/hugo-theme-zdoc/) ([Demo](https://zzo-docs.vercel.app/zdoc)) is an opinionated wiki framework for creating documentation websites.

Zdoc differs from Book in the following ways:

- Navigation Menu only displays the current tree level
- Similar [shortcodes](https://zzo-docs.vercel.app/zdoc/shortcodes/)
- Language Dropdown
- Integrated Search using [Fuse.js](https://fusejs.io/)
- Light/Dark Theme toggle

Search experience is better because it includes match previews. Search Index is pre-built and Hugo build time so is fast on the client.

Light/Dark Theme toggle is gives better user control, and saves preference to Local Storage.

However, I found it a bit more cumbersome and visualy more noisy than I intended. It doesn't match the `Minimal` theme of [brisberg.dev] as well as I'd like.

My previous attempt to use this theme is preserved in this [branch](https://github.com/brisberg/wiki.brisberg.dev/tree/zDoc) for posterity.


[brisberg.dev]: https://brisberg.dev
