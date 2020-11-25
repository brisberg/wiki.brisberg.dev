# Welcome to wiki.brisberg.dev Wiki!

## Inspiration
This repo represents a knowledge repository of everything [@brisberg](https://github.com/brisberg) knows and is learning.
Original inspiration: [Nikitavoloboev's Knowledge Wiki](https://wiki.nikitavoloboev.xyz/)

## Hugo
This site is built using [Hugo](https://gohugo.io).

### Themes
#### Hugo-Book
Currently I have decided to build my site using the simplistic [Hugo-Book](https://themes.gohugo.io/theme/hugo-book/) theme.

It has many of the things I need:

- Tree view for navigating topics
- Simple and effective shortcodes
- Table of Contents
- Git Integration for editing / last edit time
- Dark Theme

#### zDoc
I previously attempted to use the simple [zDoc] theme.

However, I found it a bit more cumbersome and visualy more noisy than I intended. It doesn't match the `Minimal` theme of [brisberg.dev] as well as I'd like.

My previous attempt is preserved in this [branch](https://github.com/brisberg/wiki.brisberg.dev/tree/zDoc) for posterity.

### Improvements
Hugo-Book comes with an `auto` theme selection where it will select a white/dark theme based on OS preferences. This is nice, but it would be a bit better to give the user control.

I could integrate a `light/dark theme toggle` similar to the toggle in [zDoc](https://themes.gohugo.io/hugo-theme-zdoc/)

This could even include local storage, but possibly session storage would be better so it will be overwritten by OS prefs each reload.


[brisberg.dev]: https://brisberg.dev
[zDoc]: https://themes.gohugo.io/hugo-theme-zdoc/
