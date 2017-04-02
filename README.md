DnD Theme
===============

This theme is designed to be used in Tiddlywiki to write Dungeons & Dragons 5E modules.

## Setup

To enable custom CSS themes you must modify your core template shadow tiddler to insert a custom HTML `link` referencing the .css file from this theme.

1. Open your tiddlywiki and search for the `Shadow` tiddler category in the right menu.
2. Edit a tiddler called `$:/core/templates/tiddlywiki5.html`.
3. Add the following line in the `head` section:

```
<link rel="stylesheet" href="./themes/DnDTheme/stylesheet.css"/>
```

Now you only need to copy the theme files into that location (relative to you tiddlywiki root folder) and reload the page.
