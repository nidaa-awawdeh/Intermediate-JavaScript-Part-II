 ### Exercises

* What is jQuery? What does it enable you to do? <br>
jQuery is a JavaScript library that helps us perform cross-browser compatible DOM manipulation using a shorter syntax.<br>
* What is the difference between a jQuery object and HTML Element? <br>
A jQuery object has access to all of the functionality of jQuery, including methods like text and each, while an HTML Element has access to none of these methods. You can only manipulate HTML Elements using vanilla JavaScript; if you want to use jQuery, you'll need to convert your element into a jQuery object first. <br>
* What does the $ represent in jQuery? <br>
$ is an alias for the jQuery function. By wrapping elements or node lists in the jQuery function, you are able to manipulate those elements using jQuery methods.

<hr>

`` Write the jQuery selectors/code to do the following``<br>

* Write the necessary to code wait for the DOM to load in jQuery.<br>
* Select the footer element.<br>
* Select the div with an id of "container".<br>
* Select all of the lis inside of the ul with a class of nav.<br>
* Select the third li inside of the div with a class of list-container.<br>
* Select only the last li in each of the uls.<br>

``solution``

 1. Write the necessary to code wait for the DOM to load in jQuery.
    $(function() {
2. Select the footer element.
        $("footer");

 3. Select the div with an id of "container".
        $("#container");

 4. Select all of the lis inside of the ul with a class of nav.
        $(".nav li");

 5. Select the third li inside of the div with a class of list-container.
        $(".list-container li:nth-child(3)");

 6. Select only the last li in each of the uls.
        $("ul li:last-child");
    });

    <hr>