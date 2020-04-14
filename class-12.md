# partials

Partials that are used to help us to avoid repetition of the same code on several web pages.
EJS Partials help us avoid repetition of the same code on several web pages. For example, you may want the same header for several web pages
We use <%- include( PARTIAL_FILE ) %> where the partial file is relative to the template you use it in.
Partials come in handy when you want to reuse the same HTML across multiple views

Partials automatically inherit the view locals that are available wherever they are used.