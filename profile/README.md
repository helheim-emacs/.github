# Helheim Emacs

**Helix-style modal editing for Emacs — and a framework built on it.**

Several projects live here — it's worth knowing which one you come for.

## [Hel](https://github.com/helheim-emacs/hel) — the core

**TL;DR:** Hel is to Helix what Evil is to Vim.

Hel is a [Helix](https://helix-editor.com/) emulation layer for Emacs.

- Selection → action modal editing model.
- Multiple cursors that play well with Emacs' native undo/redo.
- PCRE regexps by default.
- Smooth scrolling out of the box.

## [Helheim](https://github.com/helheim-emacs/helheim) — the framework

**TL;DR:** Helheim is to Helix what Spacemacs or Doom are to Vim.

Helheim is an Emacs modular configuration framework built around Hel.
It gives you a curated, preconfigured Emacs distribution with sane defaults,
tree-sitter and batteries included.

Take this if you just want to give it a try, don't want to configure
everything yourself, or need a foundation to build your own Emacs config
on. Helheim is modular to the core: `require` only the modules you want,
and configure the rest however you like.

## [hel-collection](https://github.com/helheim-emacs/hel-collection) and other extensions

All the building blocks Helheim is built from, for constructing your own
system.
