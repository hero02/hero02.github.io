---
layout: post
titel: Why the SASS?
---

![alt text](http://media02.hongkiat.com/getting-started-saas/sass-getting-started.jpg "sass logo")


###No, not the attitude the CSS preprocessor.



As you dive in more into the world of web design you will start to realize that css stylesheets are getting more complex. It's kinda hard to keep track of every header and color you gave it through out the whole website. Well this is where SASS comes in. SASS allows you to create certain variables so that when you make a change for example h1 color:red it will change it through out the whole website.


####Variables

As you can see in the below example this allows you to change the variable color with out going through the whole stylesheet and make individual changes. Anything with the variable $primary-color will automatically change to what ever was set in the variable. Think of variables as a way to store information that you want to reuse throughout your stylesheet. You can store things like colors, font stacks, or any CSS value you think you'll want to reuse. Sass uses the $ symbol to make something a variable.

<b>Example 1</b>

***

$primary-color:  #333

body

  font: open sans;
  color: $primary-color;
  
***
  
  
  
####Nesting

Sass will let you nest your CSS selectors in a way that follows the same visual hierarchy of your HTML. This saves you a lot of time when it comes to writing css.

![alt text](https://drive.google.com/file/d/0B2PyqmJHfDHva3R1OFg3eDFfRFE/view?usp=sharing "nesting")
  
  
