# CSS

# Rules
Properties indicated lower will prevail over properties above (file order)

For wrapping and aligning there needs to be dimensions indicated

no overflow allowed
```CSS
selector {
    property: value;
    property: value;
}

h1 {
    color: red;
    font-size: 12px;
}
```

# Border box model
## Margin
## Border
## Padding

# Units
vh/vw(?) view height/width (not sure about width): %age of the view port
px: pixels
%: %age of the parent

# Media Query
getting everything if the screen is under 1000 pixels:
```CSS
@media all and (max-width: 1000px) {
}

getting everything if the screen is under 500 pixels:
@media all and (max-width: 500px) {
}
```

# Align and Justify
align is on the horizontal axis?
justify is on the vertical axis?
NO it's more "main" axis and "other" axis


# Import
@import + link at the top of the CSS file
eg: @import url('https://fonts.googleapis.com/css?family=Montserrat+Alternates:900');

# wildcard

```CSS
* {
    box-sizing: border box;
}
```

# accessing a class
You can have more than one class in the html eg <p class="center large">
```CSS
.center {
    ...
}
```

```CSS
.theNameOfAClass {
    ...
}
``` 

# accessing an id
```CSS
#theID {
    ...
}
```

# accessing multiple things at once
```CSS
#image1, .font8, a {
    color: brown;
}
```

# Flexbox


 justify-content property, which aligns items horizontally and accepts the following values:

    flex-start: Items align to the left side of the container.
    flex-end: Items align to the right side of the container.
    center: Items align at the center of the container.
    space-between: Items display with equal spacing between them.
    space-around: Items display with equal spacing around them.

For example, justify-content: flex-end;

# flex:
flex-grow: 1;
flex: 1;

enables elements to grow, the higher the number, the more space will be attributed to the object proportionnaly


box-sizing: border-box;
box-sizing: content-box;

display: flex;

flex-wrap: wrap;
flex-direction: row;
flex-grow: 1;


min-height: 1vh;
width: 1000%;
max-width: 25%;

align-item: center;
align-content:
align-self:



background-image: linear-gradient(260deg, #2376ae 0%, #c16ecf 100%);
```CSS
a:hover {
  background: rgba(0, 0, 0, 0.3);
}

  .flex-nav ul li {
    width: 50%;
  }
```

# Selectors
## colon
## double colon
## coma space no space AND OR

# Animation
## keyframes


## justify-content
Aligns flex items along the main axis.
flex-start (default), flex-end, center, space-between, space-around, space-evenly


## align-items
Aligns flex items along the cross axis.
flex-start, flex-end, center, baseline, stretch (default)


