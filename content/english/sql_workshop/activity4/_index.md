---
title: "Select Multiple Info"
description: "Select Multiple Info"
date: 2020-07-13
prereq: "SELECT Command"
difficulty: "Beginner"
draft: false
translationKey: "sql_activity_4"
---
<!-- Links for javascript and CSS needed for drop down logic -->
<script type="text/javascript" src="_activity4.js"></script>
<link rel="stylesheet" href="../default/_type.css" type="text/css"></link>
<link rel="stylesheet" href="../default/_default.css" type="text/css"></link>
<script type="text/javascript" src="../default/alasql.js"></script>
<script type="text/javascript" src="../default/db.js"></script>
<script type="text/javascript" src="../default/_type.js"></script>


<!-- Embed YouTube Video Link here when ready -->

## Task 4: Find Their Dear Leader

After going to the Capital of Fun, you are told by the inhabitants to talk to their Dear Leader. Find out which inhabitant is the Dear Leader.
To do so, lets take a look at how to select multiple columns in a database.

![Commas](assets/Commas.png)

#### Now use what you learned to find out who is the leader of the Planet of Fun!

{{%notice tip%}}
**The Galactic Federation sends you a reminder that the 'galaxy' database holds the following columns:**

* planet_number: What order the planets show up in the database.

* planet: The name of the planet.

* leader: The name of the leader of the planet.

* population: How many inhabitants live on the planet.

* coordinate: The location of the planet in the galaxy.

**Hint: Only two columns are needed.**
{{%/notice%}}

### Question: Using the 'galaxy' database, how do you display the planets and their leader?


<!-- SQL Type In Activity -->
{{< rawhtml >}}

	<div class="terminal_div" id="terminal_div">
		<img class="terminal" src="../media/Terminal.png" alt="Terminal_screen" style="pointer-events:none">
		<div class="text-area">
			<textarea id="commands" placeholder="Enter command here!" style="resize: none"></textarea>
      <button class = "button reset" onclick="document.getElementById('commands').value = ''">Reset</button>
			<button class="button button1" onclick="sql()" style="top:0vw; left:0vw">	Enter </button>
		</div>
	</div>

	</br></br></br></br></br></br>
	<h1 class="error" id="sqlcommand" <h1 class="error" id="sqlcommand" style="visibility:hidden"><strong>ERROR INVALID INPUT></strong></h1>

	<table id="table">
		<tr>
		</tr>
	</table>

	<h4 id="story"></h4>

{{< /rawhtml >}}

<p>  </p>