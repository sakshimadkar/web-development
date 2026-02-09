## HTML 
HTML is the standard markup language for creating Web pages.

 What is HTML?
-HTML stands for Hyper Text Markup Language
-HTML is the standard markup language for creating Web pages
-HTML describes the structure of a Web page
-HTML consists of a series of elements
-HTML elements tell the browser how to display the content
-HTML elements label pieces of content such as "this is a heading", "this is a paragraph", "this is a link", etc.

A Simple HTML Document
Example:

<!DOCTYPE html>
<html>
<head>
<title>Page Title</title>
</head>
<body>

<h1>My First Heading</h1>
<p>My first paragraph.</p>

</body>
</html>

Example Explained:
-The <!DOCTYPE html> declaration defines that this document is an HTML5 document
-The <html> element is the root element of an HTML page
-The <head> element contains meta information about the HTML page
-The <title> element specifies a title for the HTML page (which is shown in the browser's title bar or in the page's tab)
-The <body> element defines the document's body, and is a container for all the visible contents, such as headings, paragraphs, images, hyperlinks, tables, lists, etc.
-The <h1> element defines a large heading.
-The <p> element defines a paragraph.

## What is an HTML Element?
An HTML element is defined by a start tag, some content, and an end tag:
<tagname> Content goes here... </tagname>

## HTML Attributes:
HTML attributes provide additional information about HTML elements.

-All HTML elements can have attributes.
-Attributes provide additional information about elements.
-Attributes are always specified in the start tag.
-Attributes usually come in name/value pairs like: name="value"

HTML Formatting Elements
Formatting elements were designed to display special types of text:

<b> - Bold text
<strong> - Important text
<i> - Italic text
<em> - Emphasized text
<mark> - Marked text
<small> - Smaller text
<del> - Deleted text
<ins> - Inserted text
<sub> - Subscript text
<sup> - Superscript text

## HTML Forms
HTML forms, defined using the <form> tag, are essential for collecting user input on web pages. They include interactive controls like text fields, emails, passwords, checkboxes, radios, and buttons.

Widely used, over 85% of websites rely on forms to gather user data.
They play a crucial role in modern web development by enabling user interaction and data submission.

##  HTML Table
HTML tables allow web developers to arrange data into rows and columns.

## CSS Introduction
CSS (Cascading Style Sheets) is a language designed to simplify the process of making web pages presentable.

It allows you to apply styles to HTML documents by prescribing colors, fonts, spacing, and positioning.
It separates content from styling and allows CSS to be reused across pages.
HTML uses tags, and CSS uses rule sets.
CSS styles are applied to the HTML element using selectors.

## CSS Selector
A CSS selector is a pattern used to target HTML elements and apply specific styles based on their type, class, ID, attributes, or state.

Selectors can target elements by tag, class, or ID.
Combinators allow selecting elements based on hierarchy or sibling relationships.
Attribute selectors target elements with specific attributes or values.
Pseudo-classes style elements in a particular state (e.g., :hover, :first-child).
Pseudo-elements style specific parts of an element (e.g., ::first-letter, ::after).
Advanced selectors like :not() or :nth-child() allow precise and complex selection.
Efficient use of selectors leads to clean, maintainable, and scalable CSS.
