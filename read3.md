# read 03
## Summary of **HTML document structure**


# HTML uses tags (characters that sit inside angled Xbrackets) to give the information they surround special meaning.

>See how HTML describes the structure of a web page
>>Learn how tags or elements are added to your document
>>how PeoPLe access the weB
>>how weBsItes a re created
>>1Understanding structureXLearning about markupXTags and elements
>>attributeS t  eLL uS more about eLementS

### Each HTML document starts with a document type declaration or doctype.

 **the HTML version and therefore to correctly display the page.**
 *<!DOCTYPE html>*

#### he very simplest HTML page consists of at least three tags: <html>, <head> and <body>. 
##### The <head> tag typically contains a title, keywords, page description and other metadata, which are displayed in the browser window.

### You use the <link> tag to link styles to the webpage. To do this, you can use the attribute href, 
### <head>
  _<link href="style_file_address.css" rel="stylesheet">_
### </head>

## The <title> tag is yet another element that is located inside <head>. You can use this tag to assign the page title, which is displayed in browser tabs.
## <head>
  _<title>HTML CSS Course</title>_
## </head>

## Another important tag that is also located inside <head> is the <meta> tag. 
 _<meta> tags with various attributes and values are used._

## The character encoding for the HTML page is specified using the charset attribute:cd
## <meta charset="name of character encoding">

## Css stands for Cascading Style Sheets. 
### It is a style sheet language used for describing the presentation of a document written in a markup language such as HTML.

### CSS is designed to enable the separation of presentation and content, including layout, colors, and fonts. This separation can improve content accessibility, provide more flexibility and control in the specification of presentation characteristics.


_Using Styling Each CSS Rule contains a property and a value. This is how we add CSS Rules to our HTML elements:_

 >> <h1 style="background-color:Blue;">Hello, World.</h1>

### the attribute style has a property background-color and its value is Red. This will give the text a background color on the webpage.
 1.  Other Properties
>> style="text-align:center;"
>> style="width:200px;"
>>alt="logo of html and css"
