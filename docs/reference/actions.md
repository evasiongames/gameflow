# Actions

## Activate GameObject

Activates the specified [GameObject](http://docs.unity3d.com/Manual/class-GameObject.html).

#### Properties:

* **Target** GameObject or Variable. The object to activate.

## Activate GameObjects In List

Activates the objects contained in the specified [List](data.md#list).

## Add Component

Adds a component to the specified [GameObject](http://docs.unity3d.com/Manual/class-GameObject.html).

## Add Force

Adds a force to the specified target [Rigidbody](http://docs.unity3d.com/Manual/class-Rigidbody.html) component.

## Add Force 2D

Adds a force to the specified target [Rigidbody2D](http://docs.unity3d.com/Manual/class-Rigidbody2D.html) component.

## Add Hierarchy To List

Adds the indicated GameObject and its hierarchy to the specified [List](data.md#list).

## Add Item To List

Adds an item to the specified [List](data.md#list).

## Add Selection To List

Adds the selected GameObjects to the specified [List](data.md#list).

## Add To String

Adds text to the specified [Variable](data.md#variable).

`1.0`

## Add Torque

Adds a torque to the specified target [Rigidbody](http://docs.unity3d.com/Manual/class-Rigidbody.html) component.

`1.0`

## Add Torque 2D

Adds a torque to the specified target [Rigidbody2D](http://docs.unity3d.com/Manual/class-Rigidbody2D.html) component.

`1.0`

## Attract

Attracts the specified target [Rigidbody](http://docs.unity3d.com/Manual/class-Rigidbody.html) towards the indicated point.

## Attract 2D

Attracts the specified target [Rigidbody2D](http://docs.unity3d.com/Manual/class-Rigidbody2D.html) towards the indicated point.

## Break

Stops the execution of the current block of actions.

## Cancel Web Request

Cancels the specified web request.

## Capture Screenshot

Captures and saves a screenshot as PNG file.

The output folder for the captured screenshot will be

## Change String Case

Changes the case of the text stored in the specified [Variable](data.md#variable).

## Clamp Local Position

Clamps the local position of the specified Transform.

`1.0`

## Clamp Local Rotation

Clamps the local rotation of the specified Transform.

`1.0`

## Clamp Position

Clamps the position of the specified Transform.

`1.0`

## Clamp Rotation

Clamps the rotation of the specified Transform.

## Clear Console

Clears the debug console.

## Clear List

Removes all items in the specified [List](data.md#list).

## Clear Particles

Removes all particles from the specified [ParticleSystem](http://docs.unity3d.com/Manual/class-ParticleSystem.html) or ParticleEmitter.

## Clone

Creates a duplicate or clone of the specified [GameObject](http://docs.unity3d.com/Manual/class-GameObject.html).

## Clone Material

Creates a clone of the specified Material.

## Comment

Adds a program comment as a text note. This is a no-op action.

## Concatenate Strings

Concatenates two strings and saves the result in the specified output [Variable](data.md#variable).

## Confine

Confines an object into the space defined by the specified Collider componente.

## Control Particles

Controls the specified ParticleSystem component.

`1.0`

## Control Video Player

Controls the specified VideoPlayer component.

`1.0`

## Copy Material

Copies the properties of the specified Material.

## Copy Transform

Copies the values of the specified Transform.

## Create Empty GameObject

Creates a new empty [GameObject](http://docs.unity3d.com/Manual/class-GameObject.html) with the specified name.

## Create Material

Creates a new [Material](http://docs.unity3d.com/Manual/class-Material.html) with the specified [Shader](http://docs.unity3d.com/Manual/class-Shader.html) assigned.

## Create Primitive

Creates a new primitive-type [GameObject](http://docs.unity3d.com/Manual/class-GameObject.html) with the specified name.

## Create Web Request

Creates and returns a web request object.

## Deactivate GameObject

Deactivates the specified [GameObject](http://docs.unity3d.com/Manual/class-GameObject.html).

## Deactivate GameObjects In List

Deactivates the objects contained in the specified [List](data.md#list).

## Decrement Parameter Value

Decrements the numeric value of the specified [Parameter](data.md#parameter).

## Decrement Variable Value

Decrements the numeric value of the specified [Variable](data.md#variable).

## Destroy

Destroys the specified [GameObject](http://docs.unity3d.com/Manual/class-GameObject.html) or component.

If the specified [GameObject](http://docs.unity3d.com/Manual/class-GameObject.html) belonged to a [Pool](tools.md#pool) it will released instead of destroyed.

## Destroy GameObjects In List

Destroys the objects contained in the specified [List](data.md#list).

## Disable Behaviour

Disables the specified Behaviour component.

## Disable Behaviours In List

Disables all the Behaviour components found in the specified [List](data.md#list).

## Disable Collider

Disables the specified Collider component.

## Disable Collider 2D

Disables the specified Collider2D component.

`1.2`

## Disable Component

Disables the specified Component.

## Disable Components In List

Disables all the components of the specified [List](data.md#list).

## Disable Program

Disables the specified Program.

## Disable Shader Keyword

Unsets a global shader keyword.

## Disable State Machine

Disables the specified [State Machine](programs.md#state-machine).

`1.0`

## Disable Timer

Disables the specified [Timer](tools.md#timer).

`1.0`

## Display Dialog

Displays a modal dialog and gets the user choice.

`1.0`

## Divide Parameter Value

Divides the numeric value of the specified [Parameter](data.md#parameter).

## Divide Variable Value

Divides the numeric value of the specified [Variable](data.md#variable).

## Dont Destroy On Load

Makes the object target not be destroyed automatically when loading a new scene.

#### Properties:

* **Target:** GameObject or Variable. The object to preserve.

## Draw Bounds

Draws the bounding box of the specified [Transform](http://docs.unity3d.com/Manual/class-Transform.html).

## Draw Bounds Frame

Draws the 2D frame of the bounding cube of the specified Object.

## Draw Collider

Draws the specified Collider component.

## Draw Collider 2D

Draws the specified Collider2D component.

`1.2`

## Draw Force

Draws the specified [Force](tools.md#force).

## Draw Line

Draws a line between the specified points.

`1.2`

## During

Executes the contained actions during the specified duration.

## Enable Behaviour

Enables the specified Behaviour component.

## Enable Behaviours In List

Enables all the Behaviour components found in the specified [List](data.md#list).

## Enable Collider

Enables the specified Collider component.

## Enable Collider 2D

Enables the specified Collider2D component.

`1.2`

## Enable Component

Enables the specified Component.

## Enable Components In List

Enables all the components of the specified [List](data.md#list).

## Enable Program

Enables the specified Program.

## Enable Shader Keyword

Sets a global shader keyword.

## Enable State Machine

Enables the specified [State Machine](programs.md#state-machine).

`1.0`

## Enable Timer

Enables the specified [Timer](tools.md#timer).

`1.0`

## Evaluate

Evaluates the specified conditions.

## Evaluate Conditions

Evaluates the specified conditions.

## Evaluate External

Evaluates the given expression in the containing web page.

This action will execute the given JavaScript code snippet in the web page that contains the WebPlayer or WebGL content.

## Evaluate Math Function

Evaluates the selected mathematical function.

## Execute Command

Executes the specified [Command](tools.md#command).

## Execute Program

Starts the execution of the specified Program.

#### Properties:

* **Program:** The Program to execute.
* **Force Restart:** Indicate whether the program must be restarted before executing it.
* **Wait For Completion:** Indicates whether the execution of the current program should stay hold until the executed program finishes..

## Exit Game

Quits the application.

## Fade In

Makes the specified [GameObject](http://docs.unity3d.com/Manual/class-GameObject.html) appear gradually.

## Fade Out

Makes the specified [GameObject](http://docs.unity3d.com/Manual/class-GameObject.html) disappear gradually.

## Find GameObject

Find a GameObject matching the specified search criterion.

`1.0`

## Find GameObjects

Finds GameObjects and puts them into the specified output list.

`1.0`

## Find Program

Finds a Program with the specified identifier.

`1.2`

## Find Shader

Finds a Shader with the given name.

## Finish Program

Finishes the specified Program.

## Flip

Flips the specified Transform.

## Follow

Makes a specified object follow another.

## Follow Path

Makes a specified object follow the specified [Path](tools.md#path).

## For

Executes the contained actions for a number of times specified by a numeric range.

## For Each

Executes the contained actions for each item of the specified [List](data.md#list).

## Freeze

Freezes the specified [Transform](http://docs.unity3d.com/Manual/class-Transform.html) component during the specified time.

## Game Over

Notifies the game is over.

## Get Angle

Gets the angle between two objects.

## Get Animation Property

Gets a property of the specified [Animation](http://docs.unity3d.com/Manual/class-Animation.html) component.

`1.0`

## Get Animator Parameter

Gets the value of the specified [Animator](http://docs.unity3d.com/Manual/class-Animator.html) parameter.

`1.0`

## Get Animator Property

Gets a property of the specified [Animator](http://docs.unity3d.com/Manual/class-Animator.html) component.

`1.0`

## Get Application Property

Gets the value of a property of the application.

## Get Area Effector 2DProperty

Gets a property of the specified [AreaEffector2D](http://docs.unity3d.com/Manual/class-AreaEffector2D.html) component.

## Get Audio Chorus Filter Property

Gets a property of the specified [AudioChorusFilter](http://docs.unity3d.com/Manual/class-AudioChorusFilter.html) component.

## Get Audio Distortion Filter Property

Gets a property of the specified [AudioDistortionFilter](http://docs.unity3d.com/Manual/class-AudioDistortionFilter.html) component.

## Get Audio Echo Filter Property

Gets a property of the specified [AudioEchoFilter](http://docs.unity3d.com/Manual/class-AudioEchoFilter.html) component.

## Get Audio High Pass Filter Property

Gets a property of the specified [AudioHighPassFilter](http://docs.unity3d.com/Manual/class-AudioHighPassFilter.html) component.

## Get Audio Low Pass Filter Property

Gets a property of the specified [AudioLowPassFilter](http://docs.unity3d.com/Manual/class-AudioLowPassFilter.html) component.

## Get Audio Property

Gets a general property of the audio system.

## Get Audio Reverb Filter Property

Gets a property of the specified [AudioReverbFilter](http://docs.unity3d.com/Manual/class-AudioReverbFilter.html) component.

## Get Audio Reverb Zone Property

Gets a property of the specified [AudioReverbZone](http://docs.unity3d.com/Manual/class-AudioReverbZone.html) component.

## Get Audio Source Property

Gets a property of the specified [AudioSource](http://docs.unity3d.com/Manual/class-AudioSource.html) component.

## Get Bounds Property

Gets the value of a property of the specified Bounds.

`1.2`

## Get Button Property

Gets a property of the specified [Button](http://docs.unity3d.com/Manual/script-Button.html) component.

## Get Camera Property

Gets a property of the specified [Camera](http://docs.unity3d.com/Manual/class-Camera.html) component.

## Get Canvas Group Property

Gets a property of the specified [CanvasGroup](http://docs.unity3d.com/Manual/class-CanvasGroup.html) component.

## Get Canvas Property

Gets a property of the specified [Canvas](http://docs.unity3d.com/Manual/UICanvas.html) component.

## Get Canvas Scaler Property

Gets a property of the specified Canvas Scaler component.

## Get Character Controller Property

Gets a property of the specified [CharacterController](http://docs.unity3d.com/Manual/class-CharacterController.html) component.

## Get Child

Gets a child of the specified [GameObject](http://docs.unity3d.com/Manual/class-GameObject.html).

## Get Closest Point

Gets the closest point on the specified Bounds or Collider.

`1.2`

## Get Collider 2DProperty

Gets a property of the specified Collider2D component.

## Get Collider Property

Gets a property of the specified Collider component.

## Get Color

Gets the color of the default material of the specified object.

## Get Color Component

Gets a specified component of the given color.

## Get Component

Gets a component of the specified [GameObject](http://docs.unity3d.com/Manual/class-GameObject.html).

## Get Component In Children

Gets a Component in the specified GameObject or any of its children.

## Get Component In Parent

Gets a Component in the upward hierarchy of the specified GameObject.

## Get Component Property

Gets a property of the specified component.

## Get Components

Gets a list of Components in the specified GameObject or any of its parents.

## Get Constant Force 2DProperty

Gets a property of the specified [ConstantForce2D](http://docs.unity3d.com/Manual/class-ConstantForce2D.html) component.

## Get Constant Force Property

Gets a property of the specified [ConstantForce](http://docs.unity3d.com/Manual/class-ConstantForce.html) component.

## Get Current State

Gets the current state of the specified [StateMachine](https://github.com/evasiongames/gameflow/tree/6faebaf2aabb6bd64785a4c90fd988e2e11be354/docs/reference/.md/README.md#state-machine).

## Get Direction

Gets the direction Vector that connects two points.

## Get Distance

Gets the distance between two points / objects.

## Get Dropdown Property

Gets a property of the specified [Dropdown](http://docs.unity3d.com/Manual/script-Dropdown.html) component.

## Get Farthest

Gets the farthest item in the specified [List](data.md#list) to an indicated reference point or object.

`1.0`

## Get First Child

Gets the first child of the specified [GameObject](http://docs.unity3d.com/Manual/class-GameObject.html).

## Get First Item From List

Gets the first item of the specified [List](data.md#list).

## Get First Raycast Hit

Gets the first hit after casting the specified [Ray](tools.md#ray).

## Get First Raycast Hit 2D

Gets the first hit after casting the specified [Ray](tools.md#ray) in the 2D space.

`1.2`

## Get Force Property

Gets a property of the specified [Force](tools.md#force).

## Get Fractional Part

Gets the fractional part of the specified numeric value.

## Get GUIText Property

Gets a property of the specified GUIText component.

## Get GUITexture Property

Gets a property of the specified GUITexture component.

## Get GameObject

Gets the GameObject that contains the specified Component.

`1.0`

## Get GameObject Property

Gets a property of the specified [GameObject](http://docs.unity3d.com/Manual/class-GameObject.html).

## Get Image Property

Gets a property of the specified [Image](http://docs.unity3d.com/Manual/script-Image.html) component.

## Get Impact Point

Gets the impact point after casting the specified [Ray](tools.md#ray).

## Get Index Of Item In List

Gets the index of the given item in the specified [List](data.md#list).

## Get Input Axis Value

Gets the current value of the specified input axis.

## Get Input Button State

Gets a boolean value indicating whether the specified input button is held down.

`1.0`

## Get Input Field Property

Gets a property of the specified [Input Field](http://docs.unity3d.com/Manual/script-InputField.html) component.

## Get Instance Id

Gets the instance identifier of the specified object.

`1.0`

## Get Integer Part

Gets the integer part of the specified numeric value.

## Get Item From List

Gets the item at the given index in the specified [List](data.md#list).

## Get JSONFrom List

Generates the JSON representation for the data contained in the specified [List](data.md#list).

## Get Joint 2DProperty

Gets a property of the specified Joint 2D component.

## Get Joint Property

Gets a property of the specified Joint component.

## Get Last Child

Gets the last child of the specified [GameObject](http://docs.unity3d.com/Manual/class-GameObject.html).

## Get Last Item From List

Gets the last item of the specified [List](data.md#list).

## Get Layer

Gets the layer of the specified [GameObject](http://docs.unity3d.com/Manual/class-GameObject.html).

## Get Lens Flare Property

Gets a property of the specified [LensFlare](http://docs.unity3d.com/Manual/class-LensFlare.html) component.

## Get Light Property

Gets a property of the specified [Light](http://docs.unity3d.com/Manual/class-Light.html) component.

## Get Line Renderer Property

Gets a property of the specified [LineRenderer](http://docs.unity3d.com/Manual/class-LineRenderer.html) component.

## Get List Count

Gets the number of items in the specified [List](data.md#list).

## Get Magnitude

Gets the magnitude of the specified vector.

## Get Material

Gets the first material of the specified object.

## Get Material Property

Gets a property of the specified Material.

## Get Mesh Filter Property

Gets a property of the specified [MeshFilter](http://docs.unity3d.com/Manual/class-MeshFilter.html) component.

## Get Mesh Renderer Property

Gets a property of the specified [MeshRenderer](http://docs.unity3d.com/Manual/class-MeshRenderer.html) component.

## Get Nav Mesh Agent Property

Gets a property of the specified [NavMesh](http://docs.unity3d.com/Manual/class-NavMesh.html) component.

## Get Nav Mesh Obstacle Property

Gets a property of the specified [NavMeshObstacle](http://docs.unity3d.com/Manual/class-NavMeshObstacle.html) component.

## Get Nearest

Gets the nearest item in the given [List](data.md#list) to a given point or object.

`1.0`

## Get Object From Pool

Requests a free object to the specified [Pool](tools.md#pool).

## Get Off Mesh Link Property

Gets a property of the specified [OffMeshLink](http://docs.unity3d.com/Manual/class-OffMeshLink.html) component.

## Get Offset

Gets an offset of the specified object.

## Get Outline Property

Gets a property of the specified [Outline](http://docs.unity3d.com/Manual/script-Outline.html) component.

## Get Parent

Gets the parent of the specified [GameObject](http://docs.unity3d.com/Manual/class-GameObject.html).

## Get Particle System Property

Gets a property of the specified [ParticleSystem](http://docs.unity3d.com/Manual/class-ParticleSystem.html) component.

## Get Path Property

Gets a property of the specified [Path](tools.md#path) component.

## Get Physics Property

Gets a property of the global Physics Settings.

## Get Platform Effector 2DProperty

Gets a property of the specified [PlatformEffector2D](http://docs.unity3d.com/Manual/class-PlatformEffector2D.html) component.

## Get Point Effector 2DProperty

Gets a property of the specified [PointEffector2D](http://docs.unity3d.com/Manual/class-PointEffector2D.html) component.

## Get Pool Capacity

Gets the maximum number of objects in the specified [Pool](tools.md#pool) component.

## Get Position

Gets the 3D world position of the specified object.

## Get Position 2D

Gets the 2D world position of the specified object.

## Get Position In Path

Gets a position in the specified [Path](tools.md#path) component.

## Get Program Property

Gets a property of the specified Program.

## Get Projector Property

Gets a property of the specified [Projector](http://docs.unity3d.com/Manual/class-Projector.html) component.

## Get Quaternion Component

Gets a component of the specified quaternion.

## Get Radial Offset

Gets an offset in a circle centered on the specified object.

## Get Random Color

Gets a random [Color](http://docs.unity3d.com/ScriptReference/Color.html) between the specified colors.

## Get Random Item From List

Gets a random item from the specified [List](data.md#list).

## Get Random Number

Gets a random number in the specified numeric range.

## Get Random Point In Collider

Gets a random point inside the space of the specified Collider.

## Get Random Point In Collider 2D

Gets a random point inside the space of the specified Collider2D component.

`1.2`

## Get Random Point In Collider List

Gets a random point in any Collider of the specified [List](data.md#list).

## Get Random Position

Gets a random 3D position in the specified space.

## Get Random Position 2D

Gets a random 2D position in the specified space.

## Get Random Rotation

Gets a random [Vector3](http://docs.unity3d.com/ScriptReference/Vector3.html) representing a rotation.

## Get Random Vector

Gets a random [Vector2](http://docs.unity3d.com/ScriptReference/Vector2.html) or [Vector3](http://docs.unity3d.com/ScriptReference/Vector3.html) value.

## Get Raw Image Property

Gets a property of the specified Raw Image component.

## Get Ray Point

Returns the position of the point at the given distance along the specified [Ray](tools.md#ray).

## Get Ray Property

Gets a property of the specified [Ray](tools.md#ray).

## Get Raycast Hit Property

Gets a property of the specified RaycastHit object.

## Get Raycast Hit Property 2D

Gets a property of the specified RaycastHit2D object.

`1.2`

## Get Raycast Hits

Adds to a given [List](data.md#list) the resulting hits after casting the specified [Ray](tools.md#ray).

## Get Raycast Hits Count

Get the number of impacts after casting the specified [Ray](tools.md#ray).

## Get Rect Property

Gets the value of a property of the specified Rect.

## Get Rect Transform

Gets the [RectTransform](http://docs.unity3d.com/Manual/class-RectTransform.html) component of the specified [GameObject](http://docs.unity3d.com/Manual/class-GameObject.html).

## Get Rect Transform Property

Gets a property of the specified Rect Transform component.

## Get Render Property

Gets a property of the global Render Settings.

## Get Rigidbody 2DProperty

Gets a property of the specified [Rigidbody2D](http://docs.unity3d.com/Manual/class-Rigidbody2D.html) component.

## Get Rigidbody Property

Gets a property of the specified [Rigidbody](http://docs.unity3d.com/Manual/class-Rigidbody.html) component.

## Get Rotation

Gets the rotation \(in Euler angles\) of the specified object.

## Get Rotation 2D

Gets the rotation \(Z axis only, in Euler angles\) of the specified object.

## Get SO Property

Gets the value of the specified ScriptableObject property using Reflection.

`1.0`

## Get Scale

Gets the 3D local scale of the specified object.

## Get Scale 2D

Gets the 2D local scale of the specified object.

## Get Scene Count

Gets the number of loaded scenes / scenes in Build settings.

`1.2`

## Get Scene Property

Gets a property of the current scene.

## Get Screen Point From World Point

Gets a 2D screen point from the specified 3D world point.

## Get Script Property

Gets the value of the specified script variable using Reflection.

## Get Scrollbar Property

Get a property of the specified [Scrollbar](http://docs.unity3d.com/Manual/script-Scrollbar.html) component.

## Get Selectable Property

Gets a property of the specified [Selectable](http://docs.unity3d.com/Manual/class-Selectable.html) component.

## Get Selected GameObject

Returns the currently selected GameObject.

`1.0`

## Get Selection

Completes the specified output [List](data.md#list) with the currently selected objects.

`1.0`

## Get Shadow Property

Gets a property of the specified [Shadow](http://docs.unity3d.com/Manual/script-Shadow.html) component.

## Get Skinned Mesh Renderer Property

Gets a property of the specified [SkinnedMeshRenderer](http://docs.unity3d.com/Manual/class-SkinnedMeshRenderer.html) component.

## Get Skybox Property

Gets a property of the specified [Skybox](http://docs.unity3d.com/Manual/class-Skybox.html) component.

## Get Slider Property

Gets a property of the specified [Slider](http://docs.unity3d.com/Manual/script-Slider.html) component.

## Get Sprite Property

Gets a property of the specified [Sprite](http://docs.unity3d.com/Manual/class-Sprite.html).

## Get Sprite Renderer Property

Gets a property of the specified [SpriteRenderer](http://docs.unity3d.com/Manual/class-SpriteRenderer.html) component.

## Get String Length

Gets the length in characters of the string stored in the specified [Variable](data.md#variable).

## Get Substring

Gets a part of the string stored in the specified [Variable](data.md#variable).

## Get Surface Effector 2DProperty

Gets a property of the specified [SurfaceEffector2D](http://docs.unity3d.com/Manual/class-SurfaceEffector2D.html) component.

## Get Tag

Gets the tag of the specified [GameObject](http://docs.unity3d.com/Manual/class-GameObject.html).

## Get Terrain Property

Gets a property of the specified Terrain component.

`1.2`

## Get Text Mesh Property

Gets a property of the specified [TextMesh](http://docs.unity3d.com/Manual/class-TextMesh.html) component.

## Get Text Property

Gets a property of the specified [Text](http://docs.unity3d.com/Manual/script-Text.html) component.

## Get Texture Property

Gets a property of the specified Texture.

## Get Time Property

Gets the value of a time-related property.

## Get Timer Property

Gets a property of the specified [Timer](tools.md#timer).

## Get Toggle Property

Gets a property of the specified [Toggle](http://docs.unity3d.com/Manual/script-Toggle.html) component.

## Get Trail Renderer Property

Gets a property of the specified [TrailRenderer](http://docs.unity3d.com/Manual/class-TrailRenderer.html) component.

## Get Transform

Gets the [Transform](http://docs.unity3d.com/Manual/class-Transform.html) component of the specified [GameObject](http://docs.unity3d.com/Manual/class-GameObject.html).

## Get Transform Direction

Transforms the specified direction from local space of the given [Transform](http://docs.unity3d.com/Manual/class-Transform.html) to world space.

## Get Transform Point

Transforms the specified point from local space of the given [Transform](http://docs.unity3d.com/Manual/class-Transform.html) to world space.

## Get Transform Property

Gets a property of the specified [Transform](http://docs.unity3d.com/Manual/class-Transform.html) component.

## Get Variable

Gets a variable with the specified id in the indicated scope.

## Get Vector Component

Gets a component of the specified vector.

## Get Velocity

Gets the velocity of the object containing the specified [Rigidbody](http://docs.unity3d.com/Manual/class-Rigidbody.html) component.

## Get Velocity 2D

Gets the velocity of the object containing the specified [Rigidbody2D](http://docs.unity3d.com/Manual/class-Rigidbody2D.html) component.

## Get Velocity Component

Gets a component of the velocity vector of the specified Rigidbody.

## Get Velocity Component 2D

Gets a component of the velocity vector of the specified Rigidbody2D.

## Get VideoPlayer Property

Gets a property of the specified VideoPlayer component.

`1.0`

## Get W

Gets the W component of the specified data structure.

## Get Web Request Property

Gets a property of the specified WebRequest object.

## Get Web Request Response

Gets the response to the specified web request.

## Get Wind Zone Property

Gets a property of the specified [WindZone](http://docs.unity3d.com/Manual/class-WindZone.html) component.

## Get World Point From Screen Point

Gets a 3D world point from the specified 2D screen point.

## Get X

Gets the X component of the specified Vector or Rect.

`1.0`

## Get Y

Gets the Y component of the specified Vector or Rect.

`1.0`

## Get Z

Gets the Z component of the specified Vector or Rect.

`1.0`

## Group

Executes all enabled actions in the group simultaneously.

## Hello World

Prints the 'Hello, World!' message in the console.

## Hide Mouse Cursor

Hides the mouse cursor.

## Hide Parameter

Hides the specified [Parameter](data.md#parameter).

## If

Executes the contained actions conditionally.

Notice the action has two sequences of actions: the default or "Then" or default sequence and the alternative or "Else" sequence, which is initially hidden.

You can toggle the visibility of the Else sequence by clicking on the **=** icon placed on the right side of the Then Actions title.

The If action works like this: If the result of the evaluation of the conditions is true, the "Then" sequence will be started, otherwise the Else will be executed.

The effect of the [Break](https://github.com/evasiongames/gameflow/tree/6faebaf2aabb6bd64785a4c90fd988e2e11be354/docs/reference/.md/README.md#Break) action when it is contained in an If action is not only breaking the current sequence, but also breaking the loop or program where the If is contained.

## Ignore Collision

Makes the collision detection system ignore all collisions between the specified layers or Colliders.

`1.0`

## Ignore Collision 2D

Makes the collision detection system ignore all collisions between the specified layers or Collider2D components.

`1.2`

## Increment Parameter Value

Increments the numeric value of the specified [Parameter](data.md#parameter).

## Increment Variable Value

Increments the numeric value of the specified [Variable](data.md#variable).

## Insert In String

Inserts text in the specified [Variable](data.md#variable).

## Insert Item In List

Inserts an item in the given index of the specified [List](data.md#list).

## Instantiate

Creates an instance of the specified Prefab.

## Interpolate

Interpolates the specified [Transform](http://docs.unity3d.com/Manual/class-Transform.html) component to match another.

## Interpolate Color

Interpolates the color of the specified [GameObject](http://docs.unity3d.com/Manual/class-GameObject.html) to match another.

## Interpolate Value

Interpolates the value of the specified [Variable](data.md#variable).

## Invert String

Inverts the text stored in the specified [Variable](data.md#variable).

## Invoke Method

Executes the specified method using Reflection.

## Limit Parameter Value

Limits the value of the specified [Parameter](data.md#parameter).

## Limit Variable Value

Limits the value of the specified [Variable](data.md#variable).

## Limit Velocity

Limits the velocity of the specified 3D object.

## Limit Velocity 2D

Limits the velocity of the specified 2D object.

## Load Scene

Loads the scene with the specified name or build index.

## Log Message

Prints a message in the Console window.

## Look At

Sets the rotation of the specified object so it looks at the given target.

## Look At 2D

Sets the rotation of the specified object so it looks at the given target.

## Loop

Executes the contained actions repeately until a Break action.

## Loop In Current Frame

Forces execution of the current looping action in the current update frame.

`1.0`

## Loop In Next Frame

Forces execution of the current looping action in the next update frame.

`1.0`

## Map Vector

Maps the components of the vector stored in the specified [Variable](data.md#variable).

## Move

Moves the specified object to match the given target position.

## Move Randomly

Moves the specified object to a random position.

## Multiply Parameter Value

Multiplies the numeric value of the specified [Parameter](data.md#parameter).

## Multiply Variable Value

Multiplies the numeric value of the specified [Variable](data.md#variable).

## On State

Executes the contained actions if the current [State](programs.md#state) is the currently in executiong in the [State Machine](programs.md#state-machine) it belongs to.

On State is basically a shortcut for an [If](actions.md#if) with a [Current State](conditions.md#current-state-condition) condition.

The effect of the [Break](actions.md#break) action when it is contained in an On State action is not only breaking the current sequence, but also breaking the loop or program where the On State is contained.

## Open URL

Opens the specified Url in the default browser.

## Orbit

Rotates the target [Transform](http://docs.unity3d.com/Manual/class-Transform.html) around the specified pivot.

## Pause Editor

Pauses the Unity Editor.

## Pause Game

Pauses the game.

## Play Animation

Starts the playback of the specified animation \([Animation](http://docs.unity3d.com/Manual/class-Animation.html) or [Animator](http://docs.unity3d.com/Manual/class-Animator.html)\).

## Play Music

Plays the specified music with optional volumen fading.

## Play Sound

Plays the specified sound as it was in front of the camera.

## Play Sound At Source

Plays the sound at the specified [AudioSource](http://docs.unity3d.com/Manual/class-AudioSource.html).

## Random Wait

Waits for a random time interval.

## Recalculate Path

Recalculates the specified [Path](tools.md#path).

## Remove Item From List

Removes an item from the specified [List](data.md#list).

## Repeat

Executes the contained actions for the specified number of times.

## Repeat Until

Executes the contained actions repeately until the conditions are met.

## Replace In String

Gets a new replaced version of the text stored in the specified [Variable](data.md#variable).

## Reset Language

Sets the default language as the current for localization purposes.

#### Properties:

* **Language:** SystemLanguage. The language to set as current.

## Reset Pool

Releases all the objects in the specified [Pool](tools.md#pool).

## Reset Timer

Resets and stops the specified [Timer](tools.md#timer).

## Reset Variable Value

Resets the value of the specified [Variable](data.md#variable) to the default persistent value.

`1.0`

## Resize List

Sets the size \(number of items\) in the specified [List](data.md#list).

## Restart Program

Restarts the specified Program.

## Restart Timer

Restarts the specified [Timer](tools.md#timer).

## Restore Collision

Restores the detection of collisions between the specified layers or Colliders.

`1.0`

## Restore Collision 2D

Restores the detection of collisions between the specified layers or Collider2D.

`1.2`

## Resume Game

Resumes the game if it was paused.

## Resume Timer

Resumes the specified [Timer](tools.md#timer).

## Rotate

Rotates the specified object to match the given target rotation.

## Rotate Randomly

Rotates the specified object randomly.

## Round Variable Value

Rounds the numeric value of the specified [Variable](data.md#variable).

## Save Data

Saves the persistent data.

## Scale

Scales the specified object to match the given target scale.

## Scale Randomly

Scales the specified object to a random scale.

## Scroll Material Texture

Changes the offset of a Texture of the specified Material.

## Select

Selects the specified UI component.

## Send Command

Sends the [Command](tools.md#command) with the specified Id to a target GameObject and executes it \(if exists\).

## Send Command To List

Sends a [Command](tools.md#command) to all objects contained in the specified [List](data.md#list).

## Send Message

Calls the specified method on every MonoBehaviour of the target GameObject.

## Send Web Request

Sends the specified web request and optionally waits for a response.

## Set Animation Property

Sets a property of the specified [Animation](http://docs.unity3d.com/Manual/class-Animation.html) component.

`1.0`

## Set Animator Parameter

Sets the value of the specified [Animator](http://docs.unity3d.com/Manual/class-Animator.html) parameter.

`1.0`

## Set Animator Property

Sets a property of the specified [Animator](http://docs.unity3d.com/Manual/class-Animator.html) component.

`1.0`

## Set Animator State

Changes the state of the specified [Animator](http://docs.unity3d.com/Manual/class-Animator.html).

## Set Application Property

Sets a general property of the application.

## Set Area Effector 2DProperty

Sets a property of the specified [AreaEffector2D](http://docs.unity3d.com/Manual/class-AreaEffector2D.html) component.

## Set Audio Chorus Filter Property

Sets a property of the specified [AudioChorusFilter](http://docs.unity3d.com/Manual/class-AudioChorusFilter.html) component.

## Set Audio Distortion Filter Property

Sets a property of the specified [AudioDistortionFilter](http://docs.unity3d.com/Manual/class-AudioDistortionFilter.html) component.

## Set Audio Echo Filter Property

Sets a property of the specified [AudioEchoFilter](http://docs.unity3d.com/Manual/class-AudioEchoFilter.html) component.

## Set Audio High Pass Filter Property

Sets a property of the specified [AudioHighPassFilter](http://docs.unity3d.com/Manual/class-AudioHighPassFilter.html) component.

## Set Audio Low Pass Filter Property

Sets a property of the specified [AudioLowPassFilter](http://docs.unity3d.com/Manual/class-AudioLowPassFilter.html) component.

## Set Audio Property

Sets a general property of the audio system.

## Set Audio Reverb Filter Property

Sets a property of the specified [AudioReverbFilter](http://docs.unity3d.com/Manual/class-AudioReverbFilter.html) component.

## Set Audio Reverb Zone Property

Sets a property of the specified [AudioReverbZone](http://docs.unity3d.com/Manual/class-AudioReverbZone.html) component.

## Set Audio Source Property

Sets a property of the specified [AudioSource](http://docs.unity3d.com/Manual/class-AudioSource.html) component.

## Set Bounds Property

Sets the value of a property of the specified Bounds.

`1.2`

## Set Button Property

Modifies the value of a property of the specified [Button](http://docs.unity3d.com/Manual/script-Button.html) component.

## Set Camera Property

Sets a property of the specified [Camera](http://docs.unity3d.com/Manual/class-Camera.html).

## Set Canvas Group Property

Modifies the value of a property of the specified [CanvasGroup](http://docs.unity3d.com/Manual/class-CanvasGroup.html) component.

## Set Canvas Property

Modifies the value of a property of the specified [Canvas](http://docs.unity3d.com/Manual/UICanvas.html) component.

## Set Canvas Scaler Property

Modifies the value of a property of the specified Canvas Scaler component.

## Set Character Controller Property

Sets a property of the specified [CharacterController](http://docs.unity3d.com/Manual/class-CharacterController.html).

## Set Collider 2DProperty

Sets a property of the specified Collider2D component.

## Set Collider Property

Sets a property of the specified Collider component.

## Set Color

Sets the color of the specified object.

## Set Color Component

Sets a component of the specified color.

## Set Component Property

Sets the value of a property of the specified Component.

## Set Constant Force 2DProperty

Sets a property of the specified [ConstantForce2D](http://docs.unity3d.com/Manual/class-ConstantForce2D.html).

## Set Constant Force Property

Sets a property of the specified [ConstantForce](http://docs.unity3d.com/Manual/class-ConstantForce.html).

## Set Current State

Sets the specified [State](programs.md#state) as the current one in its [StateMachine](https://github.com/evasiongames/gameflow/tree/6faebaf2aabb6bd64785a4c90fd988e2e11be354/docs/reference/.md/README.md#state-machine).

## Set Distance

Moves a object so the distance to another object is the distance given.

## Set Dropdown Property

Modifies the value of a property of the specified [Dropdown](http://docs.unity3d.com/Manual/script-Dropdown.html) component.

## Set Force Property

Modifies the values of a property of the specified [Force](tools.md#force).

## Set GUIText Property

Modifies the value of a property of the specified GUIText component.

## Set GUITexture Property

Modifies the value of a property of the specified GUITexture component.

## Set GameObject Property

Modifies the values of a property of the specified [GameObject](http://docs.unity3d.com/Manual/class-GameObject.html).

## Set Image Property

Modifies the value of a property of the specified [Image](http://docs.unity3d.com/Manual/script-Image.html) component.

## Set Input Field Property

Modifies the value of a property of the specified [Input Field](http://docs.unity3d.com/Manual/script-InputField.html) component.

## Set Item In List

Sets the item at the given index in the specified [List](data.md#list).

## Set Joint 2DProperty

Sets a property of the specified Joint 2D component.

## Set Joint Property

Sets a property of the specified Joint component.

## Set Language

Sets the current language for localization purposes.

#### Properties:

* **Language:** SystemLanguage. The language to set as current.

## Set Lens Flare Property

Sets a property of the specified [LensFlare](http://docs.unity3d.com/Manual/class-LensFlare.html).

## Set Light Property

Sets a property of the specified [Light](http://docs.unity3d.com/Manual/class-Light.html).

## Set Line Renderer Property

Sets a property of the specified [LineRenderer](http://docs.unity3d.com/Manual/class-LineRenderer.html).

## Set Local Position

Sets the local position of the specified object.

`1.0`

## Set Local Position Component

Sets the value of a component of the local position of the specified Transform.

`1.0`

## Set Local Rotation

Sets the local rotation of the specified object.

`1.0`

## Set Local Rotation Component

Sets the value of a component of the local rotation of the specified Transform.

`1.0`

## Set Magnitude

Sets the magnitude of the specified length.

## Set Material

Sets the material of the specified object.

## Set Material Property

Sets a property of the specified Material.

## Set Mesh Filter Property

Sets a property of the specified [MeshFilter](http://docs.unity3d.com/Manual/class-MeshFilter.html).

## Set Mesh Renderer Property

Sets a property of the specified [MeshRenderer](http://docs.unity3d.com/Manual/class-MeshRenderer.html).

## Set Mouse Cursor

Changes the mouse cursor to the specified texture.

## Set Mouse Lock

Changes the mouse cursor lock mode.

`1.0`

## Set Nav Mesh Agent Destination

Sets the destination of the specified [NavMeshAgent](http://docs.unity3d.com/Manual/class-NavMeshAgent.html) component.

## Set Nav Mesh Agent Property

Sets a property of the specified [NavMeshAgent](http://docs.unity3d.com/Manual/class-NavMeshAgent.html).

## Set Nav Mesh Obstacle Property

Sets a property of the specified [NavMeshObstacle](http://docs.unity3d.com/Manual/class-NavMeshObstacle.html).

## Set Next State

Sets the next [State](programs.md#state) to jump after the current one finishes.

## Set Off Mesh Link Property

Sets a property of the specified [OffMeshLink](http://docs.unity3d.com/Manual/class-OffMeshLink.html).

## Set Orbit Rotation

Sets a relative rotation of the target [Transform](http://docs.unity3d.com/Manual/class-Transform.html) around the specified pivot.

## Set Outline Property

Sets a property of the specified [Outline](http://docs.unity3d.com/Manual/class-Outline.html).

## Set Parameter Indirection

Sets the value of indirection for the specified [Parameter](data.md#parameter).

`1.0`

## Set Parameter Value

Sets the value of the specified [Parameter](data.md#parameter).

## Set Parent

Assigns a new parent to the specified object.

## Set Particle System Property

Sets a property of the specified [ParticleSystem](http://docs.unity3d.com/Manual/class-ParticleSystem.html).

## Set Path Property

Sets a property of the specified [Path](tools.md#path) component.

## Set Physics Property

Sets a property of the global Physics Settings.

## Set Platform

Sets the runtime platform.

Sets the runtime platform that [Platform Condition](https://github.com/evasiongames/gameflow/tree/6faebaf2aabb6bd64785a4c90fd988e2e11be354/docs/reference/.md/README.md#platform-condition) will evaluate. Useful for testing purposes.

## Set Platform Effector 2DProperty

Sets a property of the specified [Platform](http://docs.unity3d.com/Manual/class-Platform.html).

## Set Platform Type

Sets the runtime platform type.

Sets the runtime platform type that [Platform Type Condition](https://github.com/evasiongames/gameflow/tree/6faebaf2aabb6bd64785a4c90fd988e2e11be354/docs/reference/.md/README.md#platform-type-condition.html) will evaluate. Useful for testing purposes.

## Set Point Effector 2DProperty

Sets a property of the specified [PointEffector2D](http://docs.unity3d.com/Manual/class-PointEffector2D.html).

## Set Position

Sets the 3D world position of the specified object.

## Set Position 2D

Sets the 2D world position of the specified object.

## Set Position Component

Sets the value of a component of the position of the specified Transform.

## Set Position From Screen Point

Sets the 3D world position of the specified object given its 2D screen position.

## Set Program Property

Sets a property of the specified Program.

## Set Projector Property

Sets a property of the specified [Projector](http://docs.unity3d.com/Manual/class-Projector.html).

## Set Quaternion Component

Sets the value of a component of the quaternion stored in the specified Variable.

## Set Random Local Position

Sets the local position of the specified target to a random [Vector3](http://docs.unity3d.com/ScriptReference/Vector3.html) value.

`1.0`

## Set Random Local Rotation

Sets the local rotation of the specified target to a random [Vector3](http://docs.unity3d.com/ScriptReference/Vector3.html) value.

`1.0`

## Set Random Position

Sets the position of the specified target to a random [Vector3](http://docs.unity3d.com/ScriptReference/Vector3.html) value.

## Set Random Rotation

Sets the rotation of the specified target to a random [Vector3](http://docs.unity3d.com/ScriptReference/Vector3.html) value.

## Set Random Scale

Sets the scale of the specified target to a random [Vector3](http://docs.unity3d.com/ScriptReference/Vector3.html) value.

## Set Random Seed

Sets the seed for the random number generator.

## Set Raw Image Property

Modifies the value of a property of the specified Raw Image component.

## Set Ray Property

Modifies the values of a property of the specified [Ray](tools.md#ray).

## Set Rect Property

Sets the value of a property of the Rect stored in the specified Variable.

## Set Rect Transform Property

Modifies the value of a property of the specified Rect Transform component.

## Set Render Property

Sets a property of the global Render Settings.

## Set Rigidbody 2DProperty

Sets a property of the specified [Rigidbody2D](http://docs.unity3d.com/Manual/class-Rigidbody2D.html) component.

## Set Rigidbody Property

Sets a property of the specified [Rigidbody](http://docs.unity3d.com/Manual/class-Rigidbody.html) component.

## Set Rotation

Sets the rotation of the specified object.

## Set Rotation 2D

Sets the 2D rotation of the specified object.

## Set Rotation Component

Sets the value of a component of the rotation of the specified Transform.

## Set SO Property

Sets the value of the specified ScriptableObject property using Reflection.

`1.0`

## Set Scale

Sets the scale of the specified object.

## Set Scale 2D

Sets the 2D scale of the specified object.

## Set Scale Component

Sets the value of a component of the scale of the specified Transform.

## Set Script Property

Sets the value of the specified script variable using Reflection.

## Set Scrollbar Property

Modifies the value of a property of the specified [Scrollbar](http://docs.unity3d.com/Manual/script-Scrollbar.html) component.

## Set Selectable Property

Sets a property of the specified [Selectable](http://docs.unity3d.com/Manual/class-Selectable.html) component.

## Set Shadow Property

Sets a property of the specified [Shadow](http://docs.unity3d.com/Manual/script-Shadow.html).

## Set Skinned Mesh Renderer Property

Sets a property of the specified [SkinnedMeshRenderer](http://docs.unity3d.com/Manual/class-SkinnedMeshRenderer.html).

## Set Skybox Property

Sets a property of the specified [Skybox](http://docs.unity3d.com/Manual/class-Skybox.html).

## Set Slider Property

Modifies the value of a property of the specified [Slider](http://docs.unity3d.com/Manual/script-Slider.html) component.

## Set Sprite Renderer Property

Sets a property of the specified [SpriteRenderer](http://docs.unity3d.com/Manual/class-SpriteRenderer.html).

## Set Substring

Sets a part of the string stored in the specified [Variable](data.md#variable).

## Set Surface Effector 2DProperty

Sets a property of the specified [SurfaceEffector2D](http://docs.unity3d.com/Manual/class-SurfaceEffector2D.html).

## Set Terrain Property

Sets a property of the specified Terrain component.

`1.2`

## Set Text Mesh Property

Sets a property of the specified [TextMesh](http://docs.unity3d.com/Manual/class-TextMesh.html).

## Set Text Property

Modifies the value of a property of the specified [Text](http://docs.unity3d.com/Manual/script-Text.html) component.

## Set Texture Property

Sets a property of the specified Texture.

## Set Time Property

Sets a general time-related property.

## Set Time Scale

Sets the time scale for de/acceleration effects during the game.

## Set Timer Property

Modifies the values of a property of the specified [Timer](tools.md#timer).

## Set Toggle Property

Modifies the value of a property of the specified [Toggle](http://docs.unity3d.com/Manual/script-Toggle.html) component.

## Set Trail Renderer Property

Sets a property of the specified [TrailRenderer](http://docs.unity3d.com/Manual/class-TrailRenderer.html).

## Set Transform Property

Sets a property of the specified [Transform](http://docs.unity3d.com/Manual/class-Transform.html) component.

## Set Variable Indirection

Sets the value of indirection for the specified [Variable](data.md#variable).

`1.0`

## Set Variable Value

Sets the value of the specified [Variable](data.md#variable).

## Set Vector Component

Sets the value of a component of the vector stored in the specified [Variable](data.md#variable).

## Set Velocity

Sets the velocity of the specified object.

## Set Velocity 2D

Sets the velocity of the specified 2D object.

## Set Velocity Component

Sets the value of a component of the velocity of the specified Rigidbody.

## Set Velocity Component 2D

Sets the value of a component of the velocity of the specified Rigidbody2D.

## Set VideoPlayer Property

Sets a property of the specified VideoPlayer component.

`1.0`

## Set W

Sets the W value of the data structure stored in the specified Variable.

## Set Wind Zone Property

Sets a property of the specified [WindZone](http://docs.unity3d.com/Manual/class-WindZone.html).

## Set World Up

Specifies the upward direction to use in actions like [Look At](actions.md#look-at).

`1.0`

## Set X

Sets the X value of the data structure stored in the specified Variable.

## Set Y

Sets the Y value of the data structure stored in the specified Variable.

## Set Z

Sets the Z value of the data structure stored in the specified Variable.

## Setup Progress

Initializes the progress indicator.

## Show In Window

Shows the GameFlow behaviour in a window.

`1.0`

## Show Mouse Cursor

Shows the mouse cursor.

## Show Parameter

Shows the specified [Parameter](data.md#parameter).

## Shuffle List

Randomly shuffles the specified [List](data.md#list).

`1.2`

## Sleep

Puts to sleep the specified object.

## Sleep 2D

Puts to sleep the specified 2D object.

## Sleep List

Puts to sleep all objects \(2D or 3D\) in the specified [List](data.md#list).

## Sort List

Sorts the items in the specified [List](data.md#list).

## Start Game

Notifies the start of the game.

## Start Program

Restarts the specified Program.

## Stop Animation

Stops the playback of the specified animation \([Animation](http://docs.unity3d.com/Manual/class-Animation.html) or [Animator](http://docs.unity3d.com/Manual/class-Animator.html)\).

`1.0`

## Stop Music

Stops the music with optional volume fading.

## Stop Sound At Source

Stops the playback of the sound at the specified [AudioSource](http://docs.unity3d.com/Manual/class-AudioSource.html).

## Stop Timer

Stops the specified [Timer](tools.md#timer).

## Swap Values

Swaps the values of the specified Variables.

`1.2`

## Toggle Audio Mute

Toggles audio mute on/off.

## Toggle Component Enablement

Toggles the enablement state of the specified component.

## Toggle GameObject Activation

Toggles the activation state of the specified [GameObject](http://docs.unity3d.com/Manual/class-GameObject.html).

## Toggle Parameter Value

Toggles the boolean-value of the specified [Parameter](data.md#parameter).

## Toggle Pause

Resumes the game if it was paused, otherwise pauses the game.

## Toggle Variable Value

Toggles the boolean-value of the specified [Variable](data.md#variable).

## Trigger Custom Event

Triggers a custom event with specified kind and information.

Related: [On Custom Event](https://github.com/evasiongames/gameflow/tree/6faebaf2aabb6bd64785a4c90fd988e2e11be354/docs/reference/.md/README.md#on-custom-event)

`1.0`

## Unload Scene

Unloads the scene with the specified name or index.

`1.2`

## Update Progress

Updates the current progress.

## Wait

Waits for the specified time interval.

## Wait For Program

Waits for the specified Program to finish.

#### Properties:

* **Program:** The Program to wait for.

## Wait For Timer

Waits the specified [Timer](tools.md#timer) for expiration.

## Wake Up

Wakes up the specified [Rigidbody](http://docs.unity3d.com/Manual/class-Rigidbody.html) component.

## Wake Up 2D

Wakes up the specified [Rigidbody2D](http://docs.unity3d.com/Manual/class-Rigidbody2D.html) component.

## Wake Up List

Wakes up all objects \(2D or 3D\) in the specified [List](data.md#list).

## While

Executes the contained actions repeately while the conditions are met.

