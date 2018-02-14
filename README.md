# Class3_Assignment

```ruby

<!DOCTYPE html>
<html>
<head>
	<title>Horroe Movie Name Generator </title>
</head>
<body>
	<h1> Welcome to My Horror Movie Name Generator! </h1>
	<script type="text/javascript">
		var horrorMovieLocations = ["Restroom", "Basement", "Forest", "Hospital", "Cheap hotel", "Basement", "Classroom", "Graveyard", "Abandoned apartment", "Taxi"]
undefined
var horrorMovieAdjectives = ["Supernatrual", "Gloomy", "Haunted", "Bloodcurdling", "Dreadful", "Fearful", "Creepy", "Eerie", "Horrific", "Scary"]
undefined
var horrorMovieTimeOfDays = ["Midnight", "Fullmoon", "Night", "When you wake up", "Morning", "Dusk"]
undefined
var randomAdjectives = horrorMovieAdjectives[Math.floor(Math.random() * 10)]

undefined
var randomTime = horrorMovieTimeOfDays[Math.floor(Math.random() * 6)]
undefined
var randomLocations = horrorMovieLocations[Math.floor(Math.random() * 10)]
undefined
var fullName = randomAdjectives + " " + randomTime + " in the " + randomLocations
undefined
console.log(fullName)
</script>

</body>

</html>
