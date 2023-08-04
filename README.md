link for the project:https://manuhegde198924.github.io/colormarker2/
in html we have used div inside div , a case of nesting
in div we have given names to 2 classes

1....border-left is a shorthand to set the below property values.
Property Values: 

    border-width: It is used to set the width of border.
    border-style: It is used to set the style of border. Its default value is ‘none’.
    border-color: It is used to set the color of border.
    initial: This property is used to set border-bottom to its default value.
    inherit: This property is inherited from its parent.
2...Linear Gradients    It includes the smooth color transitions to going up, down, left, right, and diagonally. The minimum two-color required to create a linear gradient.
    More than two color elements can be possible in linear gradients. The starting point and the direction are needed for the gradient effect
    3.....text-align:
  The text-align property in CSS is used to specify the horizontal alignment of text in an element ie., 
  it is used to set the alignment of the content horizontally, inside a block element or table-cell box.

Syntax:text-align: left|right|center|justify|initial|inherit;

    4.....background color:
        The background-color property in CSS is used to specify the background color of an element. The background covers the total size of the element with padding and border but excludes margin. It makes the text so easy to read for the user. 

Syntax:

element {
    background-color property
}

Default value : It has a default value i.e. transparent.

Property Values:

    color: It defines the background color value or color codes. For example: A color name can be given as: “green” or HEX value as “#5570f0” or RGB value as “rgb(25, 255, 2)”.

Syntax:

element {
    background-color: color_name;
}

Example: 

    5......box shadow:
    The box-shadow property in CSS is used to give a shadow-like effect to the frames of an element. 
    The multiple effects can be applied to the element’s frame which is separated by the comma.
    The box-shadow can be described using X and Y offsets relative to the element, blur and spread radius, and color.
    
    6:height  and width: for changing height and width
    7.
    margin:
    CSS Margins: CSS margins are used to create space around the element. We can set the different sizes of margins for individual sides(top, right, bottom, left).

Margin properties can have the following values:

    Length in cm, px, pt, etc.
    Width % of the element.
    Margin calculated by the browser: auto.
    hsl:The hsl() function is an inbuilt function in CSS that is used to define the colors using the Hue-saturation-lightness model (HSL).

Syntax: 

hsl( hue, saturation, lightness )

Parameters: This function accepts three parameters as mentioned above and described below: 

    hue: This parameter is used to define the degree on the color wheel. Its value lies between 0 to 360 where 0 or 360 represents red, 120 represents green and 240 represents blue.
    saturation: This parameter is used to define saturation where 0% represents a shade of gray and 100% represents a full color.
    lightness: This parameter is used to define lightness where 0% represents black, 50% represents normal, and 100% represents white.
    hsla:
    The hsla() function is an inbuilt function in CSS that is used to define the colors using the Hue Saturation Lightness Alpha (HSLA) model.

Syntax:
hsla( hue, saturation, lightness, alpha )

Parameters: This function accepts four parameters as mentioned above and described below:

    hue: This parameter is used to define the degree on the color wheel. Its value lies between 0 to 360 where 0 or 360 represents red, 
    120 represents green and 240 represents blue.
    saturation: This parameter is used to define saturation where 0% represents a shade of gray and 100% represents a full color.
    lightness: This parameter is used to define lightness where 0% represents black, 50% represents normal, and 100% represents white.
    alpha: This parameter is used to define the opacity and the value lies between 0.0 (fully transparent) and 1.0 (fully opaque).
    displa-inline:
    The display property in CSS is a very useful and commonly used property that contains many values. The display property defines how an HTML element should be displayed on the webpage. The property also specifies the type of box used for an HTML element and how it should be laid out on the page. If we need to display the elements that are laid out as inline elements, or laid out as inline-level block containers, then the display: inline and display: inline-block properties will be implemented. In this article, we will see the display property, along with understanding the 2 different property values for the display property, i.e., the display:inline and display:inline-block property, among several other properties, & finally, will understand their basic differences & implementation through the examples.

“display: inline” Property: This property is used to display an element as an inline element (like <span>). The height and width properties are not affected on display: inline; property. It allows only the left and right sides of margins, not the top, and bottom. In simple words, it has no line break before and after its neighbor elements and it allows HTML next to it. When the element is declared with display: inline property, then it is treated as an inline element that will not start on a new line. Inline elements also cannot have a width, height, margin, or padding applied to them.

Syntax:

element {
    display: inline;
    // CSS property
}
  padding:
  In this article, we will learn about the CSS Margin & Padding properties of the Box Model & understand their implementation through the example. 

CSS Margins: CSS margins are used to create space around the element. We can set the different sizes of margins for individual sides(top, right, bottom, left).

Margin properties can have the following values:

    Length in cm, px, pt, etc.
    Width % of the element.
    Margin calculated by the browser: auto
  
    
