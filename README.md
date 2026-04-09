# drearylisper.github.io

Personal blog by [@DrearyLisper](https://twitter.com/DrearyLisper), available at **https://drearylisper.github.io**.

## Posts

- [Advent Of Code in Haskell](posts/2021-12-01-aoc-01.markdown)
- [Advent Of Code in Clojure](posts/2023-12-01-aoc.markdown)
- [Random thoughts on having a blog](posts/2023-09-01-random-notes.markdown)

## Stack

- [Hakyll](https://jaspervdj.be/hakyll) — Haskell static site generator
- [Pandoc](https://pandoc.org) — Markdown to HTML
- [GitHub Pages](https://pages.github.com) — hosting, served from `docs/`

## Building

```bash
cabal run site -- build    # incremental build
cabal run site -- rebuild  # full clean rebuild
```

Output is written to `docs/`.
