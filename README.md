# Reference video

[Watch video](https://www.youtube.com/embed/KP398UANzfw?si=rZW8KDYi1EujsnaW)


# Properties that I was unsure about:
## clip-path: 
    This property is used to clip an element to a basic shape or to an SVG path. In the provided CSS, clip-path: circle(70% at right -20%); is used to create a circular clipping mask for the .circle element, revealing only a portion of it. The circle() function creates a circle, and the at keyword defines the position of the center of the circle.

## transition: 
    This property is used to create smooth transitions between different states of an element. In the provided CSS, .sci li a:hover has transition: 0.15s ease-in-out;, which means that when hovering over the .sci li a elements, the background color will transition smoothly over a duration of 0.15 seconds, with an easing effect applied.

## filter: 
    This property applies graphical effects like blur or color shifting to an element. In the provided CSS, .sci li a img has filter: invert(1);, which inverts the colors of the image. The invert() function takes a parameter between 0 and 1, where 1 means fully inverted colors.

## @media: 
    This is an at-rule used to apply styles based on the characteristics of the device displaying the page, such as screen width or height. In the provided CSS, @media (max-width: 991px) is used to apply styles specifically when the viewport width is 991 pixels or less. Within this media query, various styles are adjusted to make the layout more responsive on smaller screens, such as changing padding, hiding or showing elements, and adjusting font sizes.

## line-height:
    When you set this property to a numeric value (e.g., 1.5), it is a multiplier of the element's font size. For example, if the font size of an element is 16px and line-height is 1.5, the actual height of each line of text will be 24px (16px * 1.5).

## background-repeat
    This property can be used to define how a background image should be repeated or tiled within its containing element. It controls whether the background image should repeat horizontally, vertically, both, or not at all.

## box-sizing
    This property property in CSS is used to control how the width and height of an element are calculated, including its padding and border.

    By default, when you set the width and height of an element, these values are applied to the content area only, and any padding or border added to the element will increase its overall size. This behavior can sometimes lead to unexpected layout issues, especially when using percentages for widths or heights.

    Using box-sizing: border-box; is particularly useful for creating more predictable and consistent layouts, as it allows you to specify the overall size of an element including padding and border, making it easier to control and maintain.

## text-decoration
    This property is used to specify the decoration added to text. It allows you to control the appearance of underlines, overlines, line-throughs, and blinking effects on text.

    Here are the most common values for text-decoration:

    none: This value removes all text decoration, including underlines, overlines, and line-throughs.

    underline: This value adds a solid underline below the text.

    overline: This value adds a solid line above the text.

    line-through: This value adds a solid line through the middle of the text, typically used to indicate deleted or canceled text.

    blink: This value causes the text to blink on and off, although it's not widely supported and considered outdated.