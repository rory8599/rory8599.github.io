# interactive_detector
Repository for the Interactive Detector online game

Starting upload to github with the game at stage where random base 5 number is generated and user inputs answer with buttons.

6/4: In this update the game should be easy to integrate the tracks into. The game file no longer uses the React library, which was unneccesarily complicated, the display now also uses a whole detector instead of the quarter segement. At this point there is still the same game of show a random base 5 answer with button inputs but some files have been renamed and it's been restructured - so easy comparison may not be possible.

9/4: All the elements of the game are now fully functioning. Tracks are now fully working and now working on mainly aesthetic additions - highlighting subdetector info boxes on click, adding the rules etc. The main issues now are working on resizing the detector for different screens and generally just making the page look more appealing including fun facts, links to more info or more.

18/4: Updated the files with one which is responsive to different window sizes (although the canvas hasn't been fixed to change from 400x400)

19/4: Open new branch to start adding an introduction in the form of a multi-step dialog box. Fixing the canvas resizing issue, and improve resolution by setting the canvas dimensions to be much larger then it scales accordingly (this has caused issues with the ability to click on subdetectors and highlight the info - will need fixing if we wanna keep this feature)

27/4: The game now includes an introduction with interactive info tabs and additional links. At this point it is pretty much complete pending input from others. The only additions I want to add are: images for the particles info tab; and further animation for the particle tracks so they grow out from the centre.

29/4: This update should improve the style and for different devices. Also cut down the introduction significantly and added a button to show it again if needed.

29/4 (ii): Added a difficulty setting which varies the time tracks are shown. The tracks are now successfully animated to draw out from the centre - and should also be in quite an optimised way. The detector also shakes when a question is wrong - this may cause a bit too much lag so want to check that xx

4/5: Minor tweaks made to improve responsive web design and avoid tracks overlapping

10/5: More minor tweaks to hopefully improve the layout on mobiles - specifically to account for search bars in browsers on mobile which have a more significant impact. Also changed the game to show the number of particles correct instead of the level.

10/5 (ii): More adjustments to the layout so it fits better on mobile screen - moved the correct and wrong displays to the bottom left to give more space to the input area

13/5: Added a background similar to the CMS cavern. It's relatively simple and I'm putting it in with a view to adding a whole area above up to the surface which the player will travel through during the introduction. I wanna work on making this more stylized to add some more character which even this simple line drawing and textures does. I also want to find a better place to put the side panels as they don't look great on desktop and make the screen too busy. (I've also changed the buttons layout here so they shouldn't overflow - particularly with the hadron labels). I wanna test this version to see how the background (and buttons) fits on different devices
