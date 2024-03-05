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
1. Block level tag
2. inline tag 

1. Semantic tag - 
2. Non-Semantic Tag - div, span