# CD_Django_NinjaGold
Troy Center troycenter1@gmail.com June 2017
Coding Dojo Django Ninja Gold assignment

<strong>Assignment: Ninja Gold (Django Version)</strong>
Recreate the Ninja Gold game from flask, this time using Django.

For this assignment, you're going to create a mini-game that helps a ninja make some money! When you start the game, your ninja should have 0 gold. The ninja can go to different places (farm, cave, house, casino) and earn different amounts of gold. In the case of a casino, your ninja can earn or lose up to 50 golds. Your job is to create a web app that allows this ninja to earn gold and to display past activities of this ninja.

<strong>Guidelines</strong>
Refer to the wireframe below.
Have the four forms appear when the user goes to http://localhost
In other words, use a hidden input tag value in the form to pass the relevant location to the server
Have /process_money determine how much gold the user should have (hint: you’ll have to set up a custom routing rule)
For this assignment, we’re not using a database. Just save the activity logs in session

<strong>Bonus</strong>
Refactor your code to remove the hidden input and instead use a route parameter

<img src="http://s3.amazonaws.com/General_V88/boomyeah/company_209/chapter_3832/handouts/chapter3832_6611_ninja-gold-ci.png" alt"Coding Dojo Assignment Image">
