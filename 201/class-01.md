#  HTML and JavaScript

## FIRST:" * HTML* " 

    

- What's HTML Pages?
- What's the Elements in HTML?
- What's the attributes in HTML?  
- What's the parts of HTML page?




* # the HTML pages :

    the HTML Pages are text documnets and a way to structure it , consist of text marked up by tags and every tag called element with a special informations about its content.

   we can think about HTML as a book with head lines with multible sizes and text with photos and  lines.


* #  the HTML elements :

    - Elements are a small part of code called tags used as a container for the content of web page and tells the browser an information about the  content

    - Tags consist of :
        - Opening tag : Tow angle brackets with a charecter inside of it.
        - Closing tag : Tow angle brackets with a forward slash and a charecter inside of it 
        - Content : The text if it a paragraph or others to show.
        - Attributes : a special information about the tag.
    - Tags types :
        - semantic : Tags with related meaning with the content like Article
        - general : Tags with Genaral meaning like div

![img](https://4.bp.blogspot.com/-B5vUzJXNAoE/Vuay2ygsN2I/AAAAAAAAG5o/-qOAVBa3LRkJ0fPWywYzkAcmezRAY2Rxg/s1600/html-syntax.png)


* # the attributes  :

    - Attributes : it is a way to provide additional information about the contents of an element, they appear on the opening tag of the element and are made up of two parts: a name and a value,separated by an equals sign. 

    - Attributes consist of :
        - Attributes Name : the type of information with equal charcter at the end.
        - Attributes Value : the value of information inside tow qoutation marks.


* # The parts of  HTML page :
    any html page consist of four main elements which are the following:
    - html element : the part which tells the browser what is the type of document will be written by.
    - body element : the part which will be shown in browser with all elements inside.
    - head element : the part which consist a special informations like title and not being show in the browser frame itself. 
    - title element : the part which will be as a title for web page
![img](https://th.bing.com/th/id/Rebb7a6d1feafd66bc3a218967b317444?rik=SAd1V60kisBugg&riu=http%3a%2f%2fdailyusefulentertaining.com%2fwp-content%2fuploads%2f2014%2f07%2fhtml_title_lang.jpg)
___

## SECOND:* Markup*

- What are the versions of HTML?
- What is the DOCTYPE element?
- How do we write commnets in HTML?
- What is the ID and Class attribute?
- what are the types of elements depeding on how they appear?
- What are the div and span Grouping Text & Elements In a Block are ?
- What is the iframe Element?
- What is the meta Element?
- Finally What are the Escape Carecters?

___

* ### What the **versions** of HTML are :
    - XHTML 1.0
    - HTML 4
    - HTML 5


* ### The **DOCTYPE** element is :

    a special element to determine the version of HTML that the browser will use usually the browsers read html pages as HTML 4 by default but as the best practice the defention of html version is necessary.
* ### How we write a **comment** in th HTML is as the following:
    between a tow angle brackets with tow dash inside of it we put a comment with Exclamation mark after the left angle mark


* ### What The **ID** and **Class** attribute is :

    #### **ID attribute** : an attribute can be carried by any HTML element used to uniquely identify that element from other elements on the page.
    </br>

    #### **Class attribute** : an attribute to identify several elements with same design and it can be carried by any elemnet.

    </br>

    - **attribute writing rules** :
        - start with a letter or an underscore (not a
    number or any other character).
        - It is important that no two elements on the same page have the same value for their id attributes

* ### The types of elements depeding on how they appear are :

    - **Block Elements** : always appear to start on a new line in the browser window.

    - **Inline Elements** : always appear to continue on the same line as their neighbouring elements.

* ### What **div** and **span** Grouping Text & Elements In a Block are : 

      - **div element** : The div element allows you to group a set of elements together in one block-level box.
 


      - **span element** : The span element acts like an inline equivalent of the div element. 

      - **span used to either** :
            - Contain a section of text where there is no other suitable element to differentiate it from its surrounding text
            - Contain a number of inline elements.


* ### What **iframe** element is :

    An iframe is like a little window that has been cut into your page — and in that window you can see another page and The term iframe is an abbreviation of inlineframe.

    - **iframe attributes are :** :

        - src : specifies the URL
        - height : the height of the iframe in pixels.
        - width : the width of the iframe in pixels.
        - scrolling : t indicates whether the iframe should have scrollbars or not.
        - frameborder : indicates whether the frame should have a border or not.
        - seamless : can be applied to an iframe where scrollbars are not desired

* ### What The **meta** element is : 
    The <meta> element lives inside the head element and contains information about that web page,It is not visible to users but fulfills a number of purposes such as telling search engines about your page, who created it, and whether or not it is time sensitive.

    - **meta attributes are :** 
        - **name** attribute.
        - **content** attribute.

    The value of the name attribute is the property you are setting, and the value of the content attribute is the value that you want to give to this property.
    <br>
    - The values of the **name** attribute are
        -  description: description is commonly used by search engines to understand what the page is about and should be a maximum of 155 characters.

        - keywords:This contains a list of comma- separated words that a user might search on to find the page.
        - robots: This indicates whether search engines should add this page to their search results or not.
        - author: This defines the author of the web page.
        - pragma : This prevents the browser from caching the page.
        - expires : Because browsers often cache the content of a page, the expires option can be used to indicate when the page should expire (and no longer be cached).
    - The values of the **content** attribute are anything related to the name value for every element.

* ### What The **Escape Cahecters** are : 
    Escape characters are used to include special characters in your pages such as <, >, and ©.

___

## THIRD:* HTML5 Layout* 

- What is the main difference between Traditional HTML
Layouts and HTML5 Layout?
- What are the 8 elements of New Layout?
- What is Linking Around Block-Level Elements?
- How we Help Old Browsers Understand the page?
___



* ### What the main difference between Traditional HTML Layouts and HTML5 Layout is: 

the new HTML5 is more semantic and has a special purpose tags makes debugging and writing code easier. 

* ### The 8 elements of New Layout are :


    1. Headers & Footers: header and footer tag are the main header or footer that appears at the top or bottom of every page on the site.

    2. Navigation : nav tag  used to contain the major navigational blocks on the site such as the primary site navigation.

    3. Articles : article tag acts as a container for any section of a page that could stand alone and potentially be syndicated.

    4. Asides : aside tag has two purposes, depending on whether it is inside an article element or not.

    5. Sections : section tag is a groups related content together, and typically each section would have its own heading.

    6. Heading Groups : The purpose of the hgroup element is to group together a set of one or more h1 through ]h6 elements so that they are treated as one single heading.

    7. Figures : figure and figcaption tags It can be used to contain any content that is referenced from the main flow of an article (not just images).

    8. Div Element :the <div> element will remain an important way to group together related elements

* ###  Linking Around Block-Level Elements is :

    Block-Level Elements HTML5 allows web page authors to place an (a) element around a block level element that contains child elements. This allows you to turn an entire block into a link.

* ### we Help Old Browsers Understand the page :

    Older browsers that do not know the new HTML5 elements will automatically treat them as inline elements. Therefore, to help older browsers, you should include the line of CSS on the left which states which new elements should be rendered asblock-level elements.


___                                 

## FOURTH:* The ABC of Programming*

- What is the script and how do i create one?
- How do computers fit in with the world arround them?
- How do i write a script for a web page?
___
* ### What is a scriptand how do i create one?

A script is a series of instructions that the computer can follow in order to  achieve a goal
To write a script:
 you need to first state your goal and then list the tasks that need to be completed in order to achieve it. 


* ### How do computers fit in with the world arround them?

   The computers creat models of the world using data,The models use objects to represent physical things,Object have properties that tell us about the object .
   Programmers can write code
   Web browser use HTML markup to create amodel of the web page
   To make webpage interactive,you write code that uses the browser model of the web page .


* ### How do i write a script for a web page?
   The HTML <script> elementis used in HTML pages to tell the browser to load the JavaScript file 
   you can link it in When you want to use JavaScript with a web page you use the HTML


   
> THIS READING QOUT FROM "Duckett HTML book &  Duckett JS book".


             FARAH ASHA 



