# Challenge-1: Code Refactor

## Description :

### Header :
I began with removing the division with the class of header and implementing a header tag on its own. This simplified all css selector for the header because general design choices could be given to all aspects of this element in one css selector. This also simplified the HTML code because it removed un-necessary div elements with their own unique classes and ids therefore shortening the code.
### Main :
I grouped the central features of the HTML code into a "main" HTML element in order to create a general organization for the prior elements. This allowed for css selectors to be simplified and broadened which then facilitated a reduction in overall lines of code.
### Aside :
In order to seperate HTML elements between the main section of the website and the side bar content I used the semantic element of Aside. This reduced the use of the div element even furthur and again facilitated a reduction in css and html code.
### Footer :
I used the footer element to replace the former div element with the class of footer in order to use a more semantic element and overall reduction in code.

## User Story:

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

## Acceptance Criteria

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the image elements
THEN I find accessible alt attributes
WHEN I view heading attributes
THEN they fall in sequntial order
WHEN I view title element 
THEN I find a concise, descriptive title
```

## Author:
Wes Simcox

## Deployment:

[Live](https://wessimcox.github.io/Code-Refraction-Challenge-1/)

## References:

[StarterCode](https://github.com/coding-boot-camp/urban-octo-telegram)