# RunJavaScriptOnKeyPress
Automatically generates a thing to run JavaScript on a specific key-press

<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
<title>Run JavaScript on Key-Press</title>
</head>

<body>
<p>Input the charater you want to activate the JS here:</p>
<input type="text" size="20" maxlength="1" onkeypress="myFunction(event)">
<p>Paste your JavaScript you want to run:</p>
<input type="text" id="myText">
<p>Then press the "AddJS" button</p>
<button onclick="myFunction1()">AddJS</button>
<p><pre>&lt;script&gt;
window.onkeypress = function(event) {
   if (event.keyCode == <span id="demo">96</span>) {
      <span id="demo1"></span>
   }
}
&lt;/script&gt;
</pre></p>
<script>
function myFunction(event) {
  var x = event.which || event.keyCode;
  document.getElementById("demo").innerHTML = "" + x;
}
</script>

<script>
function myFunction1() {
  var x = document.getElementById("myText").value;
  document.getElementById("demo1").innerHTML = x;
}
</script>
</body>
</html>
