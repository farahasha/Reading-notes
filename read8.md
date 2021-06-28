# ** Layout **

## * Key Concepts in Positioning Elements *

1. *Building Blocks*
CSS treats each HTML element as if it is in its own box. This box will either be ablock-level box or an inline box.
Block-level boxes start on a new line and act as the main building blocks
of any layout, while inline boxes flow between surrounding text.
 You can control how much space each box takes up by setting the width of the
boxes (and sometimes the height, too).
 To separate boxes, you can use borders, margins, padding, and background colors.

 * Block-level elements start on a new line.
 * Inline elements flow in between surrounding text

 2. *Containing Elements*
If one block-level element sits inside another
block-level element then the outer box is
known as the containing or parent element.
It is common to group a number of elements together inside a <div>
(or other block-level) element. For example, you might group together
all of the elements that form the header of a site (such as the logo and
the main navigation). The <div> element that contains this group of
elements is then referred to as the containing element.

* note:
A box may be nested inside several other block-level elements. The containing element is always the direct parent of that element.

3. *Controll ing the Position of El ements*
CSS has the following positioning schemes that allow you to control
the layout of a page:

* A.
* *Normal flow:
Every block-level element appears on a new line, causing each item to appear lower down the page than the previous one.
Even if you specify the width of the boxes and there is space for two elements to sit side-byside,they will not appear next to each other. 
This is the default behavior (unless you tell the browser to do something else).

* *Relative Positioning:
This moves an element from the position it would be in normal flow, shifting it to the top, right, bottom, or left of where it would have been placed.
 This does not affect the position of surrounding elements; they stay in the position they would be in in normal flow.

 * *Ab solute positioning:
This positions the element in relation to its containing
element. 
It is taken out of normal flow, meaning that it does not affect the position of any surrounding elements (as they simply ignore the space it would have taken up).
Absolutely positioned elements move as users scroll up and down the page.

 
* B.
 To indicate where a box should be positioned, you may also need to use
box offset properties to tell the browser how far from the top or bottom
and left or right it should be placed. 

* *Fixed Positioning:
This is a form of absolute positioning that positions the element in relation to the browser window, as opposed to the containing element.
Elements with fixed positioning do not affect the position of surrounding elements and they do not move when the user scrolls up or down the page.

* *Floating Elements:
Floating an element allows you to take that element out of normal flow and position it to the far left or right of acontaining box. The floated element becomes a block-level element around which other content can flow.

* note:
When you move any element from normal flow, boxes can overlap. 
The z-index property allows you to control which box appears on top.

* *Clearing Floats:
The clear property allows you to say that no element (within the same containing element) should touch the left or righthand sides of a box. It can take the following values:

1. left
The left-hand side of the box should not touch any other elements appearing in the same containing element.

2. right
The right-hand side of the box will not touch elements appearing in the same containing element.
 
 3. both
Neither the left nor right-hand sides of the box will touch elements appearing in the same containing element.

4. none
Elements can touch either side.


* *CREATIing Multi-Column Layouts with Floats:
Many web pages use multiple columns in their design. 
This is achieved by using a <div> element to represent each column. The following three CSS properties are used to position the columns next to each other:
1. width
This sets the width of the columns.

2. float
This positions the columns next to each other.

3. margin
This creates a gap between the columns.


## **Screen Sizes**

Different visitors to your site will have different sized screens that show different amounts of information, so your design needs to be able to work on a range of different sized screens.

The size of a user's screen affects how big they can open their windows and how much of the page they will see. 
There are also an increasing number of handheld devices (mobile phones and tablets) that have smaller screens.

## **Screen Resolution**
the higher the resolution, the smaller the text appears. 
Many mobile devices have screens that are higher resolution than their desktop counterparts.


## **Page Sizes**
<img src ="https://th.bing.com/th/id/OIP.DWbQHYyEhheTqMONorPH2wHaFs?pid=ImgDet&w=800&h=615&rs=1">

*  <div> elements are often used as containing elements to group together sections of a page.
*  Browsers display pages in normal flow unless you specify relative, absolute, or fixed positioning.
*  The float property moves content to the left or right of the page and can be used to create multi-column layouts. (Floated items require a defined width.).
*  Pages can be fixed width or liquid (stretchy) layouts.
*  Designers keep pages within 960-1000 pixels wide,and indicate what the site is about within the top 600 pixels (to demonstrate its relevance without scrolling).
*  Grids help create professional and flexible designs.
* CSS Frameworks provide rules for common tasks.
* You can include multiple CSS files in one page.