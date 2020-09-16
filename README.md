# HTML W3CSS Template base

W3 CSS templates. w3 css pure templates is a new, faster and lighter way than engines based on java scripts to build their themes.
It is my favorite to build simple projects.

This folder contains our themes designed by us from scratch, to learn how to make HTML / CSS themes with the use of w3.css and the separation of HTML and CSS code.

This design tries to make maximum impact on simplicity, cleanliness and readability.

It contains three variants of the same design:

- Complete page, with header and footer.
- Same with a side.
- Same with two sides.
- Sample SVG logo, colours are not import here

The colors and elements have been designed with sizes and tones to facilitate layout.

## About colours.

The colors are not important here, colors with strong contrast have been chosen to facilitate the layout and easily differentiate the areas where you are working, finally, many times everything becomes white or at most two colors.

All my design start at this point and could be translate to TWIG later.

## About the body section.

As complementary help for layout, a hight identifiable color and a cross image are added to body background.
Thats help me to identify clear spaces between objects and the cross help me to align objects better.
You can chose use or remove from the style.css file.

```css
body {
    background-color: lightgray;
    background-image: url(../cross.svg);
    background-size: 10px;
}
```