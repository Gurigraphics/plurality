# plurality

Modular Code Editor

![alt tag](http://i.imgur.com/s8GRW35.png)

## Plurality - Modular Code Editor

### About:

Plurality aims to be a middle ground between written and visual programming.


### The three tabs

- This window of program has three buttons: blocks, code and matrix.

The "button blocks" displays the "blocks".
The "button code" displays the "code of blocks".
The "button matrix" displays "all blocks" of this module.

Concept art image:

http://imgur.com/nTgrgAF.png


### The blocks tab

Create blocks
- To create a new block, you just need to enter a name and select a category.
- The category is useful to facilitate block searches.
- In this simplified example there is still no option to choose the block color.
- After creating a block this block is available in the search.

Edit code blocks
- To select a "code block", simply drag the block to "blocks tab".
- Then you can edit the code of block and also the name of block.
- After doing this, you can right click on the block and choose one of two options:

1- save changes
2- save as new block

If you choose "1- save changes" all blocks with this name, in all modules of the program will change.

If you choose "2- save as new block" you create a new block with this code. For this, you will also have to rename the block.

For example: "click_button_start", "click_button_credits", etc.


Concept art image:

http://imgur.com/f5g7Nv0.png


The code tab

- This tab displays all codes of blocks.
- This is the view of a common code editor.
- Realize that the name of this module appears in the comments.
- Each block also has comments with name: "click" and id: 001-0, 001-1, etc.
- The ID is formed by the position of the matrix and the order of the block in this position.
- You can also change this code so it will be changed in all blocks.
- But the comments should be preserved. They are used for the program to separate the modules. They are removed after the "final files" are compiled.


Concept art image:

http://imgur.com/IDYbdV3.png


The matrix tab

- This tab displays all the blocks of the array.
- In this edit mode, you can drag code snippets to different positions to organize your code.
- You can add new blocks.
- You can also show and edit the code blocks by clicking the arrow of each block.


### Some advantages:

- Modular programming: Plurality introduces a new conception of programming organization: using arrays and modules rather than separate folders and files.
- Lightning maintenance: When correcting a error, or improve a snippet of code, all blocks of the program can be changed simultaneously.
- Matrix Blocks: allows you to store 1,000 items in little space. And Matrix Blocks inside Matrix Blocks can store infinite information.
- End of spaghetti code: The modules of the organization block is much more intuitive.
- Reuse and share code: Code blocks allows full reuse of code. No need to always write the same thing. And you can also share your blocks.



## Comments:

### The first stage of this project is the construction of this modular code editor.

The program will be written in PHP, HTML and Javascript. Using Twitter bootstrap to layout and Json to data base arrays.


### The second stage of this project is to make this editor a Game Engine.

The Google Chrome Engine will be used as the "Browser" and "Server" built into the program.

The program will be able to of creating, copying and editing files with PHP and Store data with Json or use the Chrome database.

You will can choose and use different game frameworks: Phaser, Pixi.js, Cocos2d, SDL, XNA, etc. And create projects based on these frameworks. And also create blocks to speed and organize the development.


### The third stage of this project is to make this Game Engine a Engine Multi-language.

The idea is to write block codes with javascript and when export you can choose which framework to export.

So an Android game, for example, will be written in javascript, but when "compile-translation" is press, it will be translation into native language.

After having the code in native language, you can compile in any other program, while we do not have all it integrated in this engine.

How will this be done?

A standard library will be used, for example Phaser.

Phaser will have a block to create the entire main structure of the project, and a block to "Hello World" on the screen.

Android will also have a block to create the whole main structure of the project, and a block to make "Hello World" on the screen.

So you create an HTML5 game with Phaser, and use these two blocks, and test on Plurality itself, which is a "server" and "browser" and "editor".

Then, if there are both Android compatible blocks or other frameworks, you can export to all these languages ​​in native code.

This multi-language system is better than cross-platform. Because you are not restricted to a single framework or language. You can choose the best framework according to the requirements of each game.

### The fourth stage of this project is make this programm also an editor of scripts and narratives using the same system of arrays to organize the information and chapters of the story.

### The fifth stage of this project is make this programm also an editor of music or music tracker, also using the same system of arrays to organize the blocks of information.

### The sixth stage of this project is make this program an image and animation editor, for pixel art and svg, also using the same system of arrays to organize the blocks of information.

### The seventh stage of this project is insert in this program a lighting and particles editor.

### The eighth stage is to insert a Tile Editor.

### The ninth stage is to insert a management project, task and version.

### The tenth stage is to include a chat, realtime file sharing, save files in the cloud, a forum and a virtual store to share and sell templates, blocks and plugins.


## This is Plurality!
