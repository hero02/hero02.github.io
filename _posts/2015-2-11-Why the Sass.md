---
layout: post
titel: Why the SASS?
---

![alt text](http://media02.hongkiat.com/getting-started-saas/sass-getting-started.jpg "sass logo")


###No, not the attitude the CSS preprocessor.

As you dive in more into the world of web design you will start to realize that css stylesheets are getting more complex. It's kinda hard to keep track of every header and color you gave it through out the whole website. Well this is where SASS comes in. SASS allows you to create certain variables so that when you make a change for example h1 color:red it will change it through out the whole website.

<b>Example 1</b>

$primary-color:  #333

body

  font: open sans;
  color: $primary-color;
  
  As you can see here this allows you to change the variable color with out going through the whole stylesheet and make individual changes. Anything with the variable $primary-color will automatically change to what ever was set in the variable.
