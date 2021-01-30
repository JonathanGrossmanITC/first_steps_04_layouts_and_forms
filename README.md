# HTML and CSS: Layouts and Forms  

Welcome to the fourth lesson! In this lesson, you learn the basics of layouts and forms. A webpage's layout is how the HTML elements are organized on the screen. Based on which HTML tag types you write in your code and the order of them, your page will have a default layout. In other words, when you load the page in the browser, the HTML elements will organize themselves based on the tag type and order written in your file.

Using various collections of CSS style properties, you can override the default layout. In this lesson, you learn about three different collections of style properties that help you customize your page layout. Specifically, you learn how to position a single HTML element, how to align multiple HTML elements in a row *or* column, and how to align multiple HTML elements in rows *and* columns.

After learning about layouts, you learn about HTML forms. A form is a collection of HTML elements that allow a user to input and submit information. A form has one or more inputs and can also have one or more buttons. A form usually submits the information to a server. In this lesson, you learn about the different parts of HTML forms and how to customize them for your needs. If you entroll in [ITC's fullstack program](htps://www.itc.tech), you can learn how to send the information from a form to a server.

At the end of this lesson, you see a live coding example for creating a page layout and adding a form to your page. The live coding session reinforce what you learn in the lesson. This lesson also helps prepare you for making your personal portfolio site. The code from the session is included in this repository. You can use it however you like, but as with any code you get from someone else, make sure you understand it well enough to explain it to someone before putting it in your own projects.  

In this lesson, you learn:  

- Hour 1: [Position and Flexbox](#position-and-flexbox)    
- Hour 2: [Grid and Forms](#grid-and-forms)   
- Hour 3: [HTML and CSS Live Coding](#html-and-css-live-coding)  

The topics below outline what you learn in the live session. After the live session, you can use this material as a resource for guided self-learning. This document will serve you as a roadmap for gaining repetition with the material that you learn during the live session.   

## [Position and Flexbox](#position-and-flexbox)   

### Position  
 
- HTML elements by default have a collection of positioning properties  
- The positioning properties are `position`, `top`, `right`, `bottom`, `left`, `clip`, and `z-index`  
- Read about them at the bottom of the page about [positioning properties](https://www.w3schools.com/css/css_positioning.asp)  
- An HTML element's default value for `position` is `static`  
- `static` results in an HTML element rending on the screen in the order written in your document  
- By setting the `position` value to something other than `static`, you can change the type of positioning method for that element  
- The `position` values available are `static`, `relative`, `absolute`, `fixed`, `sticky`  
- Each [positioning method has its own behavior](https://www.w3schools.com/cssref/pr_class_position.asp)  
- Understand [how the positioning methods differ](https://css-tricks.com/absolute-relative-fixed-positioining-how-do-they-differ/)  
- Get [detailed definitions and see examples](https://developer.mozilla.org/en-US/docs/Web/CSS/position)  
- One key concept to understand is [how to wrap an element inside a *positioned* ancestor](https://stackoverflow.com/a/4457821)  
- Use [`top`, `right` `bottom`, and `left`](https://css-tricks.com/almanac/properties/t/top-right-bottom-left/) to place an element somewhere other than in its default location    
- Use the [`z-index`](https://css-tricks.com/almanac/properties/z/z-index/) to control the order elements appear on the z-axis (i.e., the axis perpendicular to the plane of your screen)   
- `top`, `right` `bottom`,`left` and `z-index` only impact *positioned* elements  
- For more on `clip`, see [this description on W3Schools](https://www.w3schools.com/cssref/pr_pos_clip.asp)  

### Flexbox

  - Flexbox is a collection of CSS properties makes it easy to align items in a row *or* column   
  - When using Flexbox, you need to turn an HTML element into a [flex container](https://www.w3schools.com/css/css3_flexbox.asp) by setting its `display` property to `flex`  
  - By defining an HTML element as `flex`, you activate a collection of [flex properties](https://www.w3schools.com/css/css3_flexbox_container.asp) that control how it aligns the elements inside it  
  - An element nested *directly* inside a flex container is a flex child    
  - A flex child exhibits the flex behavior defined by the flex container  
  - You can override the default flex child behavior by setting [flex properties for the child](https://www.w3schools.com/css/css3_flexbox_items.asp)  
  - [See how Flexbox works](https://codepen.io/enxaneta/full/adLPwv) on CodePen      
  - Common [use cases for using Flexbox](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Typical_Use_Cases_of_Flexbox)  
  - Example of [centering items inside a flex container](https://codepen.io/danielwarren/pen/WzqBOZ)
  - Elements nested inside a flex child are not influenced by the flex container  
  - To learn about the flex properties and see examples, visit [CSS Trick's Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)  
  - Reinforce the [basics for Flexbox](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Basic_Concepts_of_Flexbox)  
  - Level up your understanding of flex child properties by [learning to control ratios of flex children on the main axis](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Controlling_Ratios_of_Flex_Items_Along_the_Main_Ax)  
  - Learn about [wrapping flex children](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Mastering_Wrapping_of_Flex_Items)  
  
## [Grid and Forms](#grid-and-forms)   
After Flexbox, you learn about CSS Grid Layout. This collection of CSS properties makes it easy to align items in rows *and* columns. This is a great solution when you need to organize information in two dimensions. You can use it in combination with Flexbox and `position` to create intuitive and user-friendly layouts.  
  
## [HTML and CSS Live Coding](#html-and-css-live-coding)  

The live coding session continues working on the live code from the previous lessons. Here are the tasks:

 1. 
 2. 
 3.   
