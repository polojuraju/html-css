# html-css

### Repeating background images
we can use the ```background-repeat``` property sets if/how a background image will be repeated.

syntax: ```background-repeat: repeat|repeat-x|repeat-y|no-repeat|initial|inherit;```
Ex:
```body {
  background-image: url("paper.gif");
  background-repeat: repeat-y; //
}
```
__repeat:__ 	The background image is repeated both vertically and horizontally.  The last image will be clipped if it does not fit. This is default 	
__repeat-x:__ 	The background image is repeated only horizontally 	
__repeat-y:__ 	The background image is repeated only vertically 	
__no-repeat:__ 	The background-image is not repeated. The image will only be shown once

### Box model

css Box model is a container which contains multiple properties including borders, margin, padding and the content itslef. It is used to create the design and layout of webpages.
-- it can be used as a toolkit for customizing the layout of different elements.
Box model has multiple properties:
1. borders
2. margins
3. padding
4. content

The total width of an element should be calculated like this:

```Total element width = width + left padding + right padding + left border + right border + left margin + right margin```

The total height of an element should be calculated like this:

```Total element height = height + top padding + bottom padding + top border + bottom border + top margin + bottom margin```

### centering an element?

```margin : 0 auto```

