# 01: Object rotation & Color change

In this basic tutorial we will learn how to rotate a cube and how to apply a smooth color change at the same time:

    ![](0.gif)

## 1. Scene setup

First we must setup our scene. Apart from the default Main Camera and Light, we only need a cube:

1. Create a new scene: File menu > New Scene
2. Add a cube: GameObject menu > 3D Object > Cube
3. In Scene, double click the cube to focus it.
4. Select the Main Camera.
5. Align it with the Scene: GameObject menu > Align with View

    ![](1-1.png)

## 2. Adding a Program

As we want our cube to rotate continuously, we will need to add a suitable type of GameFlow program. That is the **On Update** program which executes its actions every frame, so it is perfect for the job:

1. Select the cube.
2. In the Inspector, click on the **Add Component** button.
3. Type `Gameflow` and press Return to add the component.

    ![](2-1.png)

4. In the Inspector, click on the + button in the GameFlow component.

    ![](2-2.png)

5. Select the **On Update** program in the block in the selector window and press Return (double click also works).

    ![](2-3.png)


## 3. Rotation

Now that we have a Program added to the GameFlow component, we need to add the actions that we want it to execute:

1. In the Inspector, click on the + button inside the **On Update** block in the GameFlow component.

    ![](3-1.png)

2. Type `setrot` to filter the actions in the selector window.
3. Select the Set Rotation action and press Return (or double click) to add it to the program.

    ![](3-2.png)

4. In the Set Rotation action, set the Angles property to 0, 2, 0 and Toggle the Relative property on.

    ![](3-3.png)

Now you can click the Play button in the Unity top toolbar and verify that the cube is rotating.

## 4. Color change

Why not adding a little bit of color to our cube? For that we will need another kind of program because the actions we will be executing would not work if we restart the program every frame like in On Update. We will use an On Start program for this:

1. In the Inspector, click on the + button (the one at the bottom) in the GameFlow component.

    ![](4-1.png)

2. Select the **On Start** program in the block in the selector window and press Return (or double click).
3. Add a **Loop** action to the **On Start** program. The Loop action will execute the contained actions :

    ![](4-2.png)

4. Now, we will generate a random color. Click on the + button in the Loop action and add a **Get Random Color** action.
5. The Get Random Color action has an Output field to indicate the Variable which the generated value will be sent to. You can create that Variable automatically by clicking in the inner + button of the Output field:

    ![](4-3.png)

6. You will see now a new Variable block of a different color and that Variable assigned in the Output field.

    ![](4-4.png)

7. Ok, now let's change the color of the cube! for that we will need to add an **Interpolate Color** action below the Get Random Color action:

    ![](4-5.png)

8. The last step is indicating the action that the destination color we will be using is the one stored in the Variable we have just created. For that, just click on the title of the Variable block and drag it into the To Color field of the Interpolate Color:

    ![](4-6.png)


Click the Play button and... Et voilà!

#

[Víctor Valenzuela](https://twitter.com/v4lv1k)
