# Stunt-pilot-2-with-creator-level

Description :

Stunt pilot 2 is a game flash SWF developed by Rock Solid Arcade. The servers were shut down and the game was abandoned. Archives of the game can be found all over the internet, but the last version didn't include level creation. Since it was a fan game, I am publishing the same version with the integrated level creation feature.
(Sadly, The scores, level save and multiplayer features are still unavailable [see end of note])

The game involves controlling and piloting a plane and making it pass through levels, the goal being to successfully make it pass through all the rings of a level so that the exit is accessible, and to earn points (previously an RSA server scoring system was displayed to show the best player scores but this is no longer available). As you progress through the levels, the difficulty of the level and the obstacles become increasingly difficult to avoid. At the start of the game, the player has 5 planes (lives), and this decreases if the plane crashes into an obstacle, ring, ground or runs out of fuel.

How do I open an SWF file?

SWF is a file format for Flash animations, often supported with Java between 2005 and 2015.
Java was abandoned around 2016, Flash games depend on it, they are converted to HTML5 (security and graphics). 
It can still be opened via Adobe Flash Player, Ruffle (very versatile) 

How do you control the plane?

Keyboard (move) and mouse (select buttons) required
Pivot backward (upward): Left or Up
Pivot forward (Descend): Right or Down
Accelerate : Space

Ability to invert rotation controls in options


What is the change compared to the Stunt Pilot 2 archives?

The current archives don't have the "Creation Level" feature. I remember playing Stunt Pilot 2 about eight years ago, and it had this "Creation Level" button that let you create your own game level, test it, save it to the RSA servers, and load it. It's quite fun to make your own level and be able to challenge friends locally on your computer.

So I was able to tinker with the script to try to find this functionality, and one night I was able to solve the problem by just displaying the button and the functionality.

There is no other change other than that, I just show the button that was hidden

Why did they remove "Creation Level" (Create Level) ?

The reason they removed it is that the developers of RSA or the site did not want to abandon this feature for an unknown reason on their part; maybe they thought it would cause a bug in the game (because the game has scripts that depend on RSA's servers, and since these are closed, the script may no longer make the game work). 

This is the case for the old archives (which you can find by going to the Wayback Archive website and entering the RSA URL (I think it's "rocksolidarcade.com"), in the date before 2014
(Make sure you have the ruffle app or extension)

You will notice that the game cannot be opened.  This is because the game is trying to access data from the RSA server but since then the link causes a security error due to an invalid certificate from the new server instead of the RSA server which therefore does not open the game.
This is also the case with the script, Rock Solid Arcade did not foresee the closure of the server in the development of the game

Is Creation Level/Create Level a cool game mode?

This is a way for a level editor or game editor, It's an experience that extends the playtime because it's more fun and it calls upon your creativity as a player to shape your own world.
It's very original because very few games (1 in 10) offer this, many games offer few possibilities and you remain stuck on a predetermined path, on the story of the game which ends.
Here, it feels like an open world where you can place as many obstacles as you want, anywhere and in any way you like. For a game from almost 2010, that's really cool.

How did you manage to put “Create level” back hidden/abandoned?

I used the software Js SWF Decompiler which allows you to deconstruct a SWF file in order to display and extract the file's components such as images, sounds, fonts, scripts, metadata


#Stunt-pilot-2 #Editor-level #Create-level #Creation-level
