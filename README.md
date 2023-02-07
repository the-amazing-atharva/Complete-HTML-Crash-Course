# HTML Crash Course
Contains all necessary HTML tags from a Crash Course in the form of a web page. <br>
Visit site [here](https://the-amazing-atharva.github.io/Complete-HTML-Crash-Course/)

# Boilerplate Code 
&lt;!DOCTYPE html&gt; <br>
&lt;html lang="en"&gt; <br>
&lt;head&gt; <br>
    &lt;meta charset="UTF-8"&gt; <br>
    &lt;title&gt;Document&lt;/title&gt; <br> 
&lt;/head&gt; <br>
&lt;body&gt; <br>
    &lt;!-- Body --&gt; <br>
&lt;/body&gt; <br>
&lt;/html&gt; <br>


# HTML Cheatsheet 

## Basic Tags

### &lt;html&gt; &lt;/html&gt;<br>
>Creates an HTML document
### &lt;head&gt; &lt;/head&gt;
>Sets off the title & other info that isn't displayed
### &lt;body&gt; &lt;/body&gt;
>Sets off the visible portion of the document
### &lt;title&gt; &lt;/title&gt;
>Puts name of the document in the title bar; when bookmarking pages, this is what is bookmarked

<br>

## Text Tags

### &lt;pre&gt; &lt;/pre&gt;
>Creates preformatted text
### &lt;h1&gt; &lt;/h1&gt; --> &lt;h6&gt; &lt;/h6&gt;
>Creates headlines -- H1=largest, H6=smallest
### &lt;b&gt; &lt;/b&gt;
>Creates bold text (should use &lt;strong&gt; instead)
### &lt;i&gt; &lt;/i&gt;
>Creates italicized text (should use &lt;em&gt; instead)
### &lt;tt&gt; &lt;/tt&gt;
>Creates typewriter-style text
### &lt;code&gt; &lt;/code&gt;
>Used to define source code, usually monospace
### &lt;cite&gt; &lt;/cite&gt;
>Creates a citation, usually processed in italics
### &lt;address&gt; &lt;/address&gt;
>Creates address section, usually processed in italics
### &lt;em&gt; &lt;/em&gt;
>Emphasizes a word (usually processed in italics)
### &lt;strong&gt; &lt;/strong&gt;
>Emphasizes a word (usually processed in bold)
### &lt;font size=?&gt; &lt;/font&gt;
>Sets size of font - 1 to 7 (should use CSS instead)
### &lt;font color=?&gt; &lt;/font&gt;
>Sets font color (should use CSS instead)
### &lt;font face=?&gt; &lt;/font&gt;
>Defines the font used (should use CSS instead)

<br>

## Links

### &lt;a href="URL"&gt;clickable text&lt;/a&gt;
>Creates a hyperlink to a Uniform Resource Locator
### &lt;a href="mailto:EMAIL_ADDRESS"&gt;clickable text&lt;/a&gt; 
>Creates a hyperlink to an email address
### &lt;a name="NAME"&gt;
>Creates a target location within a document
### &lt;a href="#NAME"&gt;clickable text&lt;/a&gt;
>Creates a link to that target location

<br>

## Formatting

### &lt;p&gt; &lt;/p&gt;
>Creates a new paragraph
### &lt;br&gt;
>Inserts a line break (carriage return)
### &lt;blockquote&gt; &lt;/blockquote&gt;
>Puts content in a quote - indents text from both sides
### &lt;div&gt; &lt;/div&gt;
>Used to format block content with CSS
### &lt;span&gt; &lt;/span&gt;
>Used to format inline content with CSS

<br>

## Lists

### &lt;ul&gt; &lt;/ul&gt;
>Creates an unordered list
### &lt;ol start=?&gt; &lt;/ol&gt;
>Creates an ordered list (start=xx, where xx is a counting number)
### &lt;li&gt; &lt;/li&gt;
>Encompasses each list item
### &lt;dl&gt; &lt;/dl&gt;
>Creates a definition list
### &lt;dt&gt;
>Precedes each definition term
### &lt;dd&gt;
>Precedes each definition

<br>

## Graphical elements

### &lt;hr&gt;
>Inserts a horizontal rule
### &lt;hr size=?&gt;
>Sets size (height) of horizontal rule
### &lt;hr width=?&gt;
>Sets width of rule (as a % or absolute pixel length)
### &lt;hr noshade&gt;
>Creates a horizontal rule without a shadow
### &lt;img src="URL" /&gt;
>Adds image; it is a separate file located at the URL
### &lt;img src="URL" align=?&gt;
>Aligns image left/right/center/bottom/top/middle (use CSS)
### &lt;img src="URL" border=?&gt;
>Sets size of border surrounding image (use CSS)
### &lt;img src="URL" height=?&gt;
>Sets height of image, in pixels
### &lt;img src="URL" width=?&gt;
>Sets width of image, in pixels
### &lt;img src="URL" alt=?&gt;
>Sets the alternate text for browsers that can't process images 

<br>

## Forms

### &lt;form&gt; &lt;/form&gt;
>Defines a form
### &lt;select multiple name=? size=?&gt; &lt;/select&gt;
>Creates a scrolling menu. Size sets the number of menu items visible before user needs to scroll.
### &lt;select name=?&gt; &lt;/select&gt;
>Creates a pulldown menu
### &lt;option&gt;
>Sets off each menu item
### &lt;textarea name=? cols="x" rows="y"&gt;&lt;/textarea&gt;
>Creates a text box area. Columns set the width; rows set the height.
### &lt;input type="checkbox" name=? value=?&gt;
Creates a checkbox.
### &lt;input type="checkbox" name=? value=? checked&gt;
>Creates a checkbox which is pre-checked.
### &lt;input type="radio" name=? value=?&gt;
>Creates a radio button.
### &lt;input type="radio" name=? value=? checked&gt;
>Creates a radio button which is pre-checked.
### &lt;input type="text" name=? size=?&gt;
>Creates a one-line text area. Size sets length, in characters.
### &lt;input type="submit" value=?&gt;
>Creates a submit button. Value sets the text in the submit button.
### &lt;input type="image" name=? src=? border=? alt=?&gt;
>Creates a submit button using an image.
### &lt;input type="reset"&gt;
>Creates a reset button

<br>

## Table

### &lt;table&gt; &lt;/table&gt;
>Creates a table
### &lt;tr&gt; &lt;/tr&gt;
>Sets off each row in a table
### &lt;td&gt; &lt;/td&gt;
>Sets off each cell in a row
### &lt;th&gt; &lt;/th&gt;
>Sets off the table header (a normal cell with bold, center text)




