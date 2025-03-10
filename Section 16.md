#Adding JS to websites
1. Learning how to integrate JS in our web page. Through the help of writing code in the body tag itself.
2. Learnt, onload and how we need to write the code within "".
3. Better method is to include a script tag, right before the ending body tag
4. Inside this tag you can freely write your JS program.
5. And finally, there's a method where you can call the source of the JS code, inside this script tag, from another file, where you have the actual code written down.
6. Position of script tag matter, because it needs all the html declared to be able to change them, or else it will be a not defined error.

#DOM Model
8. Moving on to the DOM model
9. firstElementChild, lastElementChild
10. We can store these objects inside variables as well.
11. innerHTML, style.color
12. querySelector("").methods()
13. Objects inside the DOM contain properties and methods
14. Property don't have  () in the end, whereas methods do.
15. getElementsByTagName() //it says elementSSSSS returns array not single
16. getElementsByClassName()
17. getElementById()// says element, no s, returns single element
18. querySelector()//also returns single element//Selector is what we used when we were applying CSS to our site, with the tags, classes and ids, which can also be combined//returns the first item that matches the query
19. querSelectorAll() //just a plural version of querySelector//querySelector is recommended because it is specific and more adaptable

#Manipulating CSS through JS
1. Unlike CSS, the property names in JS are in camel cased without any -, and all the values being assignedd need to be strings ""

#Separation of Concerns
1. HTML for content
2. CSS for style
3. JS for behaviour
4. classList property, gives list of classes of the object
5. classList.add(""), classList.remove(""), classList.toggle("")
6. through this we can creaete custom style for different classes and based on that we can change the style from the JS without compromising the seperation concern

#Text Manipulation
1. textContent(Just gives the text content, simple) v/s innerHTML(Gives you the htm that is inside the current tag, can return HTML tags, can help us modify HTML tags as well)

#Attribute Manipulation
1. .attributes(lists all the attributes of that object)
2. getAttribute("the attribute you want") //returns the attribute value
3. setAttribute("the attribute you want to change", "What you want to change it to") //changes the value of that attribute
4. 
