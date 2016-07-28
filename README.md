**Banner adspace rotator**
- banner ads rotator that uses dropbox


----------


**Requirements (one time setup):**

1. download and create Dropbox account - http://dropbox.com
2.  install it in the Computer
3. add ***banner-ads.js*** to the Dropbox folder (https://dl.dropbox.com/s/d8iiat0hwurqs5d/banner-ads.js)
4. add empty file and named it ***changes.txt***


----------


**Steps for adding banners images (User):**

1. Upload the photos to dropbox
2. Copy the dropbox link
3. Paste the link to the ***changes.txt*** file inside the Dropbox folder


----------


**Example:**

1. banner rotator file (public Dropbox JS file):
https://dl.dropbox.com/s/d8iiat0hwurqs5d/banner-ads.js
2. changes.txt - https://dl.dropbox.com/s/sckr503hpz0c39f/changes.txt
IMAGE URL LINKS (contents):
 https://www.dropbox.com/s/8bjr0gdc7us3ivk/header-1.png?dl=0
https://www.dropbox.com/s/z51j2k421kh8s1q/header-2.png?dl=0
https://www.dropbox.com/s/h6cqg8wl1f3hzgf/header-3.png?dl=0
https://www.dropbox.com/s/3puu4wqafu0vegh/header-4.png?dl=0
https://www.dropbox.com/s/9a0jy6k6kkvrrse/header-5.png?dl=0
https://www.dropbox.com/s/wnjvh34fbuzoano/header-6.png?dl=0

Note:  must modified ***banner-ads.js*** with below code: (containing the ***changes.txt*** file)

    // some codes here
    var CHANGES = 'https://dl.dropbox.com/s/sckr503hpz0c39f/changes.txt';
    // some codes here


