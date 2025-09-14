# Playing Cards Assets

This directory contains the card assets for the Spades Cookout Edition game.

## Contents

- **svg-cards/**: Vector (SVG) playing card graphics
- **png/**: Rasterized (PNG) playing card graphics  
- **svg2png.js**: Script to convert SVG cards to PNG format
- **Makefile**: Build script for generating PNG assets

## Source

Card graphics courtesy of https://code.google.com/p/vector-playing-cards/ (public domain)
Additional processing has been done to remove borders from cards.

## Building PNG Assets

To build the PNG assets with parallel processing:

```bash
make -j 4 png
```

## Tools Required

- [xmlstarlet](http://xmlstar.sourceforge.net/) - to remove border paths from SVG files
- [svg2png](https://github.com/domenic/svg2png) - to convert SVG to PNG (based on PhantomJS)