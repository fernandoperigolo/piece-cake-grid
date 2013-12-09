CSS Grid - Piece of cake
===========

This is my CSS Grid implementation.

To study how it works, check it out the grid.css file. Super easy to understand.

We have basically:

-  a `.group` class just to clear the floats;
-  a `div[class^='column-']` selector to get all div who starts with `column-`. I set the gutter using padding + box sizing;
-  first-child and last-child to remove respective paddings at the begin and end;
-  a total of 12 columns that you can mixin to make your layout. Here, i'm using calc to get the sizes;
-  check it out the code inside class `cake-filling` in index.html file to see a example of usage.

Check it out the demo here, http://fernandoperigolo.github.io/piece-cake-grid/
