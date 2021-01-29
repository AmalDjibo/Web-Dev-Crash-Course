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