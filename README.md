# _ **Werewolf Run** _

Run your way through the forest jumping over rocks and spikey trees.

Just watch your back xD.

Game developed using Pygame and Tkinter.

Project done by,

Rahul Jain -IMT2020117

Deep Shashank -IMT2020129

Chinthan Chandra -IMT2020109

Tavva Akhil -IMT2020124

Shashank Shekhar -IMT2020112

# **INDEX**

1. Abstract
2. Introduction
3. System Requirements
4. Flowchart
5. Demonstration
6. Future Aspect
7. References


**Abstract:**

Initially we wanted to make a game. We went about surfing on the web for ideas to make a game using Pygame. We found out that we can a make plethora of games using Pygame.

We thought of a game where an animal chases a man where the whole game runs on an infinite loop.

The plan was to make an endless-arcade-action-running game. The game ends only when the user gets caught by the animal. The path the man is running on will have obstacles like trees or rocks. The speed of man and the animal changes at particular instants so that the user finds it harder to control.If man hits the obstacle and stops; the animal will catch up to him and the game will end.As long as man runs well, avoiding obstacles and keeping his distance from the animal, the game will continue. The moment man gets in contact with the animal, the game ends.

# **Introduction**

Werewolf Run is an arcade-action-running game where the user is chased by the wolf. Dodge the obstacles on your way and watch out for the wolf. Don&#39;t get caught if you want to live.

The speed of the player increases as he dodges more obstacles continuously. It&#39;s a full moon night and the wolf is waiting to find some fresh meat. Don&#39;t be the dinner.

The main aim of the game is to keep running and dodging the obstacles on the way for as long as you can.

Tkinter is used to make Main Menu and Toplevel Widget (End Menu), while Pygame is used to make the game.

**System Requirements**

1. **Computer:** Any laptop/PC with windows/Linux/Mac OS with Python installed and the following modules with it. The game performance in better in a PC with i5 processor or above.
  1. **Pygame Library:** Pygame is a cross-platform set of Python modules designed for writing video games. It includes computer graphics and sound libraries designed to be used with the Python programming language. The game runs on Pygame.
  2. **Tkinter Library:** Tkinter is the standard GUI library for Python. Python when combined with Tkinter provides a fast and easy way to create GUI applications. Tkinter provides a powerful object-oriented interface to the Tkinter GUI toolkit. Used to create the main menu of our game.

1. **Sprite sheets:** A sprite sheet is an image that consists of several smaller images (sprites) or animations. Combining the small images in one big image improves the game performance, reduces the memory usage and speeds up the startup time of the game. The game has a running man and a chasing animal, whose sprite sheets are taken from internet.
2. **Game background tile set:** Using a tile set makes it easier to create and edit games because the tiles get reused to make the scene in different variations. Game background image is taken from internet.
3. **Game audio:** Simply put, it is the art, science and technology of producing and configuring sounds for any kind of game or interactive media. The game audio and sound effects are taken from internet.

**Flowchart**

It has 5 options:

1)Play

2)Instructions

3)Story

4)Audio

5)Quit

![Shape1](RackMultipart20220210-4-1tlihzn_html_28b6fdff44d38408.gif)

Main Menu

![Shape2](RackMultipart20220210-4-1tlihzn_html_816249a0cbed7a1f.gif)

![Shape3](RackMultipart20220210-4-1tlihzn_html_d555850cbc8fcb31.gif)

![Shape4](RackMultipart20220210-4-1tlihzn_html_fff3d66279e10d69.gif)

Game Window

It shows:

1)The game

2)Score

![Shape5](RackMultipart20220210-4-1tlihzn_html_6ac04135a1094af4.gif)

![Shape6](RackMultipart20220210-4-1tlihzn_html_d555850cbc8fcb31.gif)

![Shape7](RackMultipart20220210-4-1tlihzn_html_fff3d66279e10d69.gif)

It shows 3 options:

1)Play again

2)Main Menu

3)End Game

Game Over Window

![Shape8](RackMultipart20220210-4-1tlihzn_html_1c729bc43e5e649.gif)

**Demonstration**

The demonstration will be done using one of our systems. We will show how the game runs and which key does what.

We will show the aspects such as speed increasing and the animation which is fit for every action being performed.

The main menu was built using Tkinter.it has functions which start the game or display instructions or show story or exit the window.

![](RackMultipart20220210-4-1tlihzn_html_d4994c200973d037.png)

The game window was created using Pygame and we used certain mathematical approach to the game too. The animation was done using sprite sheets. The background scrolling infinitely and the rest of it was done using sprites.

![](RackMultipart20220210-4-1tlihzn_html_cdaeb701d5b0d286.png)

The end menu was also built using Tkinter. This has functions which restart the game or go to the main menu or exit the game

![](RackMultipart20220210-4-1tlihzn_html_c38d085733562463.png)

**Future Aspect**

The game can be further extended to make it a 3-D game. We can introduce a story line with more details and add more objectives.

Rather than just keeping it in 2-dimension, we can improve the game to be more user interactive and add more features like invincibility, ability to fight the wolf, etc.

This will require more knowledge of game development which we might be able to learn in the future.

**References**

1. For Sprite sheets: [https://opengameart.org/](https://opengameart.org/)

1. For Sprite sheets: [https://www.spriters-resource.com/](https://www.spriters-resource.com/)

1. To remove background colour from sprite sheets: [https://www9.lunapic.com/editor/](https://www9.lunapic.com/editor/)
2. For Game background tile set: [http://unluckystudio.com/11-free-game-backgrounds/](http://unluckystudio.com/11-free-game-backgrounds/)
3.
4. To learn Pygame library: [https://www.digitalocean.com/community/tutorials/how-to-install-pygame-and-create-a-template-for-developing-games-in-python-3#:~:text=The%20pygame%20library%20is%20an,many%20platforms%20and%20operating%20systems](https://www.digitalocean.com/community/tutorials/how-to-install-pygame-and-create-a-template-for-developing-games-in-python-3#:~:text=The%20pygame%20library%20is%20an,many%20platforms%20and%20operating%20systems).

1. To learn Tkinter library: [https://www.geeksforgeeks.org/python-gui-tkinter/](https://www.geeksforgeeks.org/python-gui-tkinter/)

1. To learn Scrolling background for game and usage of sprite sheets: [https://youtu.be/US3HSusUBeI](https://youtu.be/US3HSusUBeI)
