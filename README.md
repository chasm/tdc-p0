# EDA Phase Zero Curriculum

## Development Thread

1. Fundamentals
    1. [History of the Internet](http://www.internetsociety.org/internet/what-internet/history-internet/brief-history-internet)
    2. [History of the World Wide Web](http://www.w3.org/History.html)
    3. Client-server
        1. [HTTP](https://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol)
            1. Methods
            2. [Status codes](http://httpstatus.es/)
            3. Headers
        2. SSH
        3. SFTP
        4. SMTP/POP/IMAP
    4. Routing, packets, caching
    5. Cookies and state
    6. Sockets and polling
    7. Static web sites
    8. Web applications
    9. Single-page applications
    10. Real-time applications
2. Separation of concerns
    1. Function/semantics
        1. HTML
            1. [Content categories]():
                1. Metadata content: link, meta, noscript, script, style, title
                2. Flow content: blockquote, div, dl, figure, footer, header, p, ol, ul
                3. Sectioning content: article, aside, nav, section
                4. Heading content: h1-6
                5. Phrasing content: abbr, br, em, span, strong, time
                6. Embedded content: audio, canvas, iframe, img, object, video
                7. Interactive content: a, button, input, label, select, textarea
                8. Palpable content: (contains visible content)
            2. The DOCTYPE element
            3. A basic HTML document
            4. Parts of an HTML document (head, body)
            5. Inline vs. block elements
            6. Attributes
        2. XML
            1. Schema
            2. XPath/XQuery
            3. XSL
            4. XHTML
    2. Presentation
        1. CSS
            1. Selectors
            2. Properties
            3. Units
            4. Specificity
            5. Box model
            6. Positioning
            7. Animations
            8. Media queries
            9. Prefixes
            10. The cascade
        2. CSS preprocessors
            1. Sass
            2. LESS
            3. Stylus
        3. Libraries
            1. Foundation
            2. Bootstrap
        4. XSL
            1. XSLT
            2. XSL-FO
    3. Behavior/interactivity
        1. JavaScript in the browser (see programming thread)
        2. [jQuery](https://jquery.com/)
        3. Alternatives to jQuery [Zepto](http://zeptojs.com/)
        4. JS templates
            1. [Handlebars](http://handlebarsjs.com/)
            2. [EJS](http://www.embeddedjs.com/)
            3. [Jade](http://jade-lang.com/)
    4. Accessibility/usability
        1. [NN/g](http://www.nngroup.com/articles/)
        2. [WCAG 2.0](http://www.w3.org/TR/WCAG20/)
        3. [ARIA](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA) and ARIA roles
        4. [Types of disabilities](http://webaim.org/intro/)
        5. [Color and contrast](http://accessibility.umn.edu/color-and-contrast-414.html)
        6. [Keyboard-only](http://webaim.org/techniques/keyboard/)

## Programming Thread

These are the topics that this thread will cover. They will *not* be covered in this order. Instead, each will be introduced at that point in the student's learning where it will make the most sense to the student given the student's current context.

Also, we will focus on teaching the *concepts* rather than memorizing fancy names. So the goal is for the student to understand, for example, the *idea* of referential transparency, but not necessarily know the terminology.

Finally, this is a basis from which to draw topics. As the curriculum is developed, we'll see what fits and what doesn't. Not all of these will be touched upon.

1. What is a programming language?
    1. Compiled vs. interpreted
    2. Errors, compile-time vs. runtime
    3. I/O (stdout, stderr)
    4. The terminal and shells
2. Programming paradigms
    1. Declarative vs. imperative
    2. Funtional programming (FP)
        1. First class and higher order functions
        2. Pure functions and side effects
        3. Referential transparency and the substitution principle
        4. Strict vs. non-strict (lazy) evaluation
        5. Recursion
        6. Pattern matching
        7. List comprehensions
        8. Closures
        9. Anonymous functions
        10. Currying
    3. Object-oriented programming (OOP)
      1. Prototypes vs. classes
      2. SOLID principles
      3. Inheritance vs. composition
      4. Limitations of OOP (cross-cutting concerns & AOP)
      5. HASA vs. ISA
      6. Need for testing
3. Types
    1. Static vs. dynamic
    2. Strong vs. weak
    3. Duck typing and polymorphism
    4. Datatypes
        1. Primitive
        2. Composite and algebraic
        3. Abstract
4. Fundamentals
    1. Values and variables
    2. Scope
    3. Expressions, operators (precedence), assignments
    4. Conditionals
        1. Truthiness
        2. Logical operators
        3. Boolean algebra
        4. Ternary operator
        5. Switch
    5. Loops
        1. for
        2. while
        3. do-while
    6. Arrays
    7. Objects
    8. Reusable code with functions
    9. Function.bind, *this*, and arrow functions
    10. Prototypes and prototypical inheritance
    11. Classes
    12. Control flow and error handling
5. Advanced JS
    1. Iterators and generators
    2. Destructuring assignment
    3. Extended parameter handling
        1. Default values
        2. Rest parameter
        3. Spread parameter
    4. Template strings
    5. Maps and sets
    6. Symbols
    7. Promises
6. Regular expressions
7. Node.js (io.js)
    1. Version control with *n*
    2. NPM, semantic versioning
    3. package.json
    4. Modules, importing, and build systems
        1. Browserify, gulp, grunt
        2. Webpack
    5. ES3 vs. ES5 vs. ES6
8. jQuery
    1. Selectors
    2. Events
    3. Effects
    4. DOM traversals
    5. AJAX
