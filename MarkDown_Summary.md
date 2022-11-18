# MarkDown Summary & Notes

# Headings:

# Heading Level 1, Uses 1 \#

## Heading Level 2, Uses 2 \#

### Heading Level 3, Uses 3 \#

#### Heading Level 4, Uses 4 \#

##### Heading Level 5, Uses 5 \#

###### Heading Level 6, Uses 6 \#

# Paragraphs

This is a paragraph, it requires no extra syntax or anything. Just regular text typing just like you would in Notepad or something else.

Just like this, isn’t Markdown easy!

Although it is best to avoid using tabs and spaces before paragraphs, which can lead to formatting problems or a difficult to read Markdown.

# Text Styles

Here is some **bold text**.  
Here is some *italic text*.
Here is some ***bold and italic text***.

# Blockquotes

> Here is a blockquote, it is very special.

> Here is a 
> 
> Long long
> 
> Multiple paragraph
> 
> Blockquote

## Nested Blockquotes

> Here
> 
> Is
> 
>> a nested
>> 
> blockquote

## Blockquotes with headings, styles, and lists!

> #### Here is a blockquote
> - With bullet points
> - And another
> Also with some *fancy* text and **bold text**

# Code and Codeblocks

You can use backticks (\`) to denote code.
Here is a piece of code: `print(“Hello World”)` it prints “Hello World” 

This sentence has the following \`word\` which uses backticks but is not code.

## Here is a Codeblock:

    <html>
        <head>
            <title>Some HTML Code</title>
        </head>

# Horizontal Rules
These simply make nice horizontal lines:

***

--------------------

______

You can use \*, \-, or \_ as long as you have blank lines before and after as well as at least 3 characters. 

# Links

## Format:

To create a link, enclose the link text in brackets \[\] and then follow it immediately with the URL in parentheses \(\): 

\*\*\* If your URLs have spaces make sure to substitute them with a ‘%20’! \*\*\*

\[Link Name\]\(link\)

### Example: 

A good markdown guide can be found at [Markdown Guide](https://markdownguide.org) website.

## Titles:

Titles show the 'title' of the link when people hover their mouse pointer over it before clicking.

We can also add a ‘title’ to a link by adding a description enclosed in quotation marks after the url in parenthesis: 
\[Link Name](link “Link Title”)


### Example: 

A good markdown guide can be found at [Markdown Guide](https://markdownguide.org “A good website for markdown reference website”).

## Extras:

You can make bold, italic, and code links using the same methods as we used on text as shown below:

Here is a bold link to **[Github](https://github.com)**.

Here is an italic link to *[Google](https://google.com]*.

Here is a code link to some [`html tag references`](https://w3schools.com/tags/).

# Images

To add an image, add an exclamation mark (!), followed by alt text in brackets [], and add the path/URL to the image asset in parentheses. You can also add a title in quotation marks after the path/URL if wanted.

\!\[Image Name](image path/URL “Image Title”)

Did you know in Github you can also just drap images direclty in your .Md file from the internet?

## Example

![Catto Testing your code](https://user-images.githubusercontent.com/62217158/202799801-c28eacf3-3f8c-4360-ae25-1631bf768d14.jpg "David the Kitty Testing Your Code")

## Linking Images
You can also make an image a link to a web address by enclosing the Markdown for the image in brackets [], and then add the link in parentheses:

\[!\[Image Name](image path/URL “Image Title”)](link)

### Example

[![Catto Testing your code](https://user-images.githubusercontent.com/62217158/202799801-c28eacf3-3f8c-4360-ae25-1631bf768d14.jpg "David the Kitty Testing Your Code")](https://imgflip.com/i/5qikpc)


# Lists

## Ordered

1. First item
2. Second item
3. Third Item
5. Fourth Item
6. Fifth Item
8. Seventh Item
8. Eighth Item
	1. First Indented Item
	2. Second Indented Item
8. Ninth Item
8. Tenth Item

## Unordered

- First Item
- Second Item
- Third Item
	- First Indented Item
	- Second Indented Item
- Fourth Item
- 5\. Item, We can escape creating an unordered list with the ‘\’ backslash
- 6th Item

## Nested Lists and Combinations

1. First Item
2. Second Item
    - Unordered nested item
    - Another Unordered nested item
4. Third Item
	1. Indented Item for nested urdered list
	    1. First Deeply Nested Item
	    2. Second Deeply Nested Item
	2. Another Indented Item for nested ordered list
5. Fourth Item

- First Unordered Item
- Second Unordered Item
    - First Nested Item
    - Second Nested Item
        - Deeper Nested Item
        - Second Deeper Nested Item
- Third Unordered Item
	1. First Ordered Indented Item for nested ordered list
	2. Second Ordered Indented Item for nested ordered list
- Fourth Unordered Item

# Combining Everything!

## Paragraphs and Blockquotes

- Here
- Is

	Here is a paragraph, make sure to use newlines and indents!

- An
- Unordered
- List

	> Here is a blockquote, make sure to use the newlines, indents, and special character

- As
- An
- Example

## Lists and Codeblocks

1. First element
2. Second element

         	<html>
            		 <head>
                 		<title>Some HTML Code</title>
             	</head>

3. Third element

## Lists and Images


1. First element
2. Second element
	![Linux-Symbol](https://user-images.githubusercontent.com/62217158/202803819-4c320b26-7021-4117-a0e9-f8fedd16a6c7.png)
3. Third element
4. Fourth element







