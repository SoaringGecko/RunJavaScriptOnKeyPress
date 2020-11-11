<link rel="shortcut icon" type="image/png" href="/RunJavaScriptOnKeyPress/one-keyboard-js.png">
<link rel="stylesheet" href="/RunJavaScriptOnKeyPress/assets/css/style.css?v=45e0bbafbd04e5eb3875e817bff9edf41552c081">
<link rel="stylesheet" href="https://soaringgecko.github.io/RunJavaScriptOnKeyPress/highlight.css">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<link href="/RunJavaScriptOnKeyPress/highlight.css" rel="stylesheet" type="text/css" />

### I really need to improve this thing, and maybe I will soon(er or later, not sure how soon)

<p>Automatically generates a thing to run JavaScript on a specific key-press</p>

# Why I made this
<p>I was tired of doing it myself</p>

# How do I use it?
<p>If you want to use this just go <a href="https://soaringgecko.github.io/RunJavaScriptOnKeyPress/Pages/">here</a> and follow the instructions</p>
<p>If there is a key you want to use like <b>Caps Lock</b> that doesn't show up when pressed <a href="https://wangchujiang.com/hotkeys/">this</a> may be helpful</p> 

# Updates
<p><b>5.0 —</b> This update adds pages that will generate JS for every letter (lower and upper case) and number key they can be accessed from the bottom of <a href="Pages">this page</a></p>
<p><b>4.0 —</b> You can now use HTML5 in the JS</p>
<p><b>3.3 —</b> Adds a reset  button, will now remove any # above the one selected, can remove linked files</p>
<p><b>3.2 —</b> Adds a Copy button and slight CSS3 changes</p>

# How do I put more then one on a page
<p>If you want to use more then one on a page you will have to style it like this: <pre>&lt;script&gt;
window.onkeypress = function(event) {
   if (event.keyCode == 56) {
// Your JS here
   }
   if (event.keyCode == 115) {
// Your JS here
   }
}
&lt;/script&gt;</pre></p>

# What kind of improvements are you planning on making?
<p>Not sure yet</p>

# Redirects
<p><a href="http://jsonkeypress.rf.gd/">JsOnKeyPress.rf.gd</a> redirects to the page used to generate the script</p>
<p><a href="http://jsonkeypress.rf.gd/a">JsOnKeyPress.rf.gd/[insert any letter here]</a> --- redirects to the Repository</p>

# All the letters
If you want, the code for every letter can be found <a href="https://soaringgecko.github.io/RunJavaScriptOnKeyPress/all-the-letters.html">here</a>
