# onefilereader
Extreamly light FB2 reader in one html file

[Demo here](https://laughtingman.github.io/onefilereader/index.html)

## Features
1. Open `.fb2` and `.fb2.zip` files
2. Detect correct encoding
3. Show footprints in floating panel
4. Show including pictures and book cover
5. Can add white background to transparent (png) pictures on dark themes
6. Change font, size and colors
7. Store current book and reading progress in localStorage (and indexedDB for large books over 5MB)
8. Automatic add non-breaking spaces for more comfortable

## Dependencies
1. [Vue.js](https://github.com/vuejs/vue) 2.6.9
2. [jsZip](https://github.com/Stuk/jszip) 3.5.2