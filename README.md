## Project Name:  Photo Gallery Application

### Course Title:
Web Application Development

### Assignment Date:  
February 23, 2018

### Student Name:  
Zaida Carrion-Rodriguez

### Project Description:
In this assignment we have to complete an application of a photo gallery that allow users to navigate through images and also to add additional images by creating elements in the html. In this assignment the methods  used were: getElementbById() and getElementsbyTagName, also completed some functions for the left and right arrow events. In order to add the elements the createElement() function was used, and for the childs(images) that needed to be added, the parentNode.appendChild() was used.  And to finally copy (clone) the other images the cloneNode() method was used.

### View Project:
https://zcarrion.github.io/lesson6_javascript3/

### Lessons Learned in the Assignment:
1. Browser Object Model contains several objects: Window objects, Navigator objects (which is not supported by all browsers) Arrays, Document Objects (DOM), History objects, Location objects and Screen objects.  The Window object contain the properties of information of a web browser and can be manipulated with several methods.  The History object maintains a history list of documents opened during a web browser session, but don’t display URL’s.  The Location object allows changes to a new web page from within the JavaScript code, and allow modification of URL individual portions. The Navigator Object obtain information from the browser. The Screen object obtain information about the screen (display).
2. This lesson was mainly about the DOM (Document Object Model) which is the way in which the contents or components of a web page, using JavaScript, can be access and manipulated. The DOM is a represented as a hierarchy (DOM tree) based on the document’s contents.  Each element (object) of the DOM tree is a named a node. The DOM defines the methods (actions) and the properties (values).  Using this we can find HTML elements, change HTML elements, add and delete elements, and add event handlers.
3. Finding HTML elements is one of the most common actions.  getElementById() method is the most common way to access an HTML element using the id.  innerHTML property is the easiest way to get the content of an element, and is useful for getting and replacing content of HTML elements.  Other method to find HTML elements is document.getElementsByTagName, that will find the element by it’s tag name.  The document.getElementsbByClassName will find the element using the class name. In order to change the HTML elements this properties can be used:  element.innerHTML = new html content (will provide inner HTML new content; element.attribute = new value and element.setAttribute(attribute, value) (which change the attribute of an element; element.style.property = new style (will change the selected style of the element.
