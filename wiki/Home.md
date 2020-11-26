# Welcome to wiki.brisberg.dev Wiki!

This site is built using [Hugo](https://gohugo.io).

## Inspiration
This repo represents a knowledge repository of everything [@brisberg](https://github.com/brisberg) knows and is learning.
Original inspiration: [Nikitavoloboev's Knowledge Wiki](https://wiki.nikitavoloboev.xyz/)

### Improvements

#### Light/Dark Theme
Hugo-Book comes with an `auto` theme selection where it will select a white/dark theme based on OS preferences. This is nice, but it would be a bit better to give the user control.

I could integrate a `light/dark theme toggle` similar to the toggle in [zDoc](https://themes.gohugo.io/hugo-theme-zdoc/)

This could even include local storage, but possibly session storage would be better so it will be overwritten by OS prefs each reload.

#### CTA Buttons

I need several CTA buttons to link back to `home` (brisberg.dev), `blog` (blog.brisberg.dev), and `github` (github.com/brisberg/wiki.brisberg.dev).

Currently they are included with template injection and `menu.after`. It would be better to highlight them at the top to distinguish them from topic categories.

#### Image Attribution CSS

I should find a way to layer in CSS into the Markdown files. Sepcifically, I want to include a "Image From \<source>" line below images I use from other people. This attribution line should be smaller and centered.

Currently I can embed html directly in markdown, but I would prefer to have a CSS sheet for this purpose.
