# Elements, Attributes, Images, & Links
### Block Level vs. Inline Elements
#### Block Level
Occupies the entire line of the space where it is displayed. Each new block level element starts on a new line.
```bash
<header></header>
<nav></nav>
<p></p>
<div></div>
```
#### Inline
Placed next to each other on the same line.
```bash
<span></span>
<strong</strong>
<audio></audio>
```
### Adding Links in HTML
Anchor element (inline): any links you put on your web page are going to be in between these tags
```bash
<a href=""></a>
```

### Attributes
Adds information to an element
```bash
<a 'href=""' 'target=""'></a>
```
href (which stands for Hyper reference) is an example of an attribute for the anchor element,this tells the anchor tag where we want it to redirect to when we click on the link.

The target attribute within the anchor tag specifies where you want a link to display whether that be in a new tab or in an iframe.

### Making Items in you navagation clickable
To do this, you need to wrap the the anchor tag that contains the link you wish to redirect to, with the list item.
```bash
  <li><a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Block-level_elements" target="_blank">Contact</a></li>
```
### Creating Other Pages On Your Website
Simply create a new folder for the name of the subpage. For example, a folder named "contact" and within that folder create an new "index.html" file.

**Remember to save your progress before previewing you changes!!**

#### File Paths

##### Referencing a file that is in a folder within the same directory of the file your linking from:

Lets say you wanted to link to your contact page from your home page, and the contact page was in "contact" named "contact.html" in the same directory as the the homepage.
The proccess would be as follows:
```bash
<li><a href="contact/index.html" target="_blank">Contact</a></li>
```

###### Relative Paths
An example of a relative path is demonstarated above, this is when you link to page in your website by navagating through your folder structure.

###### Absolute Paths
This is when you link to a page in your website by using the actual url. For example:
```bash
<li><a href="www.yourwebsitename.com/contact/index.html" target="_blank">Contact</a></li>
```

##### Referencing a file that is in a folder in a different directory than the file your linking from:

Lets say you wanted to link to your home page from your contact page, and the homepage page was just outside the directory of the conatct page named "index.html"
The proccess would be as follows:
```bash
<li><a href="../index.html" target="_blank">Home</a></li>
```
This means we are going out level outside of our curent directory.

### Adding Images to your website
First, you should create a new folder with an easy to remember name to store all of your images.

#### <img> tags
This were we link to images in our website site 
```bash
<img src="images/HTX.jpg" alt="Images of some buliding in Houston">
```

img element attributes:

src: This refers to the location of the image within your website's directory
alt: This is a special description of the image if the user of the website has a vision impariment and has to use a screen or if the simply could be loaded.

### Making your code more organized
Lets try to organized the code below a little bit better:

```bash
 <main>
        <p>My HTX Trip</p>
        <img src="images/HTX.jpg" alt="Images of some buliding in Houston">
        <p>The Texas Landscape</p>
        <img src="images/Texas_landscape_3.jpg" alt="Image of a farm in Texas">
    </main>
```

```bash
<main>
        <ul>
            <li>
                <p>My HTX Trip</p>
                <div><img src="images/HTX.jpg" alt="Images of some buliding in Houston"></div>
            </li>
            <li>
                <p>The Texas Landscape</p>
                <div> <img src="images/Texas_landscape_3.jpg" alt="Image of a farm in Texas"></div>
            </li>
        </ul>



        <p>Do people like my page?</p>
    </main>
 ```
What is better about the second verison?
This makes the code 10x easier to comprehend and to make edits later.

### Adding Favicons
Favicons are added within the head element
```bash
<head>
    <link rel="shortcut icon" href="images/favicon.png">
</head>
```

### Commenting Out Code in HTML
This can be useful if you have code that you need, but don't want to be rendered by the browser at the moment
This can be achived by doing the following:
```bash
<body>
    '<!--'<p>I SHOULD NOT BE DISPLAYED</p>'-->'
</body>
```