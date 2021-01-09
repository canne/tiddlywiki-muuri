## tiddlywiki-muuri - revisited

This is a lonesome fork of a long-gone tiddlywiki-muuri instance of the original author - while no PR is possible it is left here for whoever is interested in it. But please visit the original locations first:

* https://github.com/BurningTreeC/tiddlywiki-muuri

  * To be used instead of this one, of course. Contains installation instructions
  
* https://github.com/haltu/muuri

  * Not to forget to mention the origin of the wonderful algorithms, many thanks!

## What's here? Horizontal (row) alignment and proportional tiddler width

One has two new possibilities for alignment: row/left and row/right. They provide a horizontal alignement of the upper edges of the tiddlers. Motivation for making this was to be able to read multiple synopsis notes side by side without eyes need to jump up and down when the synopsis lengths do not match.

Time to time, one wants to open a tiddler with, say a PDF-file in it... It looks very narrow, too narrow for reaading! But if one sets a tiddler field in it, called `muuri-tiddler-width` and gives it a value, say `3` it will show up wider: for example, it would take half of the available display area for the tiddlers if the number of **muuri** columns is `6`. If it the number of columns is also `3` it will take 100 per cent of the width.

Open the provided `index.html` file and play around with it: drag and drop items, and modify the `muuri-tiddler-width` of some items.

