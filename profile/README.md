# Helheim Emacs

**Helix-style modal editing for Emacs — and a framework built on it.**

Several projects live here — it's worth knowing which one come for.

## Hel — the core

[**Hel**](https://github.com/helheim-emacs/hel) is a [Helix](https://helix-editor.com/) emulation layer for Emacs.

**TL;DR:** Hel is to Helix what Evil is to Vim.

- Selection → action modal editing model.
- Multiple cursors that play well with Emacs' native undo/redo.
- PCRE regexps by default.
- Smooth scrolling out of the box.

## Helheim — the framework

[**Helheim**](https://github.com/helheim-emacs/helheim) is an Emacs modular
configuration framework built around Hel.

**TL;DR:** Helheim is to Helix what Spacemacs or Doom are to Vim.

A curated, preconfigured Emacs distribution: sane defaults, tree-sitter,
batteries included.

Take this if you just want to give it a try, don't want to configure
everything yourself, or need a foundation to build your own Emacs config
on. Helheim is modular to the core: `require` only the modules you want,
and configure the rest however you like.

## hel-collection and other extensions

All the building blocks Helheim is built from, for constructing your own
system.
