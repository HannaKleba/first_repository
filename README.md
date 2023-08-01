# first_repository
funny
<!DOCTYPE html>
<html>
</head>
<body>


<h1> Bist du ein Idiot?</h1>
<button id="demo" onmouseenter="mouseOver()" >nein</button>
<button onclick="ja()">ja</button>
<button id="omed" onmouseenter="mouseOut()">nein</button>
<script>
function mouseOver() {
  document.getElementById("demo").style.visibility = "hidden" 
  document.getElementById("omed").style.visibility = "visible"
}
function mouseOut() {
  document.getElementById("demo").style.visibility = "visible"
  document.getElementById("omed").style.visibility = "hidden"
}

</script>
</body>
</html>
