---
weight: 1
bookCollapseSection: true
title: "Svelte"
---

# Svelte (3)

[Svelte](https://svelte.dev/) is a radical new approach to building user interfaces. Whereas traditional frameworks like React and Vue do the bulk of their work in the browser, Svelte shifts that work into a compile step that happens when you build your app.

Instead of using techniques like virtual DOM diffing, Svelte writes code that surgically updates the DOM when the state of your app changes.

Svelte 3 (released in late 2019) brings many innovative new features to the web landscape. See their [introductory blog](https://svelte.dev/blog/svelte-3-rethinking-reactivity) post for more.

## Svelte Compiler

Unlike other frameworks which include the framework core as a runtime dependency, Svelte does something different. Svelte is more like a `"compiler"` for `.svelte` files into JavaScript for the browser. This means the framework disappears at build time, and only the portions used by your app are sent to the browser.

This is also how Svelte instraments reactivity, but inserting it into your code at compile time.

## Example App

My sample application written in Svelte can be found at [Svelte Sample](https://github.com/brisberg/svelte-sample).

<hr>

# Sources

[Fireship](https://www.youtube.com/watch?v=043h4ugAj4c&ab_channel=Fireship) - This video by Fireship does a great job introducing the framework and highlighting its killer features compared to other frameworks.
[svelte.dev](https://svelte.dev/) - The main Svelte documentation website
