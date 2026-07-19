+++
title = "SaffronWebKit"
weight = 2
extra.displayed_filename = "sfwk.md"
extra.url = "https://git.arslaancodes.com/saffronwebkit.git/about/"
+++

WPEWebKit bindings for Saffron, allowing you to embed webview widgets into any Saffron app with just a few lines of C.

- Built with: C, SDL3, WPEWebKit, GStreamer, EGL
- Status: Completed - in active development

---

## Features

- Full WebKit browser engine embedded into Saffron
- Supports Wayland, X11, and even runs in a TTY via SDL3's kmsdrm driver
- Full audio playback via GStreamer
- WebGL, HTML5 multimedia, and many other web APIs via WebKit

---

## Why I built it

When I was building Saffron, I thought it'd be really cool to rewrite cinnamon-browser with it once it was stable. The issue was, it's a custom UI framework, how does one put a browser in it? The answer: just write your own bindings! It can't be that hard... right? Right???? Right...

This took up way too much time and effort than I thought it would.

---

## Notes

While Saffron itself is cross-platform, I cannot guarantee that SFWK will work across platforms because WPEWebKit, the library it is based on, is very much Linux-only.
I am also yet to write documentation, but I am currently delaying that until Saffron itself has a stable API, because SFWK is subject to change based on what happens in Saffron's codebase.
