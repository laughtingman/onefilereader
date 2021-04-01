# onefilereader
Extreamly light FB2 reader in one html file

[Demo here](https://laughtingman.github.io/onefilereader/index.html)

## Features
1. Open `.fb2` and `.fb2.zip` files
1. Detect correct encoding
1. Show book info: cover, annotation, author, etc.
1. Show footnotes in floating panel
1. Show embedded images
1. Can add white background to transparent (png) images on dark themes
1. Change font family, size and colors
1. Show reading progress as a percentage
1. Store current book and reading progress in localStorage (and indexedDB for large books over 5MB)
1. Automatic add non-breaking spaces for more comfortable
1. Show active table of contents with highlighting of the current chapter


## Dependencies
1. [Vue.js](https://github.com/vuejs/vue) 2.6.9
1. [jsZip](https://github.com/Stuk/jszip) 3.5.2