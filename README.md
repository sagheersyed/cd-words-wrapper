# cd-words-wrapper

Plugin Purpose:
The jQuery plugin is designed to animate text within HTML elements with the class dynamic-title. 
It replicates a text animation effect seen in various web designs.

How to Use the Plugin:

Include Dependencies:
Ensure you have jQuery included in your HTML document. 
<script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>

HTML Structure:
Add an HTML element with the class dynamic-title to your webpage. Inside it, include one or more <b> elements to represent the text elements to be animated.

html
 
<html>

 <body>
     <div class="dynamic-title cd-headline clip is-full-width">
      <span>I Am&nbsp;</span>
      <span class="cd-words-wrapper">
          <b class="is-visible">&nbsp;<span class="gold-title">Sagheer Syed.</span></b>
          <b> a&nbsp;<span class="gold-title">Graphic Designer.</span></b>
          <b> a&nbsp;<span class="gold-title">UI Designer.</span></b>
          <b>an&nbsp;<span class="gold-title">Artist.</span></b>
          <b>a&nbsp;<span class="gold-title">Humanitarian.</span></b>
      </span>
   </div>
 </body>
 
</html>

Initialize the Plugin:
Initialize the plugin by calling .textAnimation() on the $('.dynamic-title') jQuery selector.

javascript
 
$(document).ready(function () {
  $('.dynamic-title').textAnimation();
});

Optional Configuration:
You can customize the animation options by passing an options object when initializing the plugin. For example:

javascript
 
$('.dynamic-title').textAnimation({
  animationDelay: 2500,
  // Customize other animation options here
});

if its helps u plz stared my repository which will helps other developers.
