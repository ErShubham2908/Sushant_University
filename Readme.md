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

## Ordered List
#### Ordered List Tags
Tag - < ol> Tag - ordered List
Tag - < li> - List Item
#### Ordered List Attrbutes
type - Five type (1, A, a, I, i)
reversed - Reverse your list
start - Accept number as input

## Q. Ordered List start with "z" and end with "p"

### Unordered List 
#### Unordered List Tags
Tag - < ul> (unordered list)
Tag - < li> (list item)

#### Unordered List Attributes
Attributes - type - circle, disc, squre, none

## Description List
Tag -
dl - Description list
dt - definition term
dd - definition description

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
5. Fixed - Elements with **position: fixed;** are positioned relative to the viewport, meaning they stay in place even when the page is scrolled. This is useful for creating elements that stay visible while scrolling, like navigation bars or sidebars. Similar to absolute positioning, top, bottom, left, and right properties are used for placement. Fixed elements also create gaps in the flow.


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

# 12th Mar

### Z-index

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