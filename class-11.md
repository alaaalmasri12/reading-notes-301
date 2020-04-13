# EJS
EJS is a simple templating language that lets you generate HTML markup with plain JavaScript. ... It's just plain JavaScript
Template engines are very useful for getting code out the door quickly.
There are many convenience features in template engines - including security features - such as built-in HTML encoding. For example, in EJS, you can automatically encode data for HTML context using the <%= %> tags!
However, template engines fail to consider all contexts on a webpage. Let’s say a developer chooses to print data into script blocks or JavaScript functions. Despite use of EJS encoding syntax (like <%= %> tags)

Features
Fast compilation and rendering
Simple template tags: <% %>
Custom delimiters (e.g., use <? ?> instead of <% %>)
Includes
Both server JS and browser support
Static caching of intermediate JavaScript
Static caching of templates
Complies with the Express view system

A)how to install ejs?
ex:
` npm install ejs`

B)how to use ejs?
Pass EJS a template string and some data. and you've got some HTML.
ex:
    `let ejs = require('ejs'),`
 `   people = ['geddy', 'neil', 'alex'],`
    `html = ejs.render('<%= people.join(", "); %>', {people: people});`
ejs also help with browser support
ex:
    `<script src="ejs.js"></script>`
      `<script>`
      ` let people = ['geddy', 'neil', 'alex'],`
     `  html = ejs.render('<%= people.join(", "); %>', {people: people});`
          `</script>`
