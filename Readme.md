# HTML 
HTML - HTML stands for **Hypertext Markup Language**. It's the standard markup language for creating web pages and web applications. HTML provides the structure and content of a webpage by using a system of tags and attributes.

These tags define the various elements of a webpage such as headings, paragraphs, links, images, forms, and more. Web browsers interpret HTML documents and render them into visual web pages for users to view and interact with on the internet.

### What is Tag, Attributes, Elements, and content?
1. Tag : Imagine tags like little instruction manuals for the web browser. They come in pairs, a start tag < and an end tag >  with the element name in between. For example, 
< h1> is a start tag for a heading element, and </ h1> is its closing tag.

Ex - img tag for image, p tag for paragraph, h1 to h6 for heading.

2. Attributes : Attributes provide additional information about HTML elements and are always specified in the opening tag of an element. Attributes are made up of a name and a value, separated by an equal sign (=) and enclosed in double or single quotes. Attributes modify the behavior or appearance of an element.

Ex : the href attribute in an < a> tag specifies the URL of the link, and the src attribute in an < img> tag specifies the source (URL) of an image.

3. Content : This is the information that goes between the start and end tags of an element. It can be text, images, videos, or even other HTML elements (elements can be nested within each other). The content determines what the user sees or interacts with on the webpage.

Ex : `<p>This is Paragraph Content</p>`

4. Elements : An element is a complete set of tags and their content, including the opening tag, closing tag, and any content nested within them. Together, they define a particular component or piece of content on a webpage.

Ex : `<p>This is a Paragraph.</p>`

## Fonts tag in HTML
1. **b tag:** The < b> tag is used to make text bold. However, it doesn't carry any semantic meaning and is purely presentational.
2. **strong tag:** Similar to < b>, the < strong> tag also makes text bold, but it carries semantic weight, indicating that the enclosed text is of strong importance.
3. **i tag:** The < i> tag is used to italicize text. Like < b>, it doesn't carry any semantic meaning and is purely presentational.
4. **em tag:** Similar to < i>, the < em> tag italicizes text, but it carries semantic weight, indicating emphasis.
5. **u tag:** The < u> tag underlines text.
6. **s tag:** The < s> tag is used for strikethrough text, indicating that the content is no longer accurate or relevant.
7. **del tag:** Similar to < s>, the < del> tag also represents strikethrough text, but it carries semantic weight, indicating deleted text.
8. **mark tag:** The < mark> tag highlights text with a background color, typically yellow.
9. **sup:** The < sup> tag is used for superscript text, often used for mathematical expressions.
10. **sub:** The < sub> tag is used for subscript text, typically used for footnotes or chemical formulas.



## List in HTML
1. Ordered List 
   1. Number (Default)
   2. Cap Alpha
   3. Small Alpha
   4. Cap Roman
   5. Small Roman
2. Unordered List
   1. None
   2. Disc
   3. Squre
   4. Circle
3. Description List

# List
- **Definition :** In HTML, a list is a way to organize and display related pieces of content in a structured format. Lists are useful for presenting information in a clear and organized manner, making it easier for users to understand the relationships between different items.

### *Type of HTML List*

**1. Ordered List** An ordered list is defined using the < ol> tag in HTML. Each item within the list is defined using the < li> tag. By default, ordered lists display numbers (1, 2, 3...) to indicate the order of the items.
- Tag: ol tag (ordered list), li tag (list item)
- Attributes:
  - type: This attribute specifies the numbering or lettering style used for the list items. Here are the common options:
    - type="1" (default): Numbers the list items (1, 2, 3...)
    - type="a": Lowercase alphabetical lettering (a, b, c...)
    - type="A": Uppercase alphabetical lettering (A, B, C...)
    - type="i": Lowercase Roman numerals (i, ii, iii...)
    - type="I": Uppercase Roman numerals (I, II, III...)
  - start: This attribute allows you to define a starting number or letter for the list. For example, start="4" would begin the list with "4" instead of "1".
  - reversed: This attribute reverses the order of the numbering or lettering in the list.

**2. Unordered List:** An unordered list in HTML is used to represent a collection of items where the order doesn't necessarily matter. These lists are typically displayed with bullet points to visually group the items.
- An unordered list is defined using the < ul> tag in HTML.
- Each item within the list is defined using the < li> tag.
- By default, unordered lists display bullet points (●, ◦, etc.) for each list item.
- Tag: ul tag (unordered list), 
- Attribute: 
  - type="disc" (default): The standard disc bullet (●)
  - type="circle": A circle bullet (○)
  - type="square": A square bullet (■)
    
**3. Definition List:** Definition lists in HTML provide a structured way to define terms and their corresponding meanings. They are essentially like mini-glossaries embedded within your web page.
- Tag:
  - < dl>: This tag marks the beginning of the definition list.
  - < dt>: This tag defines the term being explained.
  - < dd>: This tag defines the description or definition of the term.
- Attribute: 
  - Definition lists are simple and don't have any specific attributes associated with their tags.
  - The structure relies on the proper nesting of tags:
  - The < dl> tag acts as a container for the entire definition list.
  - Within < dl>, each term being defined is wrapped in a < dt> tag.
  - The corresponding definition or description for the term goes inside a < dd> tag, always following the < dt> tag for the corresponding term.


## Q. Name of Dept. ordered List, name of Prof. (Unordered list)

1. School of Desi
   1. Shubham
2. ABC
   1. wsa

## Table in HTML
tag - table (Parent tag)
tr - Table Row
th - Table Heading
td - table data

attributes - border
rowspan - Merge two row
colspan - Merge two column
cellspacing - Space outside the border
cellpadding - space b/w text and border

## H/W - 26th Feb (Create a 5*5 table, and add rowspan, colspan, cellspacing and cellpedding), table contain heading.

### Date - 28th Feb '24

## Form in HTML
Tag used in Form - form, input, lebal
Attributes used in Form - value, type, name, id, placeholder, etc

## Form contain - Name, Email, Password, Gender with type "Radio" (Male, Female) button (Submit).


### Type of Tag
1. Block level tag - In HTML, block-level elements are elements that start a new line on a web page and take up the full width of their parent element.
Ex:  < div>, < p>, < h1> to < h6>, and < ul>, etc.
2. inline tag -  Inline elements are used within block-level elements to style or format specific parts of the content. They don’t start on a new line and only take up as much width as necessary.
Ex: < span>, < a>, < strong>, and < em>.

1. Semantic tag - A semantic element clearly describes its meaning to both the browser and the developer.
Ex: < img>, < header>, < footer>, < article>, < table>
2. Non-Semantic Tag - div, span

# 5th March '24

## Image and Multimedia
1. **Image** -
   1. Tag - Img tag
   2. Attributes - src (Source), alt (Alternative), width and height
2. **Video**
   1. Tag - Video as parent tag, source tag
   2. Attributes for video tag - control, muted, autoplay, loop, width and height
   3. Attributes for source tag - src
3. **Audio**
4. **Iframe**


# CSS - Cascading Style Sheet
### Class - 
class should be duplicate and represent by . never start with number.
Ex = class = "Abc", "abc", "abc_abc" 
class = 'abc pqr'

### Id - 
Id should be unique and represented by (#).

**1. Inline CSS**
+ Inline CSS involves adding styles directly to individual HTML elements.
+ This is done using the style attribute within the opening tag of the element.
+ It's like a one-time thing, good for making specific changes to a single element.

**2. Internal CSS** 
+ Internal CSS, also called embedded CSS, groups styles together within the < style> element placed in the < head> section of your HTML document.
+ This allows you to style multiple elements within the same webpage without cluttering up your HTML tags.

**3. External CSS** 
+ External CSS offers the most organized approach. Styles are defined in a separate CSS file (with a .css extension) that's linked to your HTML documents using the < link> element in the < head> section.
+ This way, a single CSS file can control the styling of multiple HTML pages, making it ideal for maintaining a consistent look across your website.

**Priority** : inline CSS > Internal CSS > External CSS

## CSS Selector - 
**1. tag selector** - This selects all elements of a specific HTML tag. For example, if you have p as a tag selector, it will select all paragraphs in your HTML document. The syntax is just the tag name, like p, div, span, etc.

**2. class selector** - This selects all elements with a specific class attribute. Class selectors are denoted by a period (.) followed by the class name. Multiple elements can have the same class, and this selector helps to style them consistently.

**3. id selector** - This selects a single element based on its unique ID attribute. ID selectors are denoted by a hash (#) followed by the ID name. IDs should be unique within the HTML document.

**4. group selector** - This allows you to apply the same styles to multiple selectors. You separate the selectors with commas (,). It's useful for reducing redundancy in your CSS code.

**5. Universal Selector** - This selects all elements in the HTML document. It's denoted by an asterisk (*). Be cautious when using this selector as it can significantly affect performance if not used judiciously.

# 6th Mar '24

## CSS Text Formatting

1. color 
2. font-size
3. font-style
4. font-family

## Q1. Create a circle? border - white, background-color - red

## Position Properties in CSS
**Position**- The position property in CSS dictates how an HTML element is positioned relative to its normal flow in the document or other elements. It essentially controls the layout of your webpage by giving you more flexibility in placing elements.
1. Static (Default) - This is the default positioning for all elements. Elements maintain their position in the normal document flow and cannot be moved using top, bottom, left, or right properties. 
2. Relative - With **position: relative;** elements stay in their normal position, but you can use top, bottom, left, and right properties to move them relative to their original spot. Other elements in the document flow won't be affected by the movement.
3. Absolute - Here, elements are positioned relative to the nearest parent element with a non-static position (usually the viewport if not found). You can place them anywhere on the page using top, bottom, left, and right properties relative to the containing block's edges. Absolute elements create gaps in the document flow where they would have been positioned normally.
4. Sticky - This value offers a combination of relative and fixed positioning. With position: sticky;, elements act relatively positioned until they reach a certain scroll point (defined by top or bottom), at which point they become fixed like a fixed element.
5. **Fixed** - Elements with **position: fixed;** are positioned relative to the viewport, meaning they stay in place even when the page is scrolled. This is useful for creating elements that stay visible while scrolling, like navigation bars or sidebars. Similar to absolute positioning, top, bottom, left, and right properties are used for placement. Fixed elements also create gaps in the flow.


## 11th Mar

### box-Model - The combination of Content + padding + Border + Margin
#### Box-Sizing

#### padding - space b/w content and border.
#### border - 1px solid red
#### margin - space b/w border and outer container.

## box-sizing 
1. content-box
2. border-box

### Color -

## implement position proerties in css 
   - fixed and sticky

## H/W - write the code for position absolute and relative

# Z-index
In Cascading Style Sheets (CSS), the **z-index** property controls the stacking order of positioned elements that overlap on a web page. It acts like a layer system, where elements with higher z-index values appear in front of elements with lower values.

**Key Points about z-index:**
+ **Affects Positioned Elements Only:** z-index only works on elements with positioning set to absolute, relative, fixed, or sticky. The default static positioning doesn't participate in the z-index stacking order.
+ **Higher Value on Top:** Elements with higher z-index values are displayed on top of elements with lower values. Think of it as a layer cake, with higher layers appearing in front.
+ **Integers or auto:** z-index values can be positive or negative integers. Positive values stack elements on top, while negative values push them behind other elements in the stacking context. The default value is auto, which is determined by the element's position in the HTML code (elements positioned later in the code appear on top).
+ **Stacking Context:** The stacking order applies within a specific stacking context, which is usually the entire document viewport. However, certain elements can create their own stacking contexts (e.g., elements with opacity: less than 1, mix-blend-mode: not normal, or transform: translateZ()).
+ **Specificity and Inheritance:** If multiple elements have the same z-index, the element with higher specificity in the CSS rules will be stacked on top. z-index is not inherited by child elements.

## CSS Gradient - 
1. linear gredient - 
2. Radial Gredient
3. Conic Gredient



# Display - Grid
1. **display: grid** -  This property is used to define a grid container. It enables a grid context for all direct children of the container.
2. **grid-template-columns:** This property defines the number and size of columns in the grid. You can specify the width of each column individually or use flexible units like fr (fractional unit) to distribute the space evenly. In the example, 1fr 1fr 1fr creates three columns of equal width.
3. **grid-template-rows:** Similar to grid-template-columns, this property defines the number and size of rows in the grid.
4. **grid-gap:** This property sets the gap between grid items (both rows and columns). It can be specified using different units like pixels, ems, or percentages. In the example, 10px sets a gap of 10 pixels between grid items.
5. **grid-column-start:** Specifies the start position of a grid item within the grid columns.
6. **grid-column-end:** Specifies the end position of a grid item within the grid columns.
7. **grid-row-start:** Specifies the start position of a grid item within the grid rows.
8. **grid-row-end:** Specifies the end position of a grid item within the grid rows.



# 27th Mar 2024
## Transition in CSS

# CSS Transform
+ The transform property in CSS allows you to manipulate the positioning and visual appearance of elements by applying 2D or 3D transformations. This offers a powerful way to create dynamic and interactive effects without modifying the element's content or layout in the HTML structure.
+ The transform property in CSS allows you to manipulate the positioning and visual appearance of elements by applying 2D or 3D transformations. This offers a powerful way to create dynamic and interactive effects without modifying the element's content or layout in the HTML structure.
+ **Syntax:** transform: none | < transform-function> [< transform-function>];
  + none: Resets any applied transformations, returning the element to its default position.
  + < transform-function>: Individual transform functions like **translate()**, **rotate()**, **skew()**, and **scale()**, which we'll explore in detail below.
+ **Transform Functions:**
1. **translate(x, y):**
   + Moves an element horizontally (x-axis) and/or vertically (y-axis) relative to its original position.
   + Positive values move the element to the right (x) and down (y).
   + Negative values move the element to the left (x) and up (y).
   + Units can be pixels (px), percentages (%), or viewport units (vh, vw).
   + **Syntax:** translate(tx, ty), where tx is the horizontal translation and ty is the vertical translation.
2. **rotate(angle):**
   + Rotates an element clockwise around its center point.
   + Angle can be specified in degrees (deg), radians (rad), turns (turn), or gradients (grad). Positive values rotate clockwise, negative values counter-clockwise.
   + **Syntax:** rotate(angle), where angle is the degree of rotation.
   + The rotation point is the center of the element by default, but you can change it using the **transform-origin** property.
3. **skew(x-angle, y-angle):**
   + Skews an element, tilting it along the specified axes.
   + Positive x-angle skews to the right, negative to the left.
   + Positive y-angle skews downwards, negative upwards.
   + Angles are specified in degrees (deg).
   + **Syntax:** skew(ax, ay), where ax is the horizontal skew angle and ay is the vertical skew angle.
4. **scale(x, y):**
   + Scales (resizes) an element proportionally or non-proportionally.
   + A single value scales both axes equally (e.g., scale(2) doubles the size).
   + Two values scale the width (x) and height (y) independently.
   + Values can be percentages (%) or decimal numbers. Values less than 1 shrink the element, greater than 1 enlarge it.
   + **Syntax:** scale(sx, sy), where sx is the horizontal scaling factor and sy is the vertical scaling factor.