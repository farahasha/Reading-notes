# **Images**
# Adding Images
* < img >
  - To add an image into the page
  - It must carry the following two attributes:
    - src
      - This tells the browser where it can find the image file. This will usually be a relative URL pointing to an image on your own site.
    - alt
      - This provides a text description of the image which describes the image if you cannot see it. 
    - title
      - provide additional information about the image. Most browsers will display the content of this attribute in a tootip when the user hovers over the image.
   

# Height & Widthof Images
* height
  - This specifies the height of the image in pixels.
* width
  - This specifies the width of the image in pixels.

<img src="https://th.bing.com/th/id/R79b8c40362fb17e160494bbb77a6ecf5?rik=whkQGqZ7vj%2bEfQ&riu=http%3a%2f%2fdailyusefulentertaining.jpg">

# Where to Place Images in Your Code
* before a paragraph
  - The paragraph starts on a new line after the image.
* inside the start of a paragraph
  - The first row of text aligns with the bottom of the image.
* in the middle of a paragraph
  - The image is placed between the words of the paragraph that it appears in.

# Aligning Images Horizontally
* align 
 ### used to indicate how
the other parts of a page should
flow around an image. 
  - left
    - This aligns the image to the left (allowing text to flow around its right-hand side).
  - right
    - This aligns the image to the right (allowing text to flow around its left-hand side)


# Aligning Images Vertically
* top
  - This aligns the first line of the surrounding text with the top of the image.
* middle
  - This aligns the first line of the surrounding text with the middle of the image.
* bottom
  - This aligns the first line of the surrounding text with the bottom of the image


# Figure and Figure Caption
* < figure>
  - to contain images and their caption so that the two are associated You can have more than one image inside the < figure > element as long as they all share the same caption
* < figcaption> 
  - to allow web page authors to add a caption to an image. Before these elements were created there was no way to associate an < img> element with its caption.

<img src="https://image.slidesharecdn.com/htmlpdf-150429083142-conversion-gate01/95/the-other-side-of-html-7-638.jpg?cb=1430309875">

__________________
__________________
# color
* The color property allows you to specify the color of text inside an element.
  - rgb values
    - These express colors in terms of how much red, green and blue are used to make it up. For example: rgb(100,100,90)
  - hex codes
    - These are six-digit codes that represent the amount of red, green and blue in a color, preceded by a pound or hash sign. For example: #ee3e80
  - color names
    - There are 147 predefined color names that are recognized by browsers. For example: DarkCyan  

<img src="https://th.bing.com/th/id/OIP.Hf_M7kUcGOXRyqZf3QyyZgHaJl?pid=ImgDet&rs=1>

# Background Color
* background-color
<img src="https://th.bing.com/th/id/Rd7f1a9da3313cd23e7357968e67dd437?rik=FpAg%2ffmCeWUVtw&pid=ImgRaw">



# Text 
* Specifying Typefaces
  - The font-family property allows you to specify the typeface that should be used for any text inside the element(s) to which a CSS rule applies. The value of this property is the name of the typeface you want to use. 
* Size of Type 
  - The font-size property enables you to specify a size for the font. 
  - There are several ways to specify the size of a font. The most common are:
    - pixels
    - pixels
    - ems


# Bold
* font-weight 
  - The font-weight property allows you to create bold text. 
  - There are two values that this property commonly takes:
    - normal
      - This causes text to appear at a normal weight.
    - bold
      - This causes text to appear bold

# Italic 
* font-style
  - italic
    - This causes text to appear italic        

<img src="https://th.bing.com/th/id/OIP.W8uZ8F1sYAEfoPQanuxAuwHaFL?pid=ImgDet&rs=1">

<img src= "https://th.bing.com/th/id/OIP.Nn02vyufgaIQpWN-G3tLWwHaHa?pid=ImgDet&rs=1">

# UpperCase & LowerCase
* text-transform
  - used to change the case of text giving it one of the following values:
    - uppercase
      - This causes the text to appear uppercase.
    - lowercase
      - This causes the text to appear lowercase.
    - capitalize
      - This causes the first letter of each word to appear capitalized

# Underline & Strike
* text-decoration
  - The text-decoration property allows you to specify the following values:
    - none
      - This removes any decoration already applied to the text.
    - underline
      - This adds a line underneath the text.
    - overline
      - This adds a line over the top of the text.
    - line-through
      - This adds a line through words.
    - blink
      - This animates the text to make it flash on and off


# Leading
* line-height
  - use for the vertical space between lines of text.


# Letter & Word Spacing
* letter-spacing 
* word-spacing

<img src="https://th.bing.com/th/id/R38391d567b6a2292515de4d2991efa03?rik=W2hWH%2f0zdA5o%2fg&pid=ImgRaw">

# Alignment
* text-align
  - The text-align property allows you to control the alignment of text. The property can take one of four values:
    - left
      - This indicates that the text should be left-aligned.
    - right
      - This indicates that the text should be right-aligned.
    - center
      - This allows you to center text.
    - justify
      - This indicates that every line in a paragraph, except the last line, should be set to take up the full width of the containing box.

# Vertical Alignment
* vertical-align

# Styling Links


<img src="https://image3.slideserve.com/6830748/example-of-css-link-styling-n.jpg">
                                                                                  
 # TL;DR
Use JPEG format for all images that contain a natural scene or photograph where variation in colour and intensity is smooth. Use PNG format for any image that needs transparency or for images with text & objects with sharp contrast edges like logos. Use GIF format for images that contain animations.
