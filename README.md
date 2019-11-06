<link rel="stylesheet" href="/RunJavaScriptOnKeyPress/assets/css/style.css?v=45e0bbafbd04e5eb3875e817bff9edf41552c081">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<p>Automatically generates a thing to run JavaScript on a specific key-press</p>

# Why I made this
<p>I was tired of doing it myself</p>

# What kind of improvements are you planning on making?
<p>HTML5 element support</p>

# How do I use it?
<p>If you want to use this just go <a href="https://soaringgecko.github.io/RunJavaScriptOnKeyPress/Pages/">here</a> and follow the instructions</p>

# How do I put more then one on a page
<p>If you want to use more then one on a page you will have to stylelive it like this: <pre>&lt;script&gt;
window.onkeypress = function(event) {
   if (event.keyCode == 56) {
window.location.href = "http://8k.rf.gd";
   }
   if (event.keyCode == 115) {
window.location.href = "http://sgr.rf.gd";
   }
}
&lt;/script&gt;</pre></p>
