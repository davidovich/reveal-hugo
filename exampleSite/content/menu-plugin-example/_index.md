+++
title = "menu-plugin-example"
description = "Shows how a Reveal.js plugin can be added and used"
outputs = ["Reveal"]
[reveal_hugo]
theme = "night"
margin = 0.2
plugins = ["plugin/reveal.js-menu/menu.js"]
+++

# menu-plugin-example

---

{{% slide menu-title="intro" %}}

This presentation demonstrates how a Reveal.js plugin can be added.

---

The plugin is called [reveal.js-menu](https://github.com/denehyg/reveal.js-menu).

---

It installs a menu on any slide. Click the hamburger in the bottom left corner.

---

These were the steps to use this plugin for this reveal-hugo presentation.

---

### 1

Copy the plugin CSS and JavaScript into the static directory

---

### 2

Add the JavaScript file path to the `plugins` field in the front matter

---

### 3

Create a `head.html` partial inside of `layouts/partials/plugin-example/reveal-hugo`

---

### 4

In `head.html`, add a stylesheet link tag that loads the plugin CSS

---

## THE END
