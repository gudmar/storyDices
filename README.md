# storyDices

This is a little application that can be used to practice storry telling. There is a set of dices that are randomly sellected. Each dice contains a picture. 
Player should tell a story using symbols on each drawn dice. All dices can be resellected. If there is a problem with using one of dices, user might cilck on a particural 
dice to draw a next symbol.

## Features:
* Draw a set of dices. No sigle dice will repeat,
* Select number of dices to be drawn,
* Select one of topics (journeys, activities, general),
* select number of cubes to be drawn,
* Reselect a single dice,
* General rules of telling a story,
* About me tab
* Remember last selection in browser local storage, so on the same broser on the same device last sellections will be saved,
* Responsivenes - works fine on mobile devices,

## General rules of telling a story:
This appliaction was written for one of online table topics Toastmasters meeting. That is why rules for story telling harcoded to this application are 
based on toastmasters table topics rules:
* Story has to have an opener, body and conclusion,
* Less than 30s for preparation,
* Story should be at least 1 minute long, 
* Story should not be longer than 2 minutes (after 2:30 mamber is disqualificed

However one may play with different set of rules. It might be difficult to think of a story out of 12 dices in less than 30s and finish it before 2min :)

** Extending with more topics

Just edit symbols.js file to add new content. Remember. For everything to work as designed each topic should have at least maxNumberOfDices + 1 symbols. In this case 
at least 13 symbols should be placed. For symbol reference visit eg. https://www.w3schools.com/charsets/ref_utf_symbols.asp
