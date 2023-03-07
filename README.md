# READ.ME

In a book project with Quarto 1.3.247 (and 1.3 versions before) there is an issue with cross references when the document contains a list (numbered or bulleted), and later in the document a callout with a figure in it. Rendering gives then a warning: unable to resolve crossref.

Commenting out the list clears the error. And when the list is after the callout then also no problem.

Furthermore there are no problems when rendering with Quarto version 1.2.335
