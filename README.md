# Coursework

Description of unique components:
In the mdei_uddate page, there is a few select additional unique components, these being the use of bootstrapper to create the two column layout, this was done by creating a general div for the entire two columns to be put into with the id of "container" 
and then there was an additional div used to initialise the whole process to create the multiple columns, this div having the ID of "row align-items-start". Then there was the final pair of divs that made up each of the columns, the first one, one on the 
left, having the ID "col order-1" and the second one, the one on the right, having the ID of "col order-2", this making the columns appear side by side, though additional things did need to be added to make them render the correct way, as in making each 
columns have a minimum of 50% of the screens width and also the div thats has ID "container" has a class associated with it that sets it minimum width to be 100%. This was also used in the reviews page as a way to get the split between the reviews made and 
where the user can input their own review.

Another unique thing that's on the media_update page, there's some javascript that on a click of a button, it will show a video that the user can play if they want to. When the button is clicked, it will call the function called "revealVideo" thats in the 
script, this calling on two variable, "videoRevealButton" and "divForVideo", both of tehse being set to the ID of the button and div respectfully. In the function, it gets the ID for the div and then changes whats inside it, replaing the empty video tag with 
the new one that will show the video along with the tags inside of it to allow the user to play it and also give it a small width so it won;t be too obtrusive while it's being shown.

Finally, on the reviews page, there is a form that allows users to input a review. This is done by the both input boxes (one for name and one for the review) being checked to see if they are populated, this is done by using a function that is called when the
button to submit is pressed, it will set two variables to be equal to that of the IDs of the two boxes and also of the review text, after that there will be a first if statesment that checks to see if the name input has anything inside of it, if there's nothing 
it will show an alert and then ask the user to input a name. If the review text box is empty then it will do the same but check if it's length equals zero and if it is, it will send another alert asking the user to please input a review. Once all that is done,
three additional functions will be called, one that will grab the value within name and also the ID and then insert the name into the div thats on the left side of the page to fill out the empty "h3" element thats in there, this is also repeated again for the 
actual review text but this time, instead of inserting into a "h3" element, it's just a "p" element as it's just plain text, this is done in the "send_review" function. The final function called "play_sound" is there just to play the sound when sending in the 
review is successful, it does this by setting a variable called "sound" as an audio type and also getting and loading the file needed, after this the sound gets played within the javascript function and right after that, it's time will be reset back to zero so the
next review can be inputted and also still play the sound.



Sounds :-
-Ding: 
PIXABAY, n.d.. 328 royalty-free ding sound effects. [online]. Berlin, Germany: Pixabay. Available from: https://pixabay.com/sound-effects/search/ding/ [Accessed 13th April 2024]. 

Images :-
Logo:
M. HASSAN, 2020. Download Tank, Weapon, Silhouette, Royalty-Free Vector Graphics - Pixabay. [online]. Berlin, Germany: Pixabay. Available from: https://pixabay.com/vectors/tank-weapon-silhouette-military-5376792/ [Accessed 16th April 2024].

Profile Pictures:
E. BLINTSOV, n.d.. World of Tanks UI Art. [online]. Monteal, Canada: ArtStation. Available from: https://asylumcat.artstation.com/projects/8YKbn [Accessed 4th April 2024].

Code:-
Code for playing the sound
STACKOVERFLOW, 2012. Immediate play sound on button click in HTML page. [online]. Amsterdam, Netherlands: Stack Exchange Inc. Available from: https://stackoverflow.com/questions/12953928/immediate-play-sound-on-button-click-in-html-page [Accessed 12th April 2024].

Code for video reveal on button click:
SHECODES, 2023. [JavaScript] - How to replace HTML content when a button is clicked in JavaScript . [online]. Lisbon, Portugal: SheCodes. Available from: https://www.shecodes.io/athena/46753-how-to-replace-html-content-when-a-button-is-clicked-in-javascript [Accessed 14th April 2024].

Code for creating columns:
Bootstrap, n.d.. Columns - Bootstrap v5.0. [online]. San Francisco, California: Bootstrap. Available from: https://getbootstrap.com/docs/5.0/layout/columns/ [Accessed 4th April 2024].