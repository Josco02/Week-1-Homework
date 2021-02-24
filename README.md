# 01 HTML, CSS, and Git: Code Refactor - Joshua Mathew

## Acceptance Criteria and Changes Made to Meet Them

```
GIVEN a webpage meets accessibility standards
    - Standards are met when all criteria are met

WHEN I view the source code
THEN I find semantic HTML elements
    - Divs were changed to "sections" and "articles" and the articles on the right were classified as "aside."
    - Header and footer already had a class so it was unnecessary to change the div tag
    - header list is classed as nav as all 3 links are internal

WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
    - No change in position. Three main point on the left and three benefits on the right


WHEN I view the image elements
THEN I find accessible alt attributes
    - alt attributes describing images have been used 

WHEN I view the heading attributes
THEN they fall in sequential order
    - content is inside span, which is a subset of heading 1

WHEN I view the title element
THEN I find a concise, descriptive title
    - Title is now the name of the organisation

There was too much code for the same few actions so some coding from the stylesheet have been changed to incorporte all parts of the website using the same actions
    - All but one articles of benefits and their images have been deleted and the last one has had it's name changed to "benefits-article." all code referencing is area of the website has also been redirected to "benefits-article"
    - Same for the section articles and their images. The coding is now referenced to "section-content."
