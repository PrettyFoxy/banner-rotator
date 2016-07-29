**Banner adspace rotator**
- banner ads rotator that uses dropbox


----------


**Requirements (one time setup):**

1. download and create Dropbox account - http://dropbox.com
2.  install it in the Computer
3. add ***banner-ads.js*** to the Dropbox folder (https://dl.dropbox.com/s/d8iiat0hwurqs5d/banner-ads.js)
4. add empty file and named it ***changes.js***


----------


**Steps for adding banners images (User):**

1. Upload the photos to dropbox
2. **Right Click** the image file and Click "**Copy the dropbox link**"
3. Paste the link to the ***changes.js*** file inside the Dropbox folder
 
IMAGE URL LINKS (i.e.):

var a = "https://www.dropbox.com/s/8bjr0gdc7us3ivk/header-1.png?dl=0"
var b = "https://www.dropbox.com/s/z51j2k421kh8s1q/header-2.png?dl=0"
var c = "https://www.dropbox.com/s/h6cqg8wl1f3hzgf/header-3.png?dl=0"
var d = "https://www.dropbox.com/s/3puu4wqafu0vegh/header-4.png?dl=0"
var e = "https://www.dropbox.com/s/9a0jy6k6kkvrrse/header-5.png?dl=0"
var f = "https://www.dropbox.com/s/wnjvh34fbuzoano/header-6.png?dl=0"

	banners([
	a,b,c,d,e,f
	])




----------


**Example:**

1. banner rotator file (public Dropbox JS file):
https://dl.dropbox.com/s/d8iiat0hwurqs5d/banner-ads.js
2. changes.js - https://dl.dropbox.com/s/sibvxx1x04ioqrc/changes.js
 

Note:  must modified ***banner-ads.js*** with below code: (containing the ***changes.js*** file)

    // some codes here
    var CHANGES = 'https://dl.dropbox.com/s/sibvxx1x04ioqrc/changes.js';
    // some codes here



Client.html file (https://dl.dropboxusercontent.com/s/jgecmio9x9cxjgb/test.html):

    <html xmlns="http://www.w3.org/1999/xhtml"><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
    	<title>test</title>
    </head>
    <body>
    	<script type="text/javascript" src="https://ajax.googleapis.com/ajax/libs/jquery/1.8.2/jquery.min.js"></script>
    	<script type="text/javascript" src="https://dl.dropbox.com/s/d8iiat0hwurqs5d/banner-ads.js"></script>
    	
    </body></html>
