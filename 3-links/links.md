<h1> Links </h1>

There are two different link types in Markdown, but both of them render the exact same way. The first link style is called an inline link. To create an inline link, you wrap the link text in brackets ( [ ] ), and then you wrap the link in parenthesis ( ( ) ). For example, to create a hyperlink to www.github.com, with a link text that says, Visit GitHub!, you'd write this in Markdown: \[Visit GitHub!](www.github.com).

You can make parts of the inline links bold.

**Inline links point to other locations on the web while reference links point to other locations in the same document.**
Example of how reference links are used:

    [a link to something else][another place].
    Here's [yet another link][another-link]. 
    And now back to [the first link]\[another place].
     
     [another place]: www.github.com
     [another-link]: www.google.com
     
