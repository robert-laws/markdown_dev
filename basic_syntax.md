# Markdown - Basic Syntax

## Basic Span Elements

### italic and bold

* italic = \_ word_ **OR** \*word*
* bold = \_\_ word__ **OR** \*\*word**

Lorem ipsum dolor sit amet, _consectetur_ adipiscing elit, sed do eiusmod tempor incididunt ut *labore* et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud __exercitation__ ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in **reprehenderit** in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

### code tag

* code = \`text of code goes here\`

Voluptate velit esse cillum dolore eu fugiat nulla pariatur. `Code Excepteur` sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

___

## Paragraph and Headlines

* paragraphs created by adding an empty line between areas of text

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Ut enim ad minima veniam, quis nostrum exercitationem ullam corporis suscipit laboriosam, nisi ut aliquid ex ea commodi consequatur?

Headlines created multiple ways:

* H1 = "underline" with equal symbols (one or more)
* H2 = "underline" with dash symbols (one or more)
* H1 - H6 = add # tag - one for H1, two for H2, etc.

Headline Text
=============

Sub-headline Text
-----------------

# Heading Level 1 - \#
## Heading Level 2 - \#\#
### Heading Level 3 - \#\#\#
#### Heading Level 4 - \#\#\#\#
##### Heading Level 5 - \#\#\#\#\#
###### Heading Level 6 - \#\#\#\#\#\#

___

## Blockquotes

* blockquotes are created by adding a \> before a paragraph
* it's possible to make a blockquote within a blockquote with double \>\>

> Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
>> Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

> Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Ut enim ad minima veniam, quis nostrum exercitationem ullam corporis suscipit laboriosam, nisi ut aliquid ex ea commodi consequatur?

___

## Horizontal Rules

Three ways to create a horizontal rule

* three or more hyphens \-\-\-
* three or more underscores \_\_\_
* three or more asterixes \*\*\*

______________

Horizontal Rules - displayed above

___

## Lists

Two types - unordered and ordered lists

* create an unordered list with a hypen -, plus symbol +, or asterix * at the beginning of the line of text
* indented lines can create a sub-list item


* numbers
  * one
  * two
  * three
  * four

- more numbers
  - five
  - six
  - seven
  - eight

* ordered lists can be created with numbers

1. Number One
2. Two
3. Three
4. Four
5. Five

___

## Creating Links

Links can be created in multiple ways

* Inline links - Use square brackets and a link in parantheses
* Add title by writing text in quotes inside the parantheses
* Automatic links - place the URL in angle brackets
* Automatic links work for email addresses too
* Reference links - add word in brackets and more brackets around a number

[Consectetur adipiscing elit](http://www.google.com "Google Website"), sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Ut enim ad minima veniam, quis nostrum exercitationem ullam corporis suscipit laboriosam, nisi ut aliquid ex ea commodi consequatur?

Link to Google Website: <http://www.google.com>

Link to [yahoo web address][1] made with reference linking

[1]: http://www.yahoo.com "Yahoo"

___

## Images

Two ways to add an images

* Inline - add alt text in brackets and link to image in parantheses - place exclamation point at beginning
* Reference - same as for hyperlinks, but with exclamation point at beginning of image reference
* An image can link to a location by placing the code for the image into the first position of a link syntax

![Robot Character](images/robot.jpg "Robot Head")

![Another Robot][2]

[2]: images/robot2.jpg "Robot Two"

[![Robot Number 3](images/robot3.jpg "Third Robot - link to Google")](http://www.google.com)