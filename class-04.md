# Regular Expression
A Regular Expression is a sequence of characters that constructs a search pattern. When you search for data in a text, you can use this search pattern to describe what you are looking for.

A regular expression can be a single character or a more complicated pattern. It can be used for any type of text search and text replace operations. A Regex pattern consist of simple characters, such as /abc/, or a combination of simple and special characters, such as /ab*c/ or  /example(d+).d*/.


### JavaScript Regex
In JavaScript, a regular expression is an object that describes a pattern of characters. The JavaScript RegExp class represents regular expressions, and both String and RegExp define methods. It uses regular expressions to perform pattern-matching and search-and-replace functions on text.
example:
`var pattern = new RegExp(pattern, attributes);`
`var pattern = /pattern/attributes;`

-Pattern  A string that specifies the pattern of the regular expression or another regular expression.
-Attributes  An optional string containing attributes that specify global, case-insensitive, and multi-line matches.

Modifiers
Modifiers are used to perform case-insensitive and global searches.

example:
`let str = "This is the example";`
`let pattern = /is/g;`

![Image of Yaktocat](https://miro.medium.com/max/1954/1*N-JAC1TBpItJb1XLVBKZNw.png)

# Css Grid Layout 
-Grid layout replace Float layout  using less and more readable and logical css and Html also css grid works
great with the flex box which is the best to hundel one -deimnistional compenent and layout
-CSS Grid Layout is the most powerful layout system available in CSS. It is a 2-dimensional system, meaning it can handle both columns and rows, unlike flexbox which is largely a 1-dimensional system

every grid system has 
1- `a container that hold all the items`S
2- `grid items `
3-`row axies and col axis`

some of grid system property like 
`grid-template-row`
`grid-template-columns`
`&--number`
`grid-row-gap or grid-col-gap` 
`grid-template-areas`
`grid-auto-rows`
`grid-auto-columns`
`grid-auto-flow`