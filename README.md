Strapdown.js preview in Sublime Text 2
======================================

Sublime Text 2 plug-in that allows you preview your markdown files in your browser, using
[Strapdown.js](http://strapdownjs.com/).

Strapdown.js is mixing some Javascript with [Bootstrap](http://twitter.github.com/bootstrap/)
(Twitter's HTML5 & CSS framework) to show you beautiful presentation of your markdown files.

If you have [LiveReload plug-in](https://github.com/dz0ny/LiveReload-sublimetext2) installed, your
browser will auto-magically refresh page on every page-save.

## Installation :

 - you should use [Sublime Package Manager](http://wbond.net/sublime_packages/package_control#Features)
 - use `cmd+shift+P` then `Package Control: Install Package`
 - look for `Strapdown Preview` and install it.

## Usage :

 - use `cmd+shift+P` then `Strapdown Preview` to launch a preview
 - or bind some key in your user key binding, using a line like this one:
   `{ "keys": ["ctrl+shift+m"], "command": "strapdown_preview", "args": {"target": "browser"} },`
 - once displayed, the output will be updated on file save (LiveReload feature)

### Custom theme / title :

You can specify additional details on top of your text file / active window. These details can
change theme and the title of rendered file. Just add a comment near the start, like this:

```
<!-- 
  title: This file's title
  theme: cerulean
-->
```

## Licence :

The code is available at [GitHub](https://github.com/michfield/StrapdownPreview) under MIT licence.
