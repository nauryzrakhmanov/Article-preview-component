#Interface Mentor - Solution for article preview components

This is the solution to the problem [The article preview component on the interface mentor](https://www.frontendmentor.io/challenges/article-preview-component-dYBN_pYFT ). 

## Table of Contents

- #overview
  - #challenge
- #links
- #my-process
  - #built-in with
  - #what-have-I-learned
  - #continued development
  - #useful resources
- #author
- #confirmations


## Overview

### Challenge

Users have the ability to:
- View the optimal component layout depending on the screen size of their device
- View social media sharing links when they click on the sharing icon

### Links

- Solution URL: https://nauryzrakhmanov.github.io/aaa /
- URL of the live site: https://nauryzrakhmanov.github.io/aaa/

## My process

We did not get away from simply connecting JS files via the script tag and skipped the construction stages during which our language is compiled into a huge file. Also, the link between HTML and CSS, we used the internal style method Because we wanted our code to open on github without any obstacles, and also in our opinion it is more convenient, since we have paired work.

### Built with

- HTML5 semantic markup
- Custom CSS properties as well as internal style
- JavaScript programming language that allows you to create dynamically updated content

### What I learned

In this practical work, we learned some JavaScript properties also used in the process of this work. A JavaScript function is a block of code designed to perform a specific task.
A JavaScript function is executed when it is called (called) "something."
 There are 3 ways to declare a JavaScript variable:
Using var
Using let
Using const
In this practical work, var is used.

In the code below, we create a variable named varname and assign a value to it.
Then we "output" the value inside the HTML paragraph with id = " ":
 Also learned the input text value the value property sets or returns the value attribute value of the text field.
The value property contains the default value OR the value that the user enters (or the value set by the script).
 Also we have a share link that shows a list of links when clicked. We are using toggle to hide and show this list.
When the list is visible, the user can click share to hide (toggle) the visibility of the list of links.


``html
Some HTML code that I'm proud of.
 
 <div class="shareclick" onclick="myFunction()">
          <img class="share-icon" src="https://raw.githubusercontent.com/lynnecodes/FM-articlepreviewcomponent/92b81157a3a4fecbf661a3c4477025b470c6994e/images/icon-share.svg">
          <span class="sharetext" id="mytext">
            <div>
              <p style=" padding: 3px; margin-top: 15px;margin-left: 10px;">SHARE</p>
            </div>
            <div>
              <a href="#"><img src="https://raw.githubusercontent.com/lynnecodes/FM-articlepreviewcomponent/92b81157a3a4fecbf661a3c4477025b470c6994e/images/icon-facebook.svg"></a>
              <a href="#"><img src="https://raw.githubusercontent.com/lynnecodes/FM-articlepreviewcomponent/92b81157a3a4fecbf661a3c4477025b470c6994e/images/icon-twitter.svg"></a>
              <a href="#"><img src="https://raw.githubusercontent.com/lynnecodes/FM-articlepreviewcomponent/92b81157a3a4fecbf661a3c4477025b470c6994e/images/icon-pinterest.svg"></a>
            </div>
          </span>
  </div>
```
``css
 proud-of-this-css
 <style>
.shareclick .sharetext::after {
    content: "";
    position: absolute;
    top: 100%;
    left: 50%;
    margin-left: -5px;
    border-width: 5px;
    border-style: solid;
    border-color:  hsl(217, 19%, 35%) transparent transparent transparent;
}
.shareclick .show {
    visibility: visible;
    -webkit-animation: fadeIn 1s;
    animation: fadeIn 1s;
}
 </style>
```
``js
<script>
    function myFunction() {
      var shareclick = document.getElementById("mytext");
      shareclick.classList.toggle("show");
    }
}
</script>
```


### Continued development

I want to continue focusing on developing ideas for future projects. I want to improve and manage the 
priority of tasks.But in our opinion, the main thing is to approach the project consciously and try to
use professional tools and approaches that you have learned about.That is why constant development and 
pumping yourself allows you to be ready for any situations to solve problems. 
But of course we understand that the focus of attention may vary depending on our desire and direction.

### Useful resources

- https://www.w3schools.com/js/default.asp - For some reason, it helped me a lot. I really liked the 
templates found there and I will use it in the future.
- https://developer.mozilla.org/ru/docs/Learn/JavaScript - This is an amazing site that helped me finally
 understand. I would recommend this to anyone who is still learning this JavaScript concept. 


## Author

- Website - [Nauryz Rakhmanov and Ayakoz Mukiyat] (https://nauryzrakhmanov.github.io/aaa/ )
- Interface Mentor - [ Togzhan Kurmanbek] 
- Instagram - [@ayagoozm](https://www.instagram.com/ayagoozm/ ) 
              [@nauryz_rahmanov](https://www.instagram.com/nauryz_rahmanov/ )


## Thank you
Thanks to our mentor on the project Togzhan Kurmanbek.
