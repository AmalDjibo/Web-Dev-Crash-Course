# HTML in 5 Minutes

## 1. index.html
Instruction Mannual of the website

## 2. Basic Syntax

```
<!DOCTYPE html>
<html lang="en">
<head>

</head>
<body>
  
</body>
</html>
```

### ```<head>``` tags
- Contains metainfo (info processed by the browser)
    - Scripts you want to load
    - Stylesheet
    - Much more!

### <body tags>
-  What the end user see on the page
  -  Headers
  -  Navagations 
  -  Paragraphes

### Common HTML Elements 

#### ```<h1>-<h6>```
Used for titles

#### ```<p>```
Paragraps... pretty self-explantory

#### ```<img>```
For images

#### ```<a>```
Used for links

#### ```<ol & <ul>```

```<ol>``` is used for a numbered list and ```<ul>``` are used for bulleted lists. Use ```<li>``` inside these for each item

#### ```<button>```
Buttons. duh...

#### ```<forms>```
Too much to explain go [here](https://github.com/AmalDjibo/Web-Dev-Crash-Course/tree/HTML/Part%203%20(Forms))

### Containter Elements
Elements you go put content inside of and style that container

#### ```<div>```
Sections

#### ```<span>```
Inline text

#### ```<style>```
Lets you write CSS inside HTML.

#### ```<script>```
Lets you write or insert JS inside HTML.

### Attributes 
Used to modify HTML elements, the go inside the opening tag

#### Global Attributes
Attributes that work on any HTML tag

##### Classes 
Lets you style and select elements in JS. You can apply multiple classes with just a space & reuse them across multiple elements.

```
<h1 class="hello"></h1>
```

##### IDs 
Lets you style and select elements in JS. You can apply multiple classes with just a space & you cannot reuse them across multiple elements.

```
<h1 id="hello"></h1>
```
