+++
title = "Saffron"
weight = 1
+++

# [Saffron](https://git.arslaancodes.com/saffron.git/about/){: .white target="_blank" }

A lightweight, extensible, and dead-simple retained-mode UI framework written in C and SDL3.

- Built with: C, SDL3
- Status: In development (alpha)

---

## Features

- Retained-mode widget system
- GL support
- Extensible and modular
- Consistent styling across platforms

---

## Why I built it

I looked at the current state of UI frameworks.
- GTK: Not very good on platforms other than Linux, and kind of bloated.
- Qt: Licensing headache, and styling is not consistent across platforms.
- Dear ImGui: Not retained-mode.
- Flutter: The toolchain is horrible, Dart sucks, and it's bloated.

And so, as I do, I decided to make my own lightweight and extensible UI framework on top of SDL3.

---

## Notes

There are currently a few things TODO in Saffron, as it is currently in alpha. For this reason, I would not recommend using it in production at the moment.

1. Write documentation
2. Test for other platforms (just because it theoretically should work, doesn't mean it will)
3. Add more built-in widgets
4. Possibly split it into 2 modular parts, SFCore and SFWidgetsBase (?)
