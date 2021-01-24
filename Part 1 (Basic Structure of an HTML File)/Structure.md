# Basic Structure Of An HTML File
### Boilerplate Code
```bash
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title></title>
</head>
<body>
    
</body>
</html>
```
This is the basic code that **NEEDS** to be in every .html file

#### Breakdown
##### First line - This tells the web browser that this is an HTML5 file
```bash
<!DOCTYPE html>
```

##### <html> tags - Everything goes under these tags
```bash
<!DOCTYPE html>
<html>

</html>
```


##### <head> tags - Contains background info about the web page that is required by the browser
###### <meta> tag - Empty element (no closing tag), used for background info For example, the charset meta tag tells the browser what characters you're going to use. There is also the viewport meta tag which helps you web page scale to different devices
```bash
<!DOCTYPE html>
<html>
<head>
     <meta charset="UTF-8">
     <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
<head>
</html>
```
##### <body> tags - This is contains the stuff that we as users see on a webpage
```bash
<!DOCTYPE html>
<html>
<head>
     <meta charset="UTF-8">
     <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
<head>
<body>
</body>
</html>
```

## Understanding HTML Elements
### Semantic vs. Non-Semantic Elements

