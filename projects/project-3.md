---
layout: project
type: project
image: images/cards.png
title: Baccarat
date: 2015
labels:
  - SQL
  - Java
summary: A baccarat game I developed for ICS 321 Database.
---

Baccarat is a game that I developed as my ICS 321 final project using Java that implemented a SQL database to record the outcome of every play.

SQL database was used to record the user's name, timestamp, player's hand, banker's hand, user's pick, the outcome, and the result.
This also allowed the game to display stats like the total number of hands.  It was slso used to display the number of times the outcome was Player, Banker, or a Tie.
<hr>
First, you would enter your name.
<img class="ui image" src="{{ site.baseurl }}/images/bac2a.png">
<hr>
Second, you would click either Player or Banker.
<img class="ui image" src="{{ site.baseurl }}/images/bac3a.png">
<hr>
Then it would display the results.
<img class="ui image" src="{{ site.baseurl }}/images/bac.png">
<hr>
Lastly, it would display stats from the database.
<img class="ui image" src="{{ site.baseurl }}/images/bac5a.png">
<hr>

To give you a flavor of the game, here is an excerpt from one run:

<hr>

<pre>
You open your eyes, and you are greeted by an unfamiliar ceiling.
Startled, you get to your feet and quickly scan your surroundings. It's
dark except for the stream of light coming from a crack on the only boarded
window in the room. You try to peek through the crack, but you cannot see
anything. You wonder where you are and who could have possibly brought you here.

<--------------------help------------------------>
Enter quit or one of the following commands -
Weld light look walk pickup inventory help h ?
<------------------------------------------------>

look
The room is a picture of decay with only a faded number identifying it as room-4. The bed you were
 lying on is stained with what looks like dried blood. Could it be your blood? No - it is not. The
 only way out of the room aside from the door to the corridor is a window that is boarded shut. It
 looks like it has been like that for decades. There is a door going west from here. You see a candle
 on the floor. You see a match on the floor.

pickup candle
- you are now carrying the candle -

pickup match
- you are now carrying the match -

light match candle

The candle is now lit. It illuminates everything in the room.

walk west
The corridor is lit with the candle. It is so long that you cannot see to the end. You notice that
 there are words written on the wall. There is a door going east from here. There is a way going north
 from here. There is a door going south from here.
</pre>

<hr>

Source: <a href="https://github.com/jogarces/ics-313-text-game"><i class="large github icon "></i>jogarces/ics-313-text-game</a>

