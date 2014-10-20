10print-variations
==================

10PRINT Ports And Variations
----------------------------
The famous 1-line program 10PRINT created in BASIC, now ported to:

* Logo
* Scratch
* Twine
* PuzzleScript
* and a preview of ZZT-OOP!

10PRINT is a famous single line of code written in BASIC on the Commodore64 computer popular in the early 1980s. The line of code 10 PRINT CHR$(205.5+RND(1)); : GOTO 10 when written into the computer in Commodore 64 BASIC creates an infinite loop that draws a maze. When you RUN this code, the computer picks a random number either 0 or 1 and adds this to 205. Then it will PRINT either the "/" character (205) or the "\" character (206). And then it loops back to the beginning and starts again, over and over.

In 2013, a group of writers, thinkers, artists, coders collaboratively wrote the book on 10Print, tracing the history of the programming language BASIC, the intersection of code and mazes with modern and contemporary art, punch card computers, ancient textiles and tilework, and the beauty of studying computer code and translating programs between languages. I enjoyed the book and was inspired to write my own 10PRINT ports to other programming languages. After seeing numerous online discussions of porting 10PRINT to Python, Javascript, Ruby and many Processing variations I decided to branch out to seldom-used and unique programming languages for fun, for a challenge, and for glory.

LOGO
----

I first tackled LOGO, the famous 1967 educational programming language by Daniel G. Bobrow, Wally Feurzeig, Seymour Papert and Cynthia Solomon. In this language, the programmer guides a turtle (appears as a circle or turtle logo) around the screen with simple commands such as FORWARD 20 and LEFT 60. I tried out UCBLogo, the 1992 Logo designed by Brian Harvey at Berkeley, and the de facto Logo standard available for Mac, PC, Linux and more. I also tried Alan Smith's early 2000s-designed ACSLogo for OS X. And a few online Turtle/Logo coding sites. I created a working 10PRINT clone for each of these.

Scratch
-------
Next I tried my hand at Scratch, the children-friendly programming language that lets you "code" by snapping different code bricks together to make programs. Scratch was created at MIT and influenced heavily by LOGO, so the programs feel similar in code even if they look somewhat different. It's great to have this version get drawn by the Scratch cat mascot; it definitely feels very scratch-y. I also made an alternate variation with breakdancers, beatboxing and more graffiti-like drawing that I call the Hip Hop variation.
 Now it starts to get funny. 

Twine 
-----
Twine is an open source tool for telling interactive stories. It was created in 2009 by Chris Klimas, and is hugely popular for creating Choose Your Own Adventure-style text adventures. The twine software lets you edit the formatting of the text through javascript and a stylesheet. Like translating a poem between languages, anytime you create a port of a program, you have many options available. Although I could have written a 10print clone exclusively in javascript, I used twine and decided to create a text adventure 10print clone. I created several different pages of random / and \ text (Hand typed in. Is this cheating?) for 10 lines. I created links between pages of other hand-typed / and \ text. So you click on the room names in blue to jump to pages with different arrangements of the maze. Through the css stylesheet, the spacing between lines and letters was eliminated so that the text would look like a maze instead of spread out letters.

Puzzlescript
------------
Next I opened up the Puzzlescript site, created in 2013 by Stephen Lavelle. Puzzlescript is designed to allow you to create simple HTML 5 tile-like "puzzle games." Is it possible to use this engine or language, designed to make drag and drop, block-pushing style games, to create a version of the 10print maze? Yes, but like my twine approach, I had to create boards of text/imagery to do so. In this version, I created a level or board of several objects, each drawn to look like a forward or backslash, and each randomly placed on the board, and each with their own instructions on how they should move, either forward or backward or up and down. The motion of the player-character causes the other objects to move, creating the appearance of a randomly generated or moving 10print maze. Try pressing up, down, left and right.

ZZT-OOP
-------
Finally, a preview or germ of an idea. ZZT is a character-based video game created in 1991 by Tim Sweeney of Potomac Computer Systems/Epic MegaGames. It has a cult status online, and plenty of people still make their own ZZT games and distribute them online. ZZT includes ZZT-OOP a simple object-oriented scripting language. I have not yet written a port of 10PRINT but I have an idea how. I'd probably start by creating many / and \ objects with simple scripts to have them randomly move around. Why haven't I done this? Because I believe each character on the screen would have to be individually scripted or use the #BIND command to emulate another and I just am not sure I want to dedicate the several hours to do this. I have a feeling that a ZZT wizard out there may have alternate ideas or a simple way to script this. Let me know if you figure it out. 

All code/ideas above copyleft. 
   
