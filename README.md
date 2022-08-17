# art33y
<!DOCTYPE html>
<html lang="en">
<head>

<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-9354309447195571"
     crossorigin="anonymous"></script>

	<meta name ="viewport" content="width=device-width,initial-scale=1.0">
	<title></title>
	<!-- Stylesheet -->
	<link rel="stylesheet" href="style.css">
</head>
<body>
	<div class="container">
		<input type="text" id="my-text"
		placeholder="Enter Name Here">
		<button id="btn">Tap In</button>
	</div>

<script>
	let myText = document.getElementByID("myText");
	let btn = document.getElementById("myId");

	myText.addEventListener("keyup", e => {
		e.preventDefault();
		if (e.keycode === 13){
			console.log("Clicked button");
			btn.click();
						}
});
btn.addEventListener("click", () => {
	alert("Clicked button");
});
</script>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-9354309447195571"
     crossorigin="anonymous"></script>
</body>
