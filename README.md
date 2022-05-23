<img src="./images/rodneylab-github-open-source-favicon-generation.png" alt="Rodney Lab open-source-favicon-generation Github banner">

<p align="center">
  <a aria-label="Open Rodney Lab site" href="https://rodneylab.com" rel="nofollow noopener noreferrer">
    <img alt="Rodney Lab logo" src="https://rodneylab.com/assets/icon.png" width="60" />
  </a>
</p>
<h1 align="center">
  Open Source Favicon Generation
</h1>

# open-source-favicon-generation

Script for generating optimised favicons from an SVG using open source tools. The code accompanies the <a aria-label="Open Rodney Lab blog post on Svelte Kit Shiki syntax highlighting" href="https://rodneylab.com/open-source-favicon-generation/">post on open source favicon generation</a>. If you have any questions, please drop a comment at the bottom of that page.

## Generate favicons to `./ouput`

This script uses Inkscape, OptiPNG and Scour so you need these installed to run it.

On macOS, you can install them with Homebrew:

```bash
brew install inkscape optipng scour
```

```bash
sh optimised-favicon-generator.sh input-svg-file.svg
```

Feel free to jump into the [Rodney Lab matrix chat room](https://matrix.to/#/%23rodney:matrix.org).
