+++
title = "cinnamon-browser"
weight = 3
extra.displayed_filename = "cinnamon.md"
extra.url = "https://git.arslaancodes.com/cinnamon-browser.git/about/"
+++

A lightweight suckless-inspired vimlike browser written in C, powered by WebKit2GTK-4.1 and GTK3.

- Built with: C, GTK3, WebKit2GTK
- Status: Completed

---

## Features

- Vim-like keybindings
- Command mode with `:`
- Quickmarks (similar to ones in qutebrowser)
- Tabs
- Hint mode
- Suckless-style C configuration file (config.h)

---

## Why I built it

For a while, I was a long-time user of qutebrowser, a popular vim-like browser written in Python and PyQtWebEngine. It was a great browser, and worked very well for my use cases, but eventually, I ran into an issue: the browser was too heavy on my system. Even though back then I used a MacBook Pro M2, which is a powerful machine, I only had 8GB RAM, which, in this digital world, is absolutely nothing. Open too many Chrome tabs? Good luck, mr. OOM killer has come to your doorstep. Because qutebrowser is powered by PyQtWebEngine, which in turn is powered by Chromium, it tends to be quite heavy on my system and eat a lot of RAM.

So, to fix this problem, there was only one proper way. MAKE YOUR OWN BROWSER IN C AND WEBKITGTK!!!!!!!!!!!!!!!!!!!!!!!!!

---

## Notes

This project will eventually be deprecated as I plan to rewrite it in Saffron, my UI framework. Why, you might ask? Because who doesn't want to have a custom browser written in their own custom UI framework AND their own custom browser engine bindings for that UI framework?! How, you might ask? With SFWK, of course! Did you not read the project listings above?


