---
permalink: /locations/
title: "Reviews"
layout: single
header:
  overlay_color: "#000"
  overlay_filter: "0.1"
  overlay_image: /photos/coffeebanner01.jpg
toc: false
author_profile: false
---

<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
/* Style the button that is used to open and close the collapsible content */
.collapsible {
  background-color: #777;
  color: white;
  cursor: pointer;
  padding: 18px;
  width: 100%;
  border: none;
  text-align: left;
  outline: none;
  font-size: 30px;
}

/* Add a background color to the button if it is clicked on (add the .active class with JS), and when you move the mouse over it (hover) */
.active, .collapsible:hover {
  background-color: #555;
}

/* Style the collapsible content. Note: hidden by default */
.content {
  padding: 0 18px;
  display: none;
  overflow: hidden;
  background-color: #f1f1f1;
}
</style>
</head>
<body>

<h2>Locations</h2>
<button type="button" class="collapsible">Florida</button>
<div class="content">
	<ul>
		<li>Alachua - Doxa Coffee Co.</li>
		<li>Gainesville - <a href="/_posts/2021-10-10-curia-on-the-drag.md">Curia on the Drag</a></li>
		<li>Gainesville - Opus Coffee</li>
		<li>Gainesville - Pascals Coffee House</li>
	  	<li>Gainesville - Volta Coffee, Tea & Chocolate</li>
	  	<li>High Springs - The Talented Cookie</li>
	  	<li>Orlando - Craft & Common</li>
	  	<li>Orlando - Foxtail Coffee</li>
	  	<li>Tampa - Buddy Brew Coffee</li> 
	  	<li>Tampa - Lady and the Mug</li>
	</ul>

</div>
<button type="button" class="collapsible">Oklahoma</button>
<div class="content">
	<ul>
		<li>Guthrie - Hoboken Coffee Roasters</li>
		<li>Oklahoma City - Clarity Coffee</li>
		<li>Oklahoma City - Coffee Slingers Roasters</li>
	  	<li>Oklahoma City - Elemental Coffee</li>
	  	<li>Stillwater - Aspen Coffee</li>
	  	<li>Yukon - Red Bird Coffee House</li>
	  	<li>Yukon - Summer Moon Coffee</li>
	  	<li>Yukon - Vacca Territory</li>
	</ul>
</div>
<button type="button" class="collapsible">Pennsylvania</button>
<div class="content">
	<ul>
		<li>Bryn Mawr - La Colombe Coffee Roasters</li>
	  	<li>Devon - Pour Richard's Coffee</li>
	  	<li>Philadelphia -  Coffee Roasters</li>
	</ul>
</div>

<script>
var coll = document.getElementsByClassName("collapsible");
var i;

for (i = 0; i < coll.length; i++) {
  coll[i].addEventListener("click", function() {
    this.classList.toggle("active");
    var content = this.nextElementSibling;
    if (content.style.display === "block") {
      content.style.display = "none";
    } else {
      content.style.display = "block";
    }
  });
}
</script>

</body>
</html>

