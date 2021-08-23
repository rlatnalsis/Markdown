<!--See the Markdown result as remove the leading four spaces-->
<body
style="background-color:darkslategray">

# Markdown

is a lightweight markup language for creating formatted text using a plain-text editor.  
<br/>

<h3 style="color:yellowgreen">extension</h3>

    .md

<br/>
<br/>

# Markdown Syntax

<h3 style="color:yellowgreen">Headers</h3>

    # heading 1 tag
    ## heading 2 tag
    ⁝
    ###### heading 6 tag

<br/>

    heading 1 tag
    ==
    heading 2 tag
    --

<br/>
<h3 style="color:yellowgreen">Emphasis</h3>

    bold by **double asterisks**
    bold by __double underscores__

    italic by *asterisk*
    italic by _underscore_

    _**combine them**_ ***i.e., bold-italic***

    underline by ++double plus signs++
    strikethrough by ~~double tildes~~

<br/>
<h3 style="color:yellowgreen">Block Quotes</h3>

    As someone said:

    > wise saying
    >> ...

<br/>
<h3 style="color:yellowgreen">Unordered Lists</h3>

    * asterisk
    + plus sign
    - hyphen
      * put two spaces before the mark
        + put two spaces before the mark
          - put two spaces before the mark

<br/>
<h3 style="color:yellowgreen">Ordered Lists</h3>

    1. item 1
    2. item 2
      1. put two spaces before the number

<br/>
<h3 style="color:yellowgreen">Images</h3>

    ![alternative text](url of an image)

<br/>
<h3 style="color:yellowgreen">Links</h3>

    [alternative text](url)

<br/>
<h3 style="color:yellowgreen">Backslash Escapes</h3>

    \*literal characters\*

for the following characters:

> \* asterisk, \ backslash, ` backtick, {} curly braces, . dot, ! exclamation mark, # hash, - minus sign (hyphen), () parentheses, + plus sign, [] square brackets, \_ underscore

<br/>
<h3 style="color:yellowgreen">Horizontal Rules</h3>

    ---
    ***
    ___

use three or more asterisks, dashes, or underscores

<br/>
<h3 style="color:yellowgreen">Line Break</h3>

    spacing twice
    and changing lines

    backslash\
    and changing lines

<br/>
<br/>

# Github Flavored Markdown(GFM)

<h3 style="color:yellowgreen">Username @Mentions</h3>

    @mention

<br/>
<h3 style="color:yellowgreen">Issue References</h3>

    Issue or Pull Request(PR)#Issue number
    ⇓
    #Issue numer

qualification:

> retain Issue number by generating an Issue or PR

<br/>
<h3 style="color:yellowgreen">Emoji</h3>

    :emoji code:

href. [Emoji Cheat Sheet](https://www.webfx.com/tools/emoji-cheat-sheet/)

<br/>
<h3 style="color:yellowgreen">Fenced Code Blocks</h3>

    wrap the code with backticks to create `a code block`

<br/>

        Markdown coverts text with four leading spaces into a code block

⇓ with GFM

    ```
    wrap the code with triple backticks to create a code block without the leading spaces
    ```

⇓ add an optional language identifier getting syntax highlighting

        ```javascript
        function test() {
        console.log("look ma’, no spaces");
        ```

<br/>
<h3 style="color:yellowgreen">Task Lists</h3>

    - [x] complete item
    - [ ] incomplete item

<br/>
<h3 style="color:yellowgreen">Tables</h3>

    | first header   | secomd header  |
    | -------------- | -------------- |
    | content cell 1 | contnet cell 2 |

process:

> assembling a list of words (for classify headers)  
> separating each column with a pipe  
> divding them with hyphens (for the first row)

</body>
