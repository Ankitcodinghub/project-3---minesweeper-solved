# project-3---minesweeper-solved
**TO GET THIS SOLUTION VISIT:** [Project 3 – Minesweeper Solved](https://www.ankitcodinghub.com/product/project-3-minesweeper-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;12939&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Project 3 – Minesweeper  Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
For this project you are going to create a version of the classic game, Minesweeper. Your final version will look like this:

&nbsp;

If you’ve never played the game before, you can find a number of playable versions of this online.

To create this project you are going to use SFML (the Simple and Fast Multimedia Library) to do the work of drawing images to the screen and getting mouse input, while you will be responsible for everything else.

<h1><a name="_Toc12216"></a>Description</h1>
<h2><a name="_Toc12217"></a>Rules Overview</h2>
The rules of the game are as follows:

There exists a board, which contains a grid of spaces. A space could be a mine, or not. The player clicks on a space, and it gets revealed. The goal of the game is to reveal all the spaces that are not mines, while avoiding the spaces that are.

When a space is revealed:

If it’s a mine, the game ends

If it’s not a mine, it shows the number of mines <strong>adjacent to</strong> that space (anywhere from 0 to 8, with 0 just showing as an empty space)

– If a space has no adjacent mines, all non-mine spaces adjacent to it are also revealed The player uses the numbers as clues to figure out where other mines may be located.

When all of the non-mine spaces have been revealed, the player wins!

<h2><a name="_Toc12218"></a>Other features:</h2>
<strong>Flags</strong>: Right-clicking a space puts a flag on that space, marking it as a possible mine. Flagged spaces cannot be revealed (with left-clicks or as a result of adjacent spaces being revealed), but another rightclick will remove the flag.

<strong>Mine Counter</strong>: to track the number of mines that are on the board. Every time the player places a flag, the counter goes down by one. Every time they remove a flag, the counter goes up by one. The mine counter CAN go negative!

<strong>Restart Button</strong>: The smiley face centered at the top or bottom of the window lets you restart a new board with everything reset and mines randomized

<h2><a name="_Toc12219"></a>Non-standard features for your version of this project</h2>
<strong>Debug Button</strong>: Clicking this button will toggle the visibility of the mines on the board. Use this to help you test/debug various features of the game. Having to play the game properly each time you want to test something is very time-consuming. Creating these developer shortcuts helps speed up the development process

<strong>Test Buttons #1-3</strong>: Another development shortcut, clicking on these loads a file with a specific board layout, details on this later.

Those are the features that your game will need to have. The rules are pretty simple, but even simple games like this can be challenging to implement.

<h1><a name="_Toc12220"></a>Window / Board Setup</h1>
Most implementations of this game allow for variability in difficulty, board size, etc, but for this project you are going to use these dimensions and values:

<table width="0">
<tbody>
<tr>
<td width="312">Window Size</td>
<td width="312">800 x 600</td>
</tr>
<tr>
<td width="312">Mine count</td>
<td width="312">50 on randomly generated maps, determined by file in other cases (more on this later)</td>
</tr>
<tr>
<td width="312">Tile count</td>
<td width="312">25 x 16 (400 tiles total)</td>
</tr>
</tbody>
</table>
<h1><a name="_Toc12221"></a>SFML</h1>
The library that you will be using in this project is SFML—Simple Fast Multimedia Library. The first thing you would need to do is compile an application using this. Building an application using an external library can be a difficult thing, but it’s something that you typically only have to do once at the start of a project, and then you’re good to go until that project is finished.

To get started with SFML, visit this site:

<u><a href="https://www.sfml-dev.org/download/sfml/2.5.1/">https://www.sfml</a><a href="https://www.sfml-dev.org/download/sfml/2.5.1/">–</a><a href="https://www.sfml-dev.org/download/sfml/2.5.1/">dev.org/download/sfml/2.5.1/</a></u>

You want to download the appropriate version for the IDE/compiler that you are using. If you are using something that isn’t listed there, it is HIGHLY RECOMMENDED that you install and use one of the recommended tools. On Windows that would be Visual Studio, XCode on MacOS, etc. The links on that page are for already-compiled versions of the library which will work “out of the box” with the appropriate compiler.

Installing and compiling your first “Hello World” program can be a bit tricky, especially if you’ve never done it before. There are guides here: <u><a href="https://www.sfml-dev.org/tutorials/2.5/">https://www.sfml</a><a href="https://www.sfml-dev.org/tutorials/2.5/">–</a><a href="https://www.sfml-dev.org/tutorials/2.5/">dev.org/tutorials/2.5/</a></u><a href="https://www.sfml-dev.org/tutorials/2.5/">,</a> and certainly elsewhere online, but often the best source is from the developer’s themselves.

<h2><a name="_Toc12222"></a>SFML Basics</h2>
There are many guides and tutorials on how to use SFML, but the key features that you will be utilizing for this project are:

<table width="0">
<tbody>
<tr>
<td width="114">sf::Sprite</td>
<td width="510">These objects will let you draw some or all of a texture to the screen, the primary object that you will use to represent all aspects of the game</td>
</tr>
<tr>
<td width="114">sf:Texture</td>
<td width="510">These store external images that you program needs</td>
</tr>
<tr>
<td width="114">sf:Vector2f/i/u</td>
<td width="510">A 2-dimensional vector (an X and Y position), a location on the screen; the f/i/u at the end indicates the type of data used for storage (float, int, unsigned int)</td>
</tr>
<tr>
<td width="114">sf::Mouse</td>
<td width="510">The mouse class, giving you information about where the cursor is located, and whether or not a mouse button is pressed</td>
</tr>
</tbody>
</table>
<h2><a name="_Toc12223"></a>SFML Tutorials</h2>
This document will not replicate the wealth of information already out there about this library. The primary list of examples/tutorials can be found here: <u><a href="https://www.sfml-dev.org/tutorials/2.5/">https://www.sfml</a><a href="https://www.sfml-dev.org/tutorials/2.5/">–</a><a href="https://www.sfml-dev.org/tutorials/2.5/">dev.org/tutorials/2.5/</a></u>

From that page, a few in particular you will find useful for this project:

<u><a href="https://www.sfml-dev.org/tutorials/2.5/window-window.php">https://www.sfml</a><a href="https://www.sfml-dev.org/tutorials/2.5/window-window.php">–</a><a href="https://www.sfml-dev.org/tutorials/2.5/window-window.php">dev.org/tutorials/2.5/window</a><a href="https://www.sfml-dev.org/tutorials/2.5/window-window.php">–</a><a href="https://www.sfml-dev.org/tutorials/2.5/window-window.php">window.php</a></u> <u><a href="https://www.sfml-dev.org/tutorials/2.5/window-events.php">https://www.sfml</a><a href="https://www.sfml-dev.org/tutorials/2.5/window-events.php">–</a><a href="https://www.sfml-dev.org/tutorials/2.5/window-events.php">dev.org/tutorials/2.5/window</a><a href="https://www.sfml-dev.org/tutorials/2.5/window-events.php">–</a><a href="https://www.sfml-dev.org/tutorials/2.5/window-events.php">events.php</a></u> <u><a href="https://www.sfml-dev.org/tutorials/2.5/graphics-sprite.php">https://www.sfml</a><a href="https://www.sfml-dev.org/tutorials/2.5/graphics-sprite.php">–</a><a href="https://www.sfml-dev.org/tutorials/2.5/graphics-sprite.php">dev.org/tutorials/2.5/graphics</a><a href="https://www.sfml-dev.org/tutorials/2.5/graphics-sprite.php">–</a><a href="https://www.sfml-dev.org/tutorials/2.5/graphics-sprite.php">sprite.php</a></u>

Anything beyond that will not be applicable for this project (networking, audio, etc will NOT be used). Everything you see on the screen (each space, numbers, buttons, etc) will all be created and drawn the same way: load a texture, create one or more sprites from that texture, and then draw them to the screen.

You will have to load and store the images listed in the next section in sf::Texture objects.

<h1><a name="_Toc12224"></a>Images</h1>
For this project you will have a folder, creatively called <strong>images</strong>, where all of the images for this project will be stored. These images will all be loaded as sf::Texture objects to be used in the creation of sf::Sprite objects.

The images are as follows:

<table width="0">
<tbody>
<tr>
<td colspan="3" width="623"><strong>Game Images </strong></td>
</tr>
<tr>
<td width="158"></td>
<td width="120">mine.png</td>
<td width="345">The star of the game (although if you play properly, you’ll never see one!)</td>
</tr>
<tr>
<td width="158"></td>
<td width="120">tile_hidden.png</td>
<td width="345">What all tiles look like before they are clicked/revealed</td>
</tr>
<tr>
<td width="158"></td>
<td width="120">tile_revealed.png</td>
<td width="345">A revealed tile with no adjacent tiles</td>
</tr>
<tr>
<td width="158"></td>
<td width="120">number_#.png</td>
<td width="345">Tiles with the numbers 1-8 on them (replace # with the appropriate number. Used for tiles that have 1-8 adjacent mines</td>
</tr>
<tr>
<td width="158"></td>
<td width="120">flag.png</td>
<td width="345">Draw this on top of hidden tiles when they are flagged by the player as possible mines.</td>
</tr>
<tr>
<td colspan="3" width="623"><strong>UI Images </strong></td>
</tr>
<tr>
<td width="158"></td>
<td width="120">face_happy.png</td>
<td width="345">Click this button to reset the map. New mines, everything hidden, it’s like you restarted the program.</td>
</tr>
<tr>
<td width="158"></td>
<td width="120">face_win.png</td>
<td width="345">Victory!</td>
</tr>
<tr>
<td width="158"></td>
<td width="120">face_lose.png</td>
<td width="345">The opposite of victory! (It’s cool, no smiley faces were harmed during the creation of this project)</td>
</tr>
<tr>
<td width="158"></td>
<td width="120">digits.png</td>
<td width="345">Used for the digits on the “remaining mines” display. You can use this one texture for all the numbers, and change the “texture rect” of a sprite to draw a different portion of the image.

&nbsp;

The size of each digit (and the size of the texture rect you should use) is 21 x 32 pixels, and each digit would be offset by 21 (the width) times the digit you wanted.

&nbsp;

See <u><a href="https://www.sfml-dev.org/tutorials/2.5/graphics-sprite.php">https://www.sfml</a><a href="https://www.sfml-dev.org/tutorials/2.5/graphics-sprite.php">–</a><a href="https://www.sfml-dev.org/tutorials/2.5/graphics-sprite.php">dev.org/tutorials/2.5/graphics</a></u><a href="https://www.sfml-dev.org/tutorials/2.5/graphics-sprite.php">https://www.sfml-dev.org/tutorials/2.5/graphics-sprite.php</a><u><a href="https://www.sfml-dev.org/tutorials/2.5/graphics-sprite.php">sprite.php</a></u> for more information
</td>
</tr>
<tr>
<td width="158"></td>
<td width="120">debug.png</td>
<td width="345">Used to toggle debug mode</td>
</tr>
<tr>
<td width="158"></td>
<td width="120">test_1/2/3.png</td>
<td width="345">Used to load test files from which the board will be set</td>
</tr>
</tbody>
</table>
<h1><a name="_Toc12225"></a>Other Features</h1>
<h2><a name="_Toc12226"></a>Buttons</h2>
A button is really just an image that you can click on to make something happen. A more complex UI system would use an event/messaging system, but on a basic level you just need a sf::Sprite to represent the button, and every time the player clicks on something, you need to check if that mouse click occurred inside the boundaries of the sf::Sprite you’re using as the button.

If you’re drawing a sprite somewhere, you know its position (it’s 0, 0 by default, or whatever you set it to). You can get the width/height of the sprite through its textureRect, and then it’s just a matter of checking if the mouse position is inside that box.

<h2><a name="_Toc12227"></a>Adjacent Mines and Tiles</h2>
In order to calculate the number of nearby mines, as well as when revealing tiles, each tile should store a list of neighboring tiles. A tile could have <strong>UP TO</strong> 8 neighbors. An easy way to do this is with pointers. Since the number is a variable, a dynamically sized container would be perfect for this. You could also use a fixed-length array, since no tile will ever have more than 8 neighbors.

vector&lt;Tile *&gt; adjacentTiles; // Store each tile near us, the size() of each vector will vary

Tile* neighbors[8]; // Always 8 pointers, some of which might be nullptr

&nbsp;

&nbsp;

<h2><a name="_Toc12228"></a>Loading board from files</h2>
When clicking either of these buttons:

&nbsp;

You should open up one of the three files located in the “boards” folder. For Test #1, you should open “testBoard1.brd”, test #2 is “testBoard2.brd”, etc. These are plain text files, and you can open them in any text editor.

Those files contain a bunch of 0s and 1s to represent the layout of a particular map. Why use these? When developing any project, having some sort of test data, some known value, is essential. How you do you know if hundreds of randomly generated values are correct or not? That’s really difficult. How do you know if your code to set a series of tiles to mines (or not) is working? Try setting to a specific pattern that you created (or someone provided for you).

<table width="0">
<tbody>
<tr>
<td width="312"><strong>testBoard </strong></td>
<td width="311"><strong>testBoard2 </strong></td>
</tr>
<tr>
<td width="312">1000000000000000000000000

0000000000000000000000000

0000000000000000000000000

0000000000000000000000000

0000000000000000000000000

0000000000000000000000000

0000000000000000000000000

0000000000000000000000000

0000000000000000000000000

0000000000000000000000000

0000000000000000000000000

0000000000000000000000000

0000000000000000000000000

0000000000000000000000000

0000000000000000000000000

0000000000000000000000000

&nbsp;
</td>
<td width="311">0000000000000000000000000

0000000000000000000000000

0011111011110111101111100

0000100010000100000010000

0000100011000011000010000

0000100010000000100010000

0000100011110011000010000

0000000000000000000000000

0000011100100010011000000

0000001000101010100100000

0000001000010100100100000

0000001000010100011000000

0000000000000000000000000

1110111010101000110100100

1010100010101000100100100

1110111010101110100100000
</td>
</tr>
<tr>
<td width="312"></td>
<td width="311"></td>
</tr>
<tr>
<td width="312">testBoard loaded, no revealed tiles</td>
<td width="311">testBoard2 loaded, one tile on the edge revealed (which caused a cascaded of revealed tiles)</td>
</tr>
</tbody>
</table>
&nbsp;

<h1><a name="_Toc12229"></a>Code Structure</h1>
With larger programs, you can accomplish the goal in any number of ways. There isn’t a single way to write this that works better above all others. From the outside perspective (i.e. that of a player), your application needs to DO various things:

<ul>
<li>When the player clicks a space, reveal it.</li>
<li>When the player clicks the restart button, reset the board.</li>
<li>If a mine is revealed, end the game. And so on.</li>
</ul>
HOW you choose to accomplish those things is up to you. If you want to write a single, gigantic main() function, you are free to do so—that approach is not recommended, however. A few suggestions:

A class to represent the board. This represents the core data object in the game.

A class for tiles/spaces. The board is made up of a whole lot of these things. Each one of these can be a mine, have a flag, some number of adjacent tiles/mines, etc.

Many programs (games or otherwise) do the same things over and over again while the application is running. The ability to easily (in code) reset everything is critical. Think about what sorts of helper functions you might want to make that happen. Things like:

Restarting the board

Setting or clearing tiles of flags

Setting or clearing mines (singly or in large quantites)

Recalculating the number of adjacent mines Etc…

<h1><a name="_Toc12230"></a>Mouse Interactions</h1>
The application can really do “nothing” until the user clicks their mouse. Typically games and many other applications are clearing/redrawing the screen on a regular basis (often dozens of times a second).

Once the player has clicked, however (you can check for this in the event loop), you then need to do some checks about that click.

<strong>Where did they click? </strong>

Is that a valid space on the board anywhere? If so, should you do anything in response to this?

<strong>Did the player just click a mine?</strong>

Boom, game over!

If not a mine, reveal the tile

<strong>Revealing a tile </strong>

If the number of adjacent mines is 0, reveal any neighboring tiles as well (as long as they aren’t mines) In revealing those, do the same sort of check for any neighbors to that tile… (sounds a bit like recursion here!)

<h1><a name="_Toc12231"></a>Storing Resources</h1>
While a program is running, it needs RESOURCES to get the job done—things like icons, textures, sound files, etc. Many of the resources need to be stored for long-term use, as they may be called upon time and time again… but you don’t always know when they’ll be needed when you compile your code.

A great storage container for assets that you want to reference by name is the <strong>map</strong>&lt;&gt;. Storing something that you can access by its name with container[“NameOfAsset”] is vastly preferable to that of dealing with arrays—was “GameOver.png” stored in array[25], or array[26]?

You may find it helpful to create a single storage container for all of the sf::Texture objects, and then pass that around to any class which might need those files.

<h1><a name="_Toc12232"></a>Using Documentation</h1>
Reading through documentation, help files, guides, tutorials, etc is an absolutely critical skill that you must develop. The problem you are currently trying to solve, the exact combination of variables for your scenario might not have existed before now.

The One True Answer to your problem might not be out there on the Internet, in a StackOverflow.com question, or in a video on YouTube. However, the information to help you figure out PARTS of your problem are almost certainly out there. You will have to figure out how to make sense of those smaller bits of information and decide on a proper course of action.

For example, the data referenced sf::Texture objects disappears when the object is deleted, or falls out of scope. You can’t create a sf::Texture inside a function, create a sf::Sprite from that texture, and then use the sprite outside the function. An example of this (and what not to do) in the documentation:

<u><a href="https://www.sfml-dev.org/tutorials/2.5/graphics-sprite.php#the-white-square-problem">https://www.sfml</a><a href="https://www.sfml-dev.org/tutorials/2.5/graphics-sprite.php#the-white-square-problem">–</a><a href="https://www.sfml-dev.org/tutorials/2.5/graphics-sprite.php#the-white-square-problem">dev.org/tutorials/2.5/graphics</a><a href="https://www.sfml-dev.org/tutorials/2.5/graphics-sprite.php#the-white-square-problem">–</a><a href="https://www.sfml-dev.org/tutorials/2.5/graphics-sprite.php#the-white-square-problem">sprite.php#the</a><a href="https://www.sfml-dev.org/tutorials/2.5/graphics-sprite.php#the-white-square-problem">–</a><a href="https://www.sfml-dev.org/tutorials/2.5/graphics-sprite.php#the-white-square-problem">white</a><a href="https://www.sfml-dev.org/tutorials/2.5/graphics-sprite.php#the-white-square-problem">–</a><a href="https://www.sfml-dev.org/tutorials/2.5/graphics-sprite.php#the-white-square-problem">square</a><a href="https://www.sfml-dev.org/tutorials/2.5/graphics-sprite.php#the-white-square-problem">–</a><a href="https://www.sfml-dev.org/tutorials/2.5/graphics-sprite.php#the-white-square-problem">problem</a></u>

<h1><a name="_Toc12233"></a>Tips</h1>
Any libraries or APIs that you work with will have some sort of documentation. READ IT! You absolutely MUST get used to being able to sift through information to find the answers that you are looking for.

Don’t be afraid to experiment! When getting access to new code, you have to figure out how it works. Documentation is all fine and good, but at some point you have to actually DO IT yourself. Learning by doing is the most effective way. Write some code, screw it up, fix that code, do it all over again.

Don’t try to write the entire program all at once. Hard-code test values if you need to. Try to get one single tile working on a basic level (position, responding to mouse clicks, etc) before creating dozens/hundreds of them.

Think about what types of classes or functions you might want to have for this project. There is a board, a board has tiles, tiles have various properties or states… How do you want to store that data? An array? A vector&lt;&gt;? A 2-dimensional array?

You’re the one writing the code! Write it in a way that makes sense to you. Everyone tackles problems a bit differently, find an approach that works for you.<strong> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </strong><strong>&nbsp;</strong>

&nbsp;
