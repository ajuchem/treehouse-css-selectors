Attribute selectos can target an element by any of its HTML attributes

We can define specific child and sibling selectors with combinators

Combinators:

- The > combinator targets a direct child of an element
- The + combinator targets an element's immediate sibling
- The ~ combinator targets all the specified siblings that follow an element

Substring matching attribute selectors:

- ^ tells the browser to match a piece of code that's at the beginning of an attribute's value
- $ matches a piece at the end of an attribute's value
- * matches any part of an attribute's value

When can we use these selectors?

- When a CMS or framework allows no access to HTML
- When we are unable to add classes or IDs to elements
- With dynamic list or images galleries

:nth-child

     :nth-child(an+b)
     :nth-child(2n+3) ===> will select the 3rd value and then every 2nd after that

- :nth-child targets combination of child elements
- :nth-of-type selects a specific type of element
- :root target the top-most element in the document (more specific than html)
- :not selects everything except the type of element we specify

Pseudo-Elements - target virtual elements that don't exist in the source code

- ::first-line
- ::first-letter
- ::before
- ::after

     ::before and ::after inserts generated contence from the CSS
