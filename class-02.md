# jQuery, Events, and The DOM
>jQuery offers a simple way to achieve a variety of common JavaScript tasks quickly and consistently, across all major browsers
# what is Jquery?
Jquery is a file that you can include in your web page it lets find an element using css selector
ex:
$('li.item');

# What You Can Do with jQuery
There are lot more things you can do with jQuery.
-You can easily select elements to perform manipulation.
-You can easily create complex CSS animation with fewer lines of code.
-You can easily manipulate DOM elements and their attributes.
-You can easily perform multiple actions on an element with a single line of code.
-You can easily get or set dimensions of the HTML elements.

# Advantages of Using jQuery
Save lots of time — You can save lots of time and efforts by using the jQuery inbuilt effects and selectors and concentrate on other development work.
Simplify common JavaScript tasks — jQuery considerably simplifies the common JavaScript tasks. Now you can easily create feature rich and interactive web pages with fewer lines of codes, a typical example is implementing Ajax to update the content of a page without refreshing it.
Easy to use — jQuery is very easy to use. Anybody with the basic working knowledge of HTML, CSS and JavaScript can start development with jQuery.
Compatible with browsers — jQuery is created with modern browsers in mind and it is compatible with all major modern browsers such as Chrome, Firefox, Safari, Internet Explorer, etc.
Absolutely Free — And the best part is, it is completely free to download and use.
 ###  jQuery Events
In most web applications, the user does some action to perform an operation.
examples on events:
`blur`
`change`
`focus`
`focusig`
`submit`
`keydown`
`keypress`
ex:
`$('#saveBtn').click(function () {`
    `alert('Save button clicked');`
`});`

`<input type="button" value="Save" id="saveBtn" />`