# Justfile syntax for TextMate

A TextMate language grammar for [`justfile`](https://github.com/casey/just) — the
command runner. Syntax highlighting for recipes, variables, attributes, shebang
recipes, and the usual `just` directives.

> **Unmaintained.** I wrote this for my own use and it does what I need. I'm not
> reviewing issues or pull requests — fork it and take it wherever you like.
> MIT licensed.

## Install

```sh
git clone https://github.com/cristbc/textmate-justfile.git \
  ~/Library/Application\ Support/TextMate/Bundles/Justfile.tmbundle
```

Restart TextMate. Files named `justfile`, `Justfile`, `.justfile`, or `*.just`
pick up the grammar automatically.

## What's here

| File | Purpose |
|---|---|
| `Syntaxes/Justfile.tmLanguage` | The grammar itself |
| `info.plist` | Bundle metadata |
