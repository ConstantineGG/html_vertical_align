# html_vertical_align

This is a comprehensive example of vertically aligning the content of an entire page using the `vertical-align: middle` CSS property of a **table-cell** element. The same tactic can be applied to specific sections of a page if needed.

First, create a *\<table\>* containing a single *\<td\>* element. 

We must ensure that the *\<table\>* element inherits the size of its parent element, we must set the properties `height: 100%; width: 100%;` on it.

In this example we want to vertically align the content of the entire viewport. Therefore we must also ensure that the table's parent element, the *\<body\>*, takes up the full height of the screen. We do this by setting `height: 100%` on both the *\<html\>* and *\<body\>* elements.

Lastly, we apply `vertical-align: middle` to the *\<td\>* element and place out content inside it.

Enjoy!

~ Constantine
