
# Web Developement Interview Questions




## Appendix
https://www.w3schools.com/html/default.asp
https://www.w3schools.com/css/default.asp





## FAQ

#### what is HTML ?

HTML stands for Hyper Text Markup Language. it is a standard language for creating web pages,mark up language is a language which uses tags to define something.

#### what are tags ?

HTML tags are used to mark or define elements within an HTML document. They provide structure and formatting instructions for web browsers to display content correctly.


#### What is the purpose of the <!DOCTYPE> declaration in an HTML document?

The <!DOCTYPE> declaration specifies the document type and version of HTML used in a web page. It helps the browser render the page correctly by defining the rules and syntax for the document.

#### What is the difference between HTML and HTML5?

HTML5 is the latest version of HTML. It introduced new elements (e.g., <video>, <audio>, <canvas>) and APIs, improved support for multimedia, and enhanced semantic markup for better document structure.

#### Explain the difference between inline and block-level elements?

 Inline elements do not start on a new line and only take up as much width as necessary. Examples include <a>, <span>, and <strong>. Block-level elements, on the other hand, start on a new line and take up the full width of their parent container.

#### How do you create a hyperlink in HTML?

You can create a hyperlink using the a (anchor) element. Example: <a href="https://www.example.com">Visit Example</a>.

#### What is the purpose of the <meta> tag in HTML?

The <meta> tag is used to provide metadata about the web page, such as character encoding, viewport settings for responsive design, and page description for search engines.



## CSS

1. what is css ?
  # css stands for cascading style sheet.it is used for decorating or presenting the html pages.

2. what are ways to include the css in our web page?
  # there are 3 ways to include css in web page.  
  ## inline : when we directly apply the css or style to the html element then it is inline way of applying css.   
  ## internal : Embedding CSS within <style> tags in the HTML <head> section.  
  ## External: Linking to an external CSS file using the <link> element.
  
3. What is the difference between display: none; and visibility: hidden;?
  # display: none; completely removes an element from the document flow, making it invisible and not taking up any space.
  # visibility: hidden; makes an element invisible, but it still occupies space in the layout.

4. What is the difference between class and ID selectors in CSS?
# Class selectors are preceded by a period (.) and can be used to apply styles to multiple elements on a page.
# ID selectors are preceded by a hash symbol (#) and are used to select and style a single unique element on a page.

5. What is the default value of the position property in CSS?
# The default value of the position property is static.

6. How can you center an element horizontally using CSS?
# You can center an element horizontally by using margin: 0 auto; if it has a specified width.

7. What is the difference between display: block; and display: inline;?
# display: block; makes an element a block-level element, causing it to take up the full width available and start on a new line.
# display: inline; makes an element an inline-level element, allowing it to flow within the content and not start on a new line

8. what is cascading styles in css ?
  # Cascading order in css determines how conflicting or overlapping rules are applied for html elements.

  eg : 
  <style>  
    p{
      color:red;
    }

      .text{
        color:blue;
      }

    #content{
      color:pink
    }
    
  </style>
  
  <p class="text" id="content"> text in p tag </p>


  here p will be of pink color because id selector has the highest specificity.

  order of specificity is :
  
  1. Inline styles
  2. id selector
  3. class selector
  4. inheritance.
     
9. how can i add background to element?
# we can add background to html element using background css property.
#  for setting color we can use --> background-color: <color>
# for background-image : url(image url)
# background-repeat:no-repeat/ repeat-x/repeat-y
# background-attachment: fixed
# shorthand : 
# background : color image_url repeat attachment.

10. what is box model in css ?
 # box model is fundamental concept in css and html. it tell how the content is and how much padding , margin and width and height of that element.
 there are various elements in the css box model:
        1.Content
          This is the innermost part of the box, where the actual content, such as text, images, or other HTML elements, is displayed. It has a                width and a height.
          
        2.Padding:
        The padding is the space between the content and the element's border

        Border:
        The border is a line or stroke that surrounds the content and padding. It separates the content from the margin.

        Margin:
        The margin is the space between the border of the element and adjacent elements in the layout.


 ![image](https://github.com/rohitsachdeva27/WEB_DEVELOPEMENT_INTERVIEW_QUESTIONS/assets/82018198/5750b856-33a9-4d48-b480-0807087d59d5)

11.  what are the various text css properties?
# 1.direction
# 2 text-decoration-line : underline/overline
# 3 text-decoration-color : color
# 4 text-decoration-style : solid/double/dotted
# 5 text-decoration-thickness: 5px 
# shorthand : text-decoration : line color style thickness
# 6 text-transform: uppercase/lowercase/capitalize
# 7 text-indent : 10px
# 8 letter-spacing: 2px
# 9 line-height:1/0.8

12.  what are various position properties ?
 # The CSS position property is used to control the positioning of an element within its containing element.
 # There are several values for the position property -
  # Static (Default): Elements are positioned in the normal flow of the document. This is the default value, and elements are not affected by the top, right, bottom, or left properties.
  # Relative: Elements are positioned relative to their normal position in the document flow. You can use the top, right, bottom, and left properties to offset the element from its normal     position.
  # Absolute: Elements are positioned relative to their nearest positioned ancestor (an ancestor with a position other than static). If there is no positioned ancestor, the element is positioned relative to the initial containing block (usually the viewport). 
  # Fixed: Elements are positioned relative to the viewport, and they do not move even when the page is scrolled. Fixed-positioned elements are also taken out of the normal document flow.
  # Sticky: Elements are positioned based on the user's scroll position. They behave like relative positioning until they reach a specified offset from the top of the viewport, at which point they become fixed.

13. what is css3 ?
# CSS3, short for "Cascading Style Sheets Level 3," is the latest major revision of the CSS.
# New Features of css 3:
# New Selectors: CSS3 introduces powerful new selectors that enable more precise targeting of HTML elements, including attribute selectors, pseudo-elements, and pseudo-classes.
# Box Model Enhancements: CSS3 introduces properties like border-radius and box-shadow for creating rounded corners and drop shadows on elements, respectively.
# Gradient Backgrounds: CSS3 provides the ability to create gradient backgrounds using the linear-gradient() and radial-gradient() functions, eliminating the need for background images in some cases.
# Text Effects: CSS3 includes text-related properties for controlling text shadow, text overflow behavior, and text wrapping.
# Transitions and Animations: CSS3 introduces the transition and animation properties, allowing developers to create smooth transitions and animations for various CSS properties.
# Media Queries: CSS3 enhances media queries, enabling designers to create responsive designs that adapt to different screen sizes and devices.

14. what are css combinators?
# 


     

