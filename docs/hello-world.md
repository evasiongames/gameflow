# Hello, World!

After [installing GameFlow](installation.md), let’s do a quick sanity check to make sure GameFlow is working properly. For that, we will build a simple [Hello, World!](https://en.wikipedia.org/wiki/%22Hello,_World!%22_program) project.

Assuming GameFlow has been installed into your project, you should see a _Tools_ menu with _GameFlow_ as a sub-menu. Select _Tools &gt; GameFlow &gt; About_ and you should see the credits of the fine folk that worked to bring you GameFlow.

Once you have verified the menu is present, go to the _GameObject_ menu. Select _GameObject &gt; 3D Object &gt; Cube_. You should now see a simple white Cube in the center of your project.

Click **Add Component** in the Inspector, and search for the GameFlow component. Double-click to add it to your Cube.

Now that you have a GameFlow component attached to your Cube, click the \[+\] button to add a block.

Double-click on the _On Start_ program block \(the first one under Frequently Used\).

Now that you have an _On Start_ block, you’ll next add _Log Message_ Action.

Click on the \[+\] button inside of the On Start block.

Two plus buttons right next to each other might seem confusing at first! The bottom \[+\] will add another Program, the \[+\] inside the _On Start_ block will add an Action to perform when OnStart is called. After experimenting with GameFlow for a while you’ll get the hang of it.

Once you have added the _Log Message_ Action, all you have to do is pick a [logging level](https://docs.unity3d.com/ScriptReference/Logger.html) and a message - here, we are using the industry standard “Hello, World!” message, but feel free to get creative.

Once you are done setting up your log message, go to the [Game view](https://docs.unity3d.com/Manual/GameView.html) and click Play. Open the [Console window](https://docs.unity3d.com/Manual/Console.html) and you should see your message!

If all of this is working - congratulations, you’ve written your first GameFlow program!

