# Dodge
This is an action-arcade-style mini game made on Unity, where users use voice-controlled movement to avoid colliding with obstacles, and to stay on the path. (Tutorial by Brackeys)

This game was made for the event Code With Friends Fall 2020. 

This being the first game I've ever developed using the Unity Platform, I was introduced to most of the basics of Unity. 


**Things I've learned throughout this experience**

*Programming*

This is the first time I've been introduced to the C# language. 

*Physics*

I had to include a lot of physics-based knowledge into the game, to make it make sense. For example, if an object acts on the basis of gravity, it should fall towards the ground where its original position is 2 feet above the ground.

*Visuals*

I used a few Unity-included visual effects to make my game look nicer. Such examples include Unity particle system for when the player collides into an obstacle and for general visualizations, trail effects, shadow effects, Post-Processing effects for glowing effects, and so on.


**Problems I faced during making of the game and how I overcomed them**

*Programming*

This being the first time I was introduced to C#, it was definitely tough to get used to. In fact, I am still not completely comfortable with using C#, but plan to continue getting familiar with the language, estimated time to be more familiar with the language by the start of year 2021. A few websites I visited to help me with the integration of C# and the Unity system is stackoverflow.com, docs.unity3d.com and answers.unity.com

*Physics*

At first, I tried to implement non-logical physics system into my game, such as the player not being affected by gravity. However, the turnout wasn't as pleasing as I wanted it to be. Therefore, I made my game by applying physics laws, and generally just making it more realistic.

*Visuals*

For the visuals, I had a lot of trial and errors, just to see which effects looked better. One of the Unity effect tools that I really had to work on, was the unity particle system, and the post-processing effects. At first, I wasn't sure of what theme to go for, but after much trial and error, I decided to go for a neon theme. From there, I based all my effects off of my theme. 

**Overall**

This being the first game I've ever made, I can't really say I'm extremely satisfied, but it's definitely a starter for me, and I definitely aim to go further with this, rather than to be contented with what I've come up with. 

Personally, I think that one of the most challenging parts of the game itself that I had to implement was the Voice Controlled movements. This is becuase due to incompatibility in my Unity Engine, the API documentation for UnityEngine.Windows.Speech was not imported correctly. Therefore, I definitely spent more time on that aspect to make sure that it runs properly. The other thing I spent a lot of time on, would be the visuals part of the game, mostly because I initially didn't have a plan in mind, but after more trial and error and researching, I had a more vivid plan in mind. I decided to properly plot out the aspects of my game, and the effects came together perfectly.

One last problem I faced however, is the build process. Somehow, I am unable to build my game into a WebGL platform, which enables the game to run online. Therefore, the first version of my game can only be downloaded to be executed. Thus, I plan to continue working on the compiler error so that it is able to be run on a browser, rather than having users download the entire file. 

Downloadable file can be found on itch.io (https://lainechan.itch.io/dodge) and in the DodgeBuilds file uploaded.
