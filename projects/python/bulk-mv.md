# bulk-mv

bulk-mv is an interactive tool that does what the `mv` command does, but for mulitiple files, with the ability to do more like adding and deleting files as well.

[REPO LINK](https://github.com/angarc/bulk-mv)

## Installation

``` bash
pip install bulk-mv
```

## Usage

When you run `bmv [path]`, a vim buffer with a representation of the file tree starting at the directory at `[path]` will open.

Something like this:

``` bmv
web/
web/pages/
web/pages/a.html
web/pages/b.html
web/static/
web/static/main.css
web/static/main.js
web/images/ 
web/images/photo.jpg
web/images/delete_me.jpg
```

Say you wanted to:

1. Delete the `delete_me.jpg` file.
2. Move the `images` folder to the `static` folder.
3. Rename `main.js` to `script.js`
4. Create a `web/fonts/` folder

You would write:

``` bmv
+ web/fonts/

web/
web/pages/
web/pages/a.html
web/pages/b.html

web/static/
web/static/main.css
web/static/main.js -> web/static/script.js

web/images/ => web/static/images/
web/images/photo.jpg
- web/images/delete_me.jpg
```

When you save and quit vim, `bmv` will perform all the operations.
