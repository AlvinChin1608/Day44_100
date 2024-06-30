# Day44_100
I am currently engaged in a 100-day Python Bootcamp, which I am documenting and sharing my progress on GitHub. The boot camp is designed to progressively intensify, allowing me to deepen my understanding and proficiency in Python programming.

Additionally, I have chosen to include the beginner, intermediate and advanced in my documentation to provide a valuable reference for my future growth and development.

----

# What I Learned Today
Today, I explored some essential HTML and CSS concepts that are fundamental for web development. Here’s a summary of what I covered:

## HTML Elements
&lt;div&gt; Element:
The &lt;div&gt; (division) element is a block-level container used to group together HTML elements. It’s often used for styling or scripting purposes and helps structure the content of a webpage.

## CSS Units
px (Pixels):

px is a unit of measurement in CSS that represents a single pixel on the screen. It’s an absolute unit and is commonly used for setting dimensions, margins, padding, and font sizes.
Example: font-size: 16px;
rem (Root EM):

rem is a relative unit that stands for root em. It is relative to the font-size of the root element (&lt;html&gt;). Using rem allows for more consistent and scalable designs, especially when adjusting the base font size.
Example: font-size: 1.5rem; (if the root font size is 16px, 1.5rem equals 24px)

## Fonts
- Font Properties:
  - font-family: Specifies the font of the text.
  - font-size: Defines the size of the font.
  - font-weight: Controls the boldness of the text.
  - font-style: Sets the style of the font, such as normal or italic.

```python
body {
  font-family: Arial, sans-serif;
  font-size: 16px;
  font-weight: 400;
  font-style: normal;
}
```

## Box Model
- Margin:
  - The margin is the space outside the border of an element. It creates space between the element and its neighbors.
  - Example: margin: 10px; (applies a 10px margin on all sides)
  - Individual Sides: margin-top, margin-right, margin-bottom, margin-left
    
- Padding:
  - The padding is the space inside the border of an element, between the content and the border. It creates space within the element.
  - Example: padding: 10px; (applies a 10px padding on all sides)
  - Individual Sides: padding-top, padding-right, padding-bottom, padding-left
    
- Border:
- The border is a line that surrounds the padding and content of an element. It can be styled with different widths, colors, and styles (solid, dashed, etc.).
  - Example: border: 1px solid black; (applies a 1px solid black border)
  - Individual Sides: border-top, border-right, border-bottom, border-left
