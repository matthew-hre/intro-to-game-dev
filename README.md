# Intro to Game Development

So you wanna make video games? Well, you've come to the right place! This document will teach you the basics of game development, and give you a solid foundation to build on. This document
will cover everything from general game design, to programming, to art, to sound, and more. It will also cover some popular game engines and resources, and include plenty of references to videos, books, or articles.

This guide was made for the Mount Royal University Game Design and Development Club.

## Table of Contents

- [Game Design](#game-design)
  - [What is Game Design](#what-is-game-design)
  - [What are some different genres?](#what-are-some-different-genres)
  - [Where do I start?](#where-do-i-start)
  - [Roadmapping](#roadmapping)
  - [Game Design Resources](#game-design-resources)
- [Programming](#programming)
  - [Intro to Python](#intro-to-python)
  - [Intro to Java](#intro-to-java)
  - [C# in a nutshell](#c-in-a-nutshell)
- [Art](#art)
  - [Intro to Aseprite](#intro-to-aseprite)
  - [Intro to Blender](#intro-to-blender)
  - [Photoshop for Pixel Art](#photoshop-for-pixel-art)
  - [Extra Tools and Resources](#extra-tools-and-resources)
- [Sound](#sound)
  - [Intro to Audacity](#intro-to-audacity)
  - [Intro to FL Studio](#intro-to-fl-studio)
  - [BFXR and SFXR](#bfxr-and-sfxr)
  - [Extra Tools and Resources](#extra-tools-and-resources-1)
- [Game Engines](#game-engines)
  - [Unity (C#)](#unity-c)
  - [Godot ("python-ish", C#)](#godot-python-ish-c)
  - [Unreal Engine (C++)](#unreal-engine-c)
  - [GameMaker Studio (GML)](#gamemaker-studio-gml)
  - [MonoGame (C#)](#monogame-c)
  - [Extra Tools and Resources](#extra-tools-and-resources-2)

## Game Design

### What is Game Design?

Game design is the process of designing the content and rules of a game. This includes the game's story, characters, environment, props, sound, interface, and more. Game design is a very broad topic, and can be broken down into many sub-topics. For example, level design is the process of designing the levels in a game. This includes the layout of the level, the placement of enemies, the placement of items, and more. Another example is character design, which is the process of designing the characters in a game. This includes the character's appearance, personality, abilities, and more. Game design is a very important part of game development, and is often overlooked by beginners. It's easy to jump right into programming, but it's important to lay some groundwork before anything. It's important to understand that game design is not just about making a game look good, but also about making it fun to play.

### What are some different genres?

Arguably the most important part of game design is the genre. The genre of a game dictates what type of game you're making. There are many different genres, and each one has its own unique set of rules and mechanics. Some of the most popular genres are:

- Action
- Adventure
- Role-Playing
- Simulation
- Strategy
- Sports
- Puzzle

From there, we can break down what I call the "subgenres". The main genre of a game covers the content of the game, more the setting or overall theme. The subgenre dictates how that theme will be conveyed **mechanically**. Game mechanics are how you interact with the world around you, and how that world interacts with you. Some common subgenres are:

- Platformer
- First Person Shooter
- Top Down Shooter
- Turn Based Strategy
- Real Time Strategy
- Visual Novel
- Point and Click
- Roguelike
- Metroidvania

Once you combine a genre and a subgenre, you can begin to craft your game around a set of tried and true rules or guidelines. Here are some examples:

- Strategy Real Time Strategy
  - Age of Empires
  - Starcraft
  - Command and Conquer
- Action Platformer
  - Super Mario
  - Celeste
  - Super Meat Boy
- Top Down Shooter Roguelike
  - The Binding of Isaac
  - Enter the Gungeon
  - Nuclear Throne

There's tons of combinations out there, and plenty of genres and subgenres to explore.

### Where do I start?

Let's go through the process of designing a game together! We'll use an old game of mine, [Rorschach](https://whycardboard.itch.io/rorschach), as an example.

First, let's pick a genre: what kind of game do we want to make? With Rorschach, I wanted to come up with a puzzle game, so the puzzle genre was a great fit.

For the subgenre, I wanted to try my hand at a platformer. I thought these two genres would work well together, so I decided to go with a puzzle platformer!

Now, for the main mechanic. We have some rules about platformers that we have to follow, but in order to create a puzzle game, how can we modify, expand, or limit these rules
to force the player to think differently? Well, what if the player can only see so many platforms? Maybe they have some sort of mechanic they have to use to see the rest of the platforms.

Now with my main idea in hand, I had a final genre and subgenre: Puzzle Platformer. I also had a main mechanic: the player must use a mechanic to reveal the platforms.

### Roadmapping

When working on a project, it's good to break down the steps you'll need to take to complete it. This is called roadmapping. Roadmapping is a great way to keep track of your progress, and to make sure you're on track to finish your project. It's also a great way to keep yourself motivated, as you can see your progress as you go. Here's an example of a roadmap for Rorschach:

- [x] Create a player
  - [x] Have the player move, jump, and fall with gravity
  - [x] Have the player collide with platforms
  - [x] Create a simple image, or **sprite**, for the player
- [x] Create a platform
  - [x] Have the platform collide with the player
  - [x] Create a simple sprite for the platform
- [x] Create a level
  - [x] Create a level layout
  - [x] Add a start and end point
- [x] Add the main mechanic
  - [x] Add some way to indicate how much ink a player has
  - [x] Add a way to drop ink onto platforms
  - [x] Set all platforms to be invisible at the start of the level, and only become visible when ink is dropped on them
- [x] Add a way to win
  - [x] Add a way to detect when the player reaches the end of the level
  - [x] Add a way to change levels
  - [x] Add restarting a level after death.
- [x] Finishing touches
  - [x] Add a title screen
  - [x] Add a way to quit the game
  - [x] Add a way to pause the game
  - [x] Create some sound effects
  - [x] Create some music

That's a lot of steps, but most of them are pretty small! It's important to break down your project into small, manageable steps. This will make it easier to keep track of your progress, and will make it easier to stay motivated.

It's also ok to scrap steps, reorder things, or restart all together. Game development should be fun, and if you're getting stressed, worried, or losing interest, make adjustments to keep yourself engaged.

### Game Design Resources

- [Game Maker's Toolkit](https://www.youtube.com/playlist?list=PLc38fcMFcV_vToz9Nvc_YQTNH8hkIQ2uC)<br/>
  A great YouTube channel that covers all aspects of game design. Highly recommended. This is his playlist
  of videos on game design, but he also has videos on specific games, genres, or mechanics.

- [WIRED by Design](https://www.youtube.com/watch?v=78rPt0RsosQ)<br/>
  A great talk by Ian Bogost, who talks about what makes games fun.

- [Game Design is Hard](https://www.youtube.com/watch?v=VYnVyuUOHl8)<br/>
  A great video talking about the difficulties of game design.

## Programming

This is your meat and potatoes, your skeleton. This is the backbone of what will become your game. Programming is the process of writing code that tells the computer what to do. This code can be written in many different languages, and can be used to do many different things. For example, you can write code to make a website, or code to make a game. You can write code to make a program that does math, or code to make a program that plays music. Programming is a very broad topic, and can be broken down into many sub-topics. Programming is a very important part of game development, and is often overlooked by beginners. It's important to understand that programming is not about making a game look good, but about making it playable, and fun to play.

### Intro to Python

If you're a student at Mount Royal University in a degree that involves computing, you should be taking COMP1701. This course will cover all the basics of programming for you, and has a fantastic textbook written by a super humble dude.
Python will introduce you to the concepts of datatypes, sequences, functions, loops, inputs, outputs, external files, and merging all these elements together into one cohesive package.

Here are a few resources to get you started:

- [Foundations of Python Programming](https://runestone.academy/ns/books/published/fopp/index.html?mode=browsing)<br/>
  This is one of the best online resources for learning Python. It assumes you're an absolute beginner, and is full of interactive excersizes.

- [Python Documentation](https://www.python.org/about/gettingstarted/)<br/>
  This is the official documentation for Python. It's a great resource for learning the language, and has a ton of examples.

### Intro to Java

This is where we start getting into the real content. Python laid out the building blocks for us, but this'll throw us right into the deep end. Object Oriented Programming
is a very important concept to understand, and Java is a great language to learn it in. It's used a lot in post-secondary education, and is a great language to learn
as it will introduce you to the concepts of classes, objects, inheritance, polymorphism, and more. These are critical for game development, as objects are
the building blocks of your game. You'll have a player object, an enemy object, a platform object, and more. These objects will have properties, like position, size, and color.
Learning how to create and use these objects is critical to game development, and to programming in general.

Here are a few resources to get you started:

- [Java Documentation](https://docs.oracle.com/javase/tutorial/java/index.html)<br/>
  This is the official documentation for Java. It's a... resource for learning the language, but is probably the most in-depth out there.

- [W3 Schools](https://www.w3schools.com/java/java_intro.asp)<br/>
  Primarily a home for documentation, W3 Schools has some great tutorials for Java.

- [Python to Java](https://github.com/matthew-hre/python-to-java)<br/>
  This was a guide I made in my first semester of University for my peers, since I work in Java professionally and know my way around. Thought I'd show people the ropes and all that.

### C# in a nutshell

If you learned Java, you've learned 90% of C#. C# is a very similar language, and is used in a lot of game engines. It's a great language to learn. C# is used in Unity, Godot, and MonoGame, so it's a great language to learn if you want to use any of those engines. It's also used in a lot of professional settings, and is really powerful for making desktop applications.

- [C# Crash Course](https://nerdparadise.com/programming/csharpforjavadevs)<br/>
  This is a great crash course for Java developers looking to learn C#.

- [C# Documentation](https://learn.microsoft.com/en-us/dotnet/csharp/tour-of-csharp/tutorials/)<br/>
  This is the official documentation for C#. It's a bit dry, but pretty comprehensive.

## Art

Art is the number one reason people will play your game, simple as that. If your game looks good, people will play it. If it doesn't, they won't. It's that simple. Art is a very broad topic, and can be broken down into many sub-topics. For example, pixel art is the process of creating art using pixels, which when used in a game, are called **sprites**. Another example is 3D modeling, which is the process of creating 3D models. This includes the model's shape, texture, and more. Art is a very important part of game development. It's important to understand that art is not just about making a game look good, but tying everything together.

### Intro to Aseprite

Aseprite is the best tool on the market for pixel art, period. It's great for beginners, but has been used on some of the biggest indie games out there like Celeste, Unpacking, or Stardew Valley. It's a great tool to learn, and is a great way to get into pixel art. It's also a great way to get into animation, as it has some great tools for animating sprites. It's a pretty penny, but is well worth the price.

- [Aseprite](https://www.aseprite.org/)<br/>
  The official website for Aseprite. You can buy it here, or on Steam.

Here are some great resources for learning Aseprite:

- [Aseprite Crash Course](https://www.youtube.com/watch?v=59Y6OTzNrhk)<br/>
  A great reference for most of the tools in Aseprite.

- [Intro to Pixel Art](https://www.youtube.com/watch?v=v-ibXM3xBjg)<br/>
  A great video on the basics of pixel art.

- [Tileset Workflow](https://www.youtube.com/watch?v=btnH0x7_1g8)<br/>
  Tilesets are a great way to make levels in a game. This is a quick look at how to make a tileset.

- [Sprite Animation](https://www.youtube.com/watch?v=iWvfaiiVuDI)<br/>
  A great video on how to animate sprites.

- [StudioMiniBoss](https://blog.studiominiboss.com/pixelart)<br/>
  A great blog on pixel art by the lead artist of Celeste. They have some great tutorials, and some great resources.

### Intro to Blender

If you're going the 3D game route, this is the tool for you. Blender is a free, open source 3D modeling tool. It's used by professionals and hobbyists alike, and is a great tool to learn. It's a bit daunting at first, but there's plenty of resources out there to help you learn.

- [Blender](https://www.blender.org/)<br/>
  The official website for Blender. You can download it here.

Here are some great resources for learning Blender:

- [Blender Crash Course](https://www.youtube.com/watch?v=nIoXOplUvAw)<br/>
  A great reference for starting in Blender.

- [Intro to Rigging](https://www.youtube.com/watch?v=9dZjcFW3BRY)<br/>
  If you're animating a character, you'll need to rig it. This is a great video on how to do that.

### Photoshop for Pixel Art

If you feel so inclined, you can use Photoshop for pixel art. It's not the best tool for the job, but it's a great tool to learn. It's also a great tool for editing sprites, or creating textures for 3D models.

- [Photoshop](https://www.adobe.com/ca/products/photoshop.html)<br/>
  The official website for Photoshop. You can buy it here for a ridiculous price.

Here are some great resources for learning Photoshop:

- [Photoshop Crash Course](https://www.youtube.com/watch?v=gKFZjRV7L_Q)<br/>
  A great reference for starting in Photoshop.

- [Pixel Art in Photoshop](https://www.youtube.com/watch?v=rLdA4Amea7Y)<br/>
  A great video on how to make pixel art in Photoshop.

### Extra Tools and Resources

There are tons of great tools out there that we haven't covered. Here are some of the best:

- [Piskel](https://www.piskelapp.com/)<br/>
  A great free online tool for making pixel art.

- [GIMP](https://www.gimp.org/)<br/>
  A great free alternative to Photoshop.

- [Krita](https://krita.org/en/)<br/>
  A great free alternative to Photoshop.

- [Inkscape](https://inkscape.org/)<br/>
  A great free alternative to Illustrator.

- [GraphicsGale](https://graphicsgale.com/us/)<br/>
  A great free alternative to Aseprite.

- [PlaySCII](https://jp.itch.io/playscii)<br/>
  A great free tool for making ASCII art.

- [OpenGameArt](https://opengameart.org/) and [itch.io](https://itch.io/game-assets)<br/>
  Great resources for free game assets. Sometimes you just need a quick sprite, and these are great places to look.

## Sound

A game's soundtrack is critical for establishing atmosphere, and immersing the player in the world you've created. Sound deals with both the music of your game, as well as any sound effects.

### Intro to Audacity

Audacity is a free, open source audio editing tool. It's a great tool for editing sound effects, or creating music.

- [Audacity](https://www.audacityteam.org/)<br/>
  The official website for Audacity. You can download it here.

Here are some great resources for learning Audacity:

- [Audacity Crash Course](https://www.youtube.com/watch?v=yzJ2VyYkmaA)<br/>
  A great reference for starting in Audacity.

- [Sound Effects for Video Games](https://www.youtube.com/watch?v=Kux_LvRl57U)<br/>
  A great video on how to make sound effects for video games.

### Intro to FL Studio

FL Studio is a paid audio editing tool. It's a great tool for creating music, and is used by professionals and hobbyists alike.

- [FL Studio](https://www.image-line.com/flstudio/)<br/>
  The official website for FL Studio. You can buy it here.

Here are some great resources for learning FL Studio:

- [FL Studio Crash Course](https://www.youtube.com/watch?v=pDIsEZsalAo)<br/>
  A great reference for starting in FL Studio.

- [Making Music for Games](https://www.youtube.com/watch?v=RtmFbohC0iw)<br/>
  A great video on how to make music for video games.

- [Undertale Music](https://www.youtube.com/watch?v=LPCBm59yFfI&t=105s)<br/>
  A famous FL Studio user, Toby Fox, made the music for Undertale in FL Studio. This is a great video on how he did it.

### BFXR and SFXR

These are great tools for spinning up some quick sound effects. They're free, and open source, and are great for beginners. They're also totally allowed in game jams, so they're a great tool to have in your back pocket.

- [BFXR](https://www.bfxr.net/)<br/>
  The official website for BFXR. You can download it here.

- [SFXR](https://www.drpetter.se/project_sfxr.html)<br/>
  The official website for SFXR. You can download it here.

### Extra Tools and Resources

Once again, there are tons of tools out there that we haven't covered. Here are some of the best:

- [BeepBox](https://www.beepbox.co/)<br/>
  A great free online tool for making music.

- [LMMS](https://lmms.io/)<br/>
  A great free alternative to FL Studio.

- [Audiotool](https://www.audiotool.com/)<br/>
  A great free online tool for making music.

- [Bosca Ceoil](https://boscaceoil.net/)<br/>
  A great free online tool for making music, super beginner friendly.

- [FamiTracker](http://famitracker.com/)<br/>
  A great free tool for making chiptune music, although it's a bit more advanced.

## Game Engines

Tackling a game engine will be the biggest hurdle you'll face. It's a lot to take in, and can be very daunting. It's important to remember that you don't need to know everything about a game engine to use it. You just need to know enough to get started. Once you get started, you can learn more as you go. It's also important to remember that you don't need to use a game engine to make a game. You can make a game from scratch, but it's a lot of work. Game engines are great because they do a lot of the heavy lifting for you, and let you focus on making your game. There are tons of game engines out there, and each one has its own pros and cons. It's important to find the one that works best for you. Here are some of the most popular game engines out there:

### Unity (C#)

Unity is one of the most popular game engines out there. It's used by professionals and hobbyists alike, and is a great engine to learn. It's a great engine for 3D games, and has the capabilities to handle 2D games as well. It's able to export to a ton of different platforms, and has a ton of great tools to help you make your game. It's also free to use, and has a great community behind it. Our executive Lawrence is a Unity expert, and is always happy to help out.

- [Unity](https://unity.com/)<br/>
  The official website for Unity. You can download it here.

| Pros                                       | Cons                                                         |
| ------------------------------------------ | ------------------------------------------------------------ |
| Extensive platform support                 | Steeper learning curve for beginners                         |
| Robust and powerful development tools      | Limited visual scripting options                             |
| Large and active community                 | Performance issues with complex scenes and high-end graphics |
| Asset Store with a wide range of resources | Lack of built-in support for certain advanced features       |
| Cross-platform development capabilities    | Limited support for native mobile features                   |
| Powerful 2D and 3D rendering capabilities  | Integration issues with certain third-party tools            |

Here are some great resources for learning Unity:

- [Unity Crash Course](https://www.youtube.com/watch?v=IlKaB1etrik)<br/>
  A great reference for starting in Unity.

- [Unity Documentation](https://docs.unity3d.com/Manual/index.html)<br/>
  The official documentation for Unity.

- [Brackeys](https://www.youtube.com/channel/UCYbK_tjZ2OrIZFBvU6CCMiA)<br/>
  A great YouTube channel with tons of Unity tutorials.

- [Unity Learn](https://learn.unity.com/)<br/>
  A great resource for learning Unity. It has a ton of tutorials, and is a great place to start.

### Godot ("python-ish", C#)

Unreal Engine is a powerful and widely-used game engine known for its stunning visual fidelity and advanced features. While Unity excels in 2D games, Unreal Engine shines in the realm of 3D games and photorealistic graphics. It offers a comprehensive set of tools for creating immersive and visually impressive experiences.

Godot is a great engine as it allows for several different programming languages. They have support for C# with .NET 6. which has a lot of great
features, and is a great language to learn. They also have support for GDScript, which is a language similar to Python. It's a great language to learn,
and is a lot more beginner friendly than C#. It's also a great language to learn if you're interested in or already know Python, as it's very similar.

- [Godot](https://godotengine.org/)<br/>
  The official website for Godot. You can download it here.

| Pros                                              | Cons                                                        |
| ------------------------------------------------- | ----------------------------------------------------------- |
| Free and open-source                              | Smaller community compared to some other engines            |
| Intuitive and beginner-friendly                   | Limited number of official tutorials and resources          |
| Node-based editor                                 | Limited third-party plugins and assets compared to Unity    |
| Efficient 2D and 3D rendering capabilities        | Less robust in terms of high-end graphics and performance   |
| Flexible and customizable                         | Limited built-in support for certain advanced features      |
| Supports multiple programming languages           | Mobile export can require additional setup and optimization |
| Active and growing community                      | Limited documentation in some areas                         |
| Dedicated support for version control             | Less extensive platform support compared to Unity           |
| Export to various platforms and operating systems | Less polished editor interface compared to some competitors |

Here are some great resources for learning Godot:

- [Godot Crash Course](https://www.youtube.com/watch?v=QftpPI5iYrY)<br/>
  A great reference for starting in Godot.

- [Godot Documentation](https://docs.godotengine.org/en/stable/index.html)<br/>
  The official documentation for Godot.

- [GDQuest](https://www.youtube.com/channel/UCxboW7x0jZqFdvMdCFKTMsQ)<br/>
  A great YouTube channel with tons of Godot tutorials.

### Unreal Engine (C++)

Unreal Engine is a powerful and widely-used game engine known for its stunning visuals and advanced features. While Godot excels in 2D games, Unreal Engine shines in the realm of 3D games and photorealistic graphics. It offers a comprehensive set of tools for creating immersive and visually impressive experiences.

One of the key strengths of Unreal Engine is its C++ support, offering flexibility and performance for more experienced developers. However, it also offers a visual scripting system called Blueprints for those who prefer a more code-free approach to programming.

- [Unreal Engine](https://www.unrealengine.com/en-US/)<br/>
  The official website for Unreal Engine. You can download it here.

| Pros                                                    | Cons                                                       |
| ------------------------------------------------------- | ---------------------------------------------------------- |
| Stunning visuals                                        | Steeper learning curve compared to some other engines      |
| Advanced rendering capabilities                         | Requires a more powerful hardware to run complex scenes    |
| Robust and feature-rich development tools               | C++ programming can be challenging for beginners           |
| Blueprint visual scripting system                       | Larger file sizes compared to some other engines           |
| Cross-platform support                                  | Longer iteration times due to compilation of C++ code      |
| Active and supportive community                         | More resource-intensive than some other engines            |
| Extensive documentation and tutorials                   | Licensing fees and revenue sharing for commercial projects |
| Real-time collaboration and version control             | Frequent compatibility issues between updates              |
| Virtual reality (VR) and augmented reality (AR) support | More suitable for larger-scale projects with bigger teams  |

Here are some great resources for learning Unreal Engine:

- [Unreal Engine Crash Course](https://www.youtube.com/watch?v=ptCN4cysDig)<br/>
  A great reference for starting in Unreal Engine.

- [Unreal Engine Documentation](https://docs.unrealengine.com)<br/>
  The official documentation for Unreal Engine.

- [Unreal Engine Full Course](https://www.youtube.com/watch?v=bT8aSTkpkDY)<br/>
  A full comprehensive course on Unreal Engine.

### GameMaker Studio (GML)

GameMaker Studio is a popular game engine for making 2D games. It's used by professionals and hobbyists alike, and is a great engine to learn. It's able to export to a ton of different platforms, and has a ton of great tools to help you make your game. It's free to use to a point, but you'll need to pay to export to certain platforms. It has a great community behind it, and is a great engine to learn.

GameMaker has both a visual scripting system, and a programming language called GML. GML is very similar to JavaScript, and is a great language to learn if you're interested in or already know JavaScript. This is VP Matthew's engine of choice, and he's spent a lot of time tweaking it to his liking. He's sometimes happy to help out. Sometimes.

- [GameMaker Studio](https://www.yoyogames.com/en/gamemaker)<br/>
  The official website for GameMaker Studio. You can download it here.

| Pros                                        | Cons                                                        |
| ------------------------------------------- | ----------------------------------------------------------- |
| Beginner-friendly                           | Limited 3D capabilities compared to some other engines      |
| Drag-and-drop visual scripting              | Performance limitations for complex and demanding games     |
| Powerful and flexible coding language (GML) | Limited platform support compared to some other engines     |
| Rapid prototyping                           | Limited built-in support for certain advanced features      |
| Active and supportive community             | 2D-focused engine, may not be ideal for 3D game development |
| Extensive documentation and tutorials       | Requires a paid license for advanced features and exports   |
| Asset Marketplace for additional resources  | Limited built-in version control and collaboration features |
| Multi-platform support                      | Exporting to certain platforms may require additional setup |
| Seamless integration of audio and graphics  | Less robust in terms of high-end graphics and effects       |

Here are some great resources for learning GameMaker Studio:

- [GameMaker Studio Crash Course](https://www.youtube.com/watch?v=nBCDzE9MDbk)<br/>
  A great reference for starting in GameMaker Studio.

- [GameMaker Studio Documentation](https://docs2.yoyogames.com/)<br/>
  The official documentation for GameMaker Studio.

- [HeartBeast](https://www.youtube.com/channel/UCrHQNOyU1q6BFEfkNq2CYMA)<br/>
  A great YouTube channel with tons of GameMaker Studio tutorials.

- [GameMaker Studio Full Course](https://www.youtube.com/playlist?list=PLUEcBPiXnlBwNjhLWzJAQJ78deyXRIIZl)<br/>
  A full comprehensive course on GameMaker Studio.

### MonoGame (C#)

MonoGame is the open-source implementation of Microsoft's XNA framework, which is now properly obsolete. It's a great engine for 2D games, and has the capabilities to handle 3D games as well. It's able to export to a ton of different platforms, and has a ton of great tools to help you make your game. It's also totally free and open source. It's a great engine to learn if you're already familiar with C# and have strong object oriented programming skills.

MonoGame is not an engine, but a framework. This means a lot of the heavy lifting is done for you, but you'll need to do a lot of the work yourself. In a way, you'll be building the actual engine yourself.
It's a great way to learn how game engines work, and is a great way to learn how to make games from scratch. Matthew's done a fair bit of work in MonoGame, and is sometimes happy to help out. Sometimes.

- [MonoGame](https://www.monogame.net/)<br/>
  The official website for MonoGame. You can download it here.

| Pros                                       | Cons                                                         |
| ------------------------------------------ | ------------------------------------------------------------ |
| Free and open-source                       | Steeper learning curve for beginners                         |
| Cross-platform development capabilities    | Requires knowledge of programming languages (C#)             |
| Direct access to low-level APIs            | Less visual scripting options compared to some other engines |
| High performance and efficiency            | Limited built-in tools and features                          |
| Flexible and customizable                  | Documentation can be sparse or outdated in certain areas     |
| Robust community and active forums         | Less extensive asset marketplace compared to other engines   |
| Suitable for 2D and 3D game development    | Development workflow can be more manual and hands-on         |
| Compatible with existing XNA projects      | Less beginner-friendly compared to some other engines        |
| Integration with popular development tools | Limited support for certain advanced graphics techniques     |

Here are some great resources for learning MonoGame:

- [MonoGame Get Started](https://www.youtube.com/watch?v=sPH-sNTSrhw)<br/>
  A great reference for starting in MonoGame.

- [MonoGame Documentation](https://docs.monogame.net/)<br/>
  The official documentation for MonoGame.

- [MonoGame Full Course](https://www.youtube.com/playlist?list=PLZ6ofHM1rvK8lQSoKX1USZstM-ZXikFHp)<br/>
  A _really_ full comprehensive course on MonoGame.

### PyGame (Python)

If you're intimidated by C# or C++, PyGame is a great alternative. It's a great framework for 2D games, and has the capabilities to handle 3D games as well. It's able to export to a ton of different platforms, and has a ton of great tools to help you make your game. It's also totally free and open source. It's a great framework to learn if you're already familiar with Python and have strong object oriented programming skills.

Just like MonoGame, PyGame isn't an engine, but a framework. This means a lot of the heavy lifting is done for you, but you'll need to do a lot of the work yourself. You won't be goven tools like a level editor or a sprite editor, so you'll need to either implement these yourself, or use third party tools.

- [PyGame](https://www.pygame.org/news)<br/>
  The official website for PyGame. You can download it here.

| Pros                                    | Cons                                                          |
| --------------------------------------- | ------------------------------------------------------------- |
| Beginner-friendly                       | Limited built-in features and tools compared to other engines |
| Easy to learn and use                   | Performance limitations for complex and demanding games       |
| Python programming language             | Limited platform support compared to some other engines       |
| Lightweight and efficient               | Lack of built-in support for advanced graphics techniques     |
| Extensive documentation and tutorials   | Limited visual scripting options                              |
| Active community and resources          | Lack of a dedicated integrated development environment (IDE)  |
| Cross-platform support                  | May require additional libraries for specific functionalities |
| Open-source and free                    | 2D-focused engine, may not be ideal for 3D game development   |
| Integration with other Python libraries | Less suited for large-scale and complex game projects         |

Here are some great resources for learning PyGame:

- [PyGame Crash Course](https://www.youtube.com/watch?v=FfWpgLFMI7w)<br/>
  A great reference for starting in PyGame.

- [PyGame Documentation](https://www.pygame.org/docs/)<br/>
  The official documentation for PyGame. It's so ugly, we're sorry.

- [PyGame Full Course](https://www.youtube.com/watch?v=Q-__8Xw9KTM)<br/>
  A full comprehensive course on PyGame.

### Extra Tools and Resources

There are plenty of other great frameworks and engines out there. A great trick is to look into what your favourite games were made in, and see if you can find the engine they used. Here are some of the best:

- [Construct](https://www.construct.net/en)<br/>
  A great engine for quick 2D games. It's able to export to a ton of different platforms, and has a ton of great tools to help you make your game.

- [RPG Maker](https://www.rpgmakerweb.com/)<br/>
  A great engine for making RPGs. It's a great engine to learn if that's a genre you're interested in. It's able to export to a ton of different platforms, and has a ton of great tools to help you make your game.

- [Stencyl](https://www.stencyl.com/)<br/>
  A great engine for Mobile Games, although reviews are mixed.

- [Phaser](https://phaser.io/)<br/>
  A great framework for 2D games with JavaScript. It's used by hobbyists, and is a great framework to learn. It's totally free and open source.

- [React](https://reactjs.org/)<br/>
  This is a web framework, but can be hackjobbed into a game if needed. Matthew did this for [Ludum Dare 53](https://ldjam.com/events/ludum-dare/53/sender-not-found), and placed 10th in mood overall. It's a great framework to learn if you're interested in web development, less so for game development.

- [PICO8](https://www.lexaloffle.com/pico-8.php)<br/>
  This is a game engine, but it's a bit different. It's a fantasy console, which means it's a game engine that's built to look like a console. It's a great engine to learn if you're interested in retro games, and is a great way to learn how to make games from scratch. It's also a great way to learn Lua, which is a... language to learn if you're interested in or already know Python.
