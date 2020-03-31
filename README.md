# Natours
A record of a CSS tutorial
## INHERITANCE:WHAT YOU NEED TO KNOW
* Inheritance passes the values for some specific properties from parents to children —— **more maintainable code**
* Properties related to text are inherited: font-family, font-size, color, etc;
* The computed value of a property is what gets inherited, **not** the declared value.
* Inheritance of a property only works if no one declares a value for that property;
* The inherit keyword forces inheritance on a certain property;
* The initial keyword resets a property to its initial value.
## THE VISUAL FORMATTING MODEL
* **Dimentions of boxes**: the box model;
* **Box Type**: inline, block and inline-block;
* **Positioning Scheme**: floats and positioning;
* **Stacking contexts**;
* Other elements in the render tree;
* Viewport size, demensions of images, etc.
## THE BOX MODEL
* **Content**: text, image, etc;
* **Padding**: transparent area around the content, inside of the box;
* **Border**: goes around the padding and the content;
* **Margin**: space between boxes;
* **Fill area**: area that gets filled with backfround color or backfround image.
* **total width** = right border + right padding + specified width + left padding + left border
* **total height** = top border + top padding + specified height + bottom padding + bottom border
