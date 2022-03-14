# Changelog

## GameFlow v1.2.5 - Nov 2019

* Fully adapted to the new theme introduced in Unity 2019.3 (tested with beta 8).
* Improved support for Retina / HDPI displays.
* Added a smooth option to the Follow action.
* Fixed: Unable to add / remove blocks to GameObject with missing prefab.
* Fixed: Timer type 'Chrono' clamps Time to Duration.
* Fixed: Block 'Enable' toggle does not change with left mouse click.
* Fixed: Draw blocks background option in Preferences not working.
* Fixed: Invalid Format warning in Set Text Property action.
* Removed: FPS Counter gamefab.
* Known issues: keyboard support (F2, Return, Delete) has been disabled (2019.3+ only).

## GameFlow v1.2.3 - Oct 2019

* Preliminary support for Unity 2019.3b (tested with beta 5).
* New setup process to prevent problems when upgrading Unity.
* Supported versions are: 2018.4.x, 2019.1.x, 2019.2.x and 2019.3.x.
* Minimum supported Unity version is now 2018.4 LTS.
* Fixed: Errors after adding a During action to a Group action.
* Fixed: Error on Interpolate Value if no Variable is specified.
* Fixed: Casting error in Get Component / Script / SO Property actions.
* Fixed: Obsolete properties in Get / Set Terrain Property actions.
* Removed FPS Counter gamefab.
* Updated Readme file.

## GameFlow v1.2.2 - Jun 2019

* Ready for Unity 2018.4 LTS.
* Preliminary support for Unity 2019.2b.
* Fixed: Property field Broken in Set Script Property Action.

## GameFlow v1.2.1 - May 2019

* Price restored to $20 for good.
* Improved: Version check and troubleshooting.
* Fixed: Issues related to Program initialization order.
* Fixed: Example scenes marked as modified after no changes.
* Fixed: Object identifiers for local components on multiple inspectors.
* Fixed: Actions following a Pause Game should not execute until Resume Game.
* Fixed: Variable expansion fails in some cases.
* Fixed: Minor bug in Snake example game.

## GameFlow v1.2 - April 2019

* Ready for 2019.1 and .Net 4.x scripting runtime.
* Important: Minimum required Unity version is now 2018.3.
* New: Added support for raycasting in the 2D space.
* New: Find Program action.
* New: Shuffle List action.
* New: Draw Line action.
* New: Draw Collider 2D action.
* New: Set / Get Terrain Property actions.
* New: Set / Get Bounds Property actions.
* New: Get Closest Point action.
* New: Collider 2D condition.
* New: Swap Values action.
* New: On Scene Load event program.
* New: Unload Scene action.
* New: Get Scene Count action.
* New: Ignore / Restore Collision 2D actions.
* New: Enable / Disable Collider 2D actions.
* New: Get Random Point In Collider 2D action.
* New: Added Modulo operation added to Evaluate Math Function action.
* New: Option in preferences to show/hide suffixes in block titles.
* New: Added validation for Collider and Collider 2D related actions.
* New: Added "Emitting" to Set / Get TrailerRenderer Property action.
* Updated: GameFlow settings adapted to new (2018.3+) Preferences dockable window.
* Updated: Example 12 (Watch) no longer using legacy GUI Text components.
* Changed: Origin and Direction now displayed as fields in Ray blocks.
* Improved: Expansion of Variables now supporting global search and GameObject specification.
* Improved: Set / Get Collider Property now supporting TerrainColliders.
* Improved: Drawing of SphereCollider in Draw Collider action.
* Improved: Minor visual improvements in object selector window.
* Improved: Draw Bounds and Draw Bounds Frame actions supporting Collider2D.
* Improved: Better validation for Set / Get Component / Script Property actions.
* Improved: Get Scene Property action.
* Improved: Added limitation to relative angles in the Rotate action interface.
* Fixed: Macros > Last Macro menu option not working in some cases.
* Fixed: Indirect Type field in Variables broken in some cases.
* Fixed: (API) Blocks.FindBlock<T>() not working for Scene scope in some cases.
* Fixed: WebRequest related actions for 2018.3.
* Fixed: Wrong icon for the GameFlow component in 2018.3.
* Fixed: UnityEngine.Networking types not showing in Type selector window.
* Fixed: Grouped actions causing NullReferenceException.
* Fixed: Property field not showing in Invoke Method action.
* Fixed: Property field not showing in Get / Set Script Property actions.
* Fixed: Property field not showing in Get / Set SO Property actions.
* Fixed: Event controllers not added to inactive GameObjects on start.
* Fixed: Warning / Glitches in Localization block interface.
* Fixed: Hierarchy window decorators in low resolution on HDPI displays.
* Fixed: Added missing properties to Get Joint2D Property (Wheel Joint 2D) action.
* Fixed: "Divide by zero" validation in Divide Variable Value when divisor is a Variable.
* Fixed: Controlled two potential errors in Clone and Instantiate actions.
* Removed: limitation of 3 levels of nesting for blocks. No more KISS warnings.
* Removed: "Execute this program during Pause" option no longer available via context menu.
* Removed: Documentation in Spanish is no longer available.
* Removed: Legacy GUI actions (Set / Get GUI Text/Texture Property) are now obsolete.
* Removed: Fade In / Out and Set / Get / Interpolate Color actions no longer supporting GUI legacy.
* Removed: "Linear Velocity Blending" no longer supported in Set / Get Animator Property actions.

## GameFlow v1.1.2 - October 2018

* Fixed: crashes in 2018.3b when adding programs or states to the GameFlow component.
* Fixed: Utility window closing when selecting another GameObject in 2018.3b.
* Initial adaptation to 2018.3b new prefab system with a known issue: Hidden GameFlow blocks are displayed as "Removed" in prefab instances due to a bug in the beta.
* Fixed: Invoke Method action not working on builds.
* Fixed: error when changing Method in a duplicate of an Invoke Method action.
* Incompatibility with Presets is now informed to user and managed.
* Fixed: Error adding a new State having another block focused.
* Fixed: spurious warnings related to 'm_EnabledProperty' in 2018.3b.
* Fixed: Set / Get Component Property actions not working when Component is specified via Variable.
* Fixed: Issues with Index variable in For action.
* Fixed: Glitch in time bars when using very small duration values.
* Fixed: Messed validation of the Listening target object in event programs.
* Fixed: Interpolate not working on first execution of On Activate.
* Fixed: Music loop stops after playing a sound FX.
* New: Get / Set Dropdown Property actions.
* Fixed: Dropdown not recognised as UI component by On Value Change.
* Additional control to prevent possible parameter index out of bounds errors in Set Animator Parameter.
* API: added static properties to Builtin class for all new variables introduced in v1.1.
* Minor visuals: popup labels made more noticeable, small fonts no longer using bold style, changed entry point icons.
* Connective (And/Or) style changed in conditions for clarity.
* Minor visual fixes in Invoke Method action user interface.
* Minor visual fixes in Set X, Set Y, Set Z and Set W actions user interface.
* This is the last version of GameFlow supporting Unity 5.6 and the rest of pre 2017.4 versions. Starting in v1.2 only Unity 2017.4 and 2018.x versions will be supported.

## GameFlow v1.1 - September 2018

* This is the last version of GameFlow supporting Unity 5.6 and the rest of pre 2017.4 versions. Starting in v1.2 only Unity 2017.4 and 2018.x versions will be supported.
* All the minor issues with Unity 2018.2 have been fixed.
* New: Decorators in Hierarchy window.
* New: Get Scale action.
* New: Set / Get Velocity Component + 2D versions.
* New: Set X / Y / Z / W + Get W.
* New: Set / Get Position, Rotation and Scale actions for 2D.
* New: Set / Get Rect Property and Set / Get Quaternion Component actions.
* New: Get Component In Parent / In Children actions.
* New: Get Components action.
* New: Look At 2D action.
* New: built-in variables: Mouse Axis, Mouse Axis X, Mouse Axis Y, Mouse Wheel.
* Optimization of block painting in Inspector window.
* Added: Validation to prevent crash when the self GameObject is specified as Pool model.
* Fixed: Program re-execution in Edit mode broken after assembly reload.
* Fixed: 'Clear Console' action not working in Unity 2017.1+
* Fixed: 'Get Magnitude' condition. 'Of Vector3' and 'Of Vector4' options showing wrong field.
* Enhancement: Key condition. Allow using a key code directly.
* Enhancement: Concatenate Strings action. Add option to add literal values.
* Fixed: Create Web Request action. Wrong validation warning.
* Get X / Y / Z now supporting Quaternion type variables.
* Set / Get GUIText / GUITexture Property actions are now deprecated.
* Fixed: Set / Get Animator Parameter. Warning and parameter list not getting updated.
* Fixed: Programs in Prefabs can't be executed using Execute() / Step() API methods.
* Fixed: Shift + Tab not selecting previous tab in object selector window.
* Fixed: Search filter not applied when changing active tab with the Tab key in object selector window.
* Fixed: Program Parameters not shown in the GameObject/Prefab tab of the object selector window.
* Fixed: No need to show the name of the GameObject before each object in the GameObject/Prefab tab of the object selector window.
* Inner button in 'Scene Name' field of the 'Load Scene' action is now visually coherent with the other inner buttons.
* Fixed: Undesired opening of the Block type selection window after Return key.
* Fixed: Asset tab showing Variables twice in the object selector window.
* Fixed: The Prefab tab should not be available in the object selector window for GameObject selection neither on Prefabs or Prefab instances.
* Enhancement: Show full paths for GameObjects instead of only names in the object selector window.
* Object selector now showing Variable/Parameter/List types on the right side.
* Fixed: crash in On Value Change / On End Edit programs in Edit mode if target GameObject in set to None.
* Fixed: Variant Parameters showing an incorrect type in Edit mode.
* Fixed: error due to bad conversion when an Enum Variable is specified as Type for a Timer.
* Fixed: Newly added blocks misplaced when using multiple Inspector windows.
* Removed serialized property 'editorId' which could produce unwanted changes in prefab .meta files.
* Fixed: Actions accepting read-only variables in Output fields.
* Styling of time bars in Timer and time-based actions.
* Added missing time bar to Interpolate Value and Look At actions.
* Changed: Random Wait action now outputs the duration of the action at the start of the wait not at the end.
* Fixed: Spurious 'KISS' warning.
* Fixed: Error after drag and drop of blocks between two Inspectors.
* Get Vector Component now supporting Vector4 type and W component.
* Fixed: Set Vector Component always setting the type of the specified target variable to Vector3.
* Removed the (now superfluous) list type validation in Get Selection and Find GameObjects actions.
* Fixed: the type selector for Add Component and Get Component actions only allows for Component types now.
* Changed: Actions with output to a List will always set the type of the specified List upon executing.
* Fixed: Look At action with Target Direction option: Direction not updated when a duration is specified.

## GameFlow v1.0.1 - May 2018

* Fixed: Send Command action. Command Id property not modifiable.
* Fixed: Start Program action. Program property missing.
* Fixed: Wrong auto start of event programs after enablement.
* Fixed: Toggle Component Enablement action. Not working with for GF blocks.
* Fixed: Disable / Enable Behaviour actions. Should alter enablement toggle when Target is a GF block.
* Fixed: On Awake program. Execution stuck when program is enabled at runtime.
* Fixed: On Awake program. Re-executed when an On Activate / Deactivate program is present.
* Fixed: 'For' action. Missing label for 'Variable' property.
* Fixed: Drop not working when dragging an unfolded program parameter.
* Fixed: Group action. Only contained time-actions are executed.
* Fixed: Lagging drag and drop of GF blocks.
* Fixed: 'Program' type not listed in object type selector window.
* Fixed: Program Context menu 'Change type' option not working for folded programs
* Fixed: 'Get Object From Pool' action. Wrong auto activation of the returned object.
* Fixed: Not easy way to detect a double click -> new On Double Click program.
* Fixed: Program context > Reset option removes destroys program parameters
* Fixed: Upgrading to v1.0 fails in the current scene after import
* Fixed: Upgrading to v1.0 not applied to Prefabs after import
* Fixed: Get Sprite Renderer Property action. Missing properties.

## GameFlow v1.0 - April 2018

### General

* Fully compatible with Unity 5.6, 2017.1, 2017.2, 2017.3. 2017.4 LTS and 2018.1b
* Unity 5.6 is now the minimum supported Unity version.
* Massive code overhaul. Almost every piece of code has been examined and refactorized to remove as much technical debt as possible.
* The GameFlow API for extensibility and communication with other scripts is now disclosed. Please refer to the documentation for more information.
* GameFlow is now the one and only component you will need to add to your GameObject. The rest of GameFlow blocks are now conveniently contained inside this main component. Previous 'legacy' containers (Variables, Localizations, Keys, Rays, Forces, etc.) will be automatically removed during the upgrade process.
* You can now program your own utilities for the Unity Editor with GameFlow.
* Separate packages are now available for Unity 5.6 and 2017.x versions so we can avoid using the API Upgrader on import. Please make sure to always re-download and re-import GameFlow from the Asset Store after upgrading your project so you install the correct version.

### Build

- Windows Store is now a supported build target even supporting Reflection actions like Invoke Method or Set/Get Component Property. Remember this build target is available only in Windows.

### Programs

- You can now have multiple programs of the same type in the GameObject.
- Macros are now easier to set up. Just select the key shortcut you want to associate to your Macro program. That's all.
- Each program now showing its type (On Start, On Update, etc.) on the right side of the title. You have now a context menu option to change the program type.
- New On Custom Event program. Use it with the new Trigger Custom Event action.
- On Update, On Fixed Update and On Late Update programs now supporting an option (in settings) allowing these programs to work during game pause if required (example: making a 'toggle pause on key press' controller).
- Program execution layer has been completely re-written to make it lighter, faster, allow for more control of loops (see new Loop In Current / Next Frame actions) and prepare it for the integration of a future debugger.
- Fixed On Variable Change programs not getting events when the value of the listened Variable was modified manually in the Inspector.
- On Parameter Change program has been modified to make it similar to the On Variable Change program. The 'Changed Parameter' program parameter is no longer used and you need to specify which Parameter the program will be listening to.
- Forced initialization/loading of actions executed in a On Awake type program to prevent errors due to an unexpected initialization order.
- Fixed loops (While, For Each, etc.) not executing correctly in On Awake type programs.
- On Draw Gizmos type programs are now executed also in Edit mode.
- Fixed On Update, On Fixed Update and On Late Update programs not executing loop-type actions (For, While, etc.) in the current frame.
- When executing programs or macros in Edit mode, termination messages in the Console will show the name of the executed program.
- New menu option (Tools > GameFlow > Macros > Last Macro) to re-execute the last executed macro or program.

### State Machines

- Multiple State Machines in the same GameObject are now supported.
- State Machines no longer require specifying a State as 'Start'. For the sake of simplicity, now the first State in the states list is always considered the Start. A small arrow icon (decorator) is now drawn on the side of the initial state block to indicate this.
- Fixed initially disabled State Machines not having a current state until enabled.

### Tools

- Commands now supporting displaying a button in Gamefab/Window mode to directly execute the Program or Macro associated with the Command.
- Commands can now be enabled or disabled. A disabled command won't execute the associated program.
- Pools now putting their released objects to sleep so they can be reused with no previous Physics applied.
- Fixed elapsed time in 'Chrono' type Timers limited to the latest value in the Duration value.
- Timer properties no longer editable during play mode.
- Description is now a block and can be added and edited like any other top block, so context menu 'Toggle Description' option is no longer required.
- You can now have more than one Timer, more than one Path, more than one Description and more than one Pool per GameObject.
- New Separator block that you can use for adding spaces between blocks in the Inspector.
- Lists can now be displayed in Gamefab/Window mode with or without a custom title.
- Hidden property for Parameters no longer used. There is now a Display option to control how parameters will be displayed in Gamefab mode.
- Added Display option to the Show Parameter action.
- New built-in variable Frame to get the current frame number since the start of the execution.

### Editor

* New Toggle Settings context menu for the GameFlow component exposing a new Display Mode property supporting the following modes: Blocks (default mode), Gamefab (formerly known as Editor mode), Utility Window and Tabbed Window mode.
* You can now show a GameFlow prefab in window mode by double clicking it in the Project view. Take a look at the GameFlow/Utils folder for some examples.
* Optimized block drawing in the Inspector window. Scrolling with the mouse wheel through long programs should be noticeable faster and smoother now.
* The 'Id' fields have been removed from all blocks. You can now rename the selected block using the F2 key or the Rename context option.
* You can now use the F2 key to rename an object or Variable on the currently focused field. A modal dialog will be shown to enter the new name.
* Replaced context menus for Collapse All and Expand All options with two separate icons for faster operating.
* Adding, removing or moving blocks is now disallowed on prefab instances to prevent conflicts. You will need to do these operations on the prefab. This is only for block operations, you can still modify properties in the prefab instances as usual.
* New block decorators for Program, Macro, State Machine, State and Action blocks. Decorators are tiny icons appearing in the left side of blocks to indicate whether they are execution entry points (play icon), executing (green play icon) or already executed (yellow tick icon).
* Changed Inspector / Scene icon.
* Fixed block colors appearing noticeably darker in the Inspector when the chosen Color Space (see Project Settings > Players > Other Settings) is Linear. Many thanks to Thomas Pasieka for finding how to reproduce this historical issue.
* Minor visual adjustment for value fields of type Shader (Set Material Property, Create Material).
* Fixed drawing of cursor insertion line in Retina displays.
* Indirect Variables/Parameters now showing additional fields below the Indirect toggle when no Value is supplied, so you can indicate the expected type for the variable indirection. This way, all the actions which can modify the value of an indirect variable or parameter (like Set Variable Value) will be able to show a proper Value field.
* Component-type controls no longer accepting drag and drop of Actions and Conditions.
* For easier modification, text in search field on Action/Condition selector window is now re-selected after adding.
* Fixed text filter in blocks selector window not selecting the first visible item in the resulting filtered list in some cases.
* GameFlow is now the only component available in the Add Component and Gizmos menus.
* Fixed incorrect drawing of conditions after undoing a condition deletion.
* Fixed issue whereby the inspected GameObject was marked as modified just by clicking in the Add Action area.
* Fixed inner + field buttons not creating new objects in some cases.
* Fixed insertion cursor line not showing in some cases.
* Fixed Comment action not collapsing / expanding when clicking in its title.
* Fixed issue whereby a collapsed condition would involuntarily expand after changing its connective (And, Or).
* Fixed a bunch of field labels (Draw Force, Flip, Play Sound At Source).
* Added title labels to Repeat and Repeat Until actions.
* Fixed references to event parameters staying alive after copying/moving actions to a different program or state. Now all references are automatically removed to avoid undesired results.
* Object selector window no longer showing internal GameFlow components.
* Fixed an issue whereby blocks (any type) were not properly copied when using context menu options Copy Component and Paste Component as New.
* Replaced "Else" toggle in If action. You have now a subtle icon on the right of the Then Actions title to toggle the Else Actions section.
* Toggle Description context menu option now available for Lists.
* Shorten texts in context menu options.
* Block backgrounds no longer looking blurry in Retina displays.
* Foldout arrows now using Retina textures when available.
* Parameters now supporting descriptions. In Editor mode, descriptions will be shown as tooltips for the parameters labels.
* Insertion cursor line will remain displayed if the Inspector loses the focus.
* Rewording (for clearness) and submenu for shader "named" properties in Set / Get Material Property actions.
* Rays are now drawn with z-buffer in Scene view. This way is easier to see whether they are colliding with objects.
* Removed < > symbols in block titles. This < > notation is still used in fields to indicate whether an object reference is a GameFlow block.
* Block titles now showing a right-aligned suffix text when collapsed. This suffix will be useful information like the type of a Variable or the current key code assigned to a Key.
* Actions section header now presenting its own context menu when the Parameters section is visible in event programs.
* Improved Type field to be more compact in Variables, Localizations, Parameters and Lists.
* Added context menu to States allowing collapse/expand of all contained actions.
* Fixed focus color for block titles too dark in Pro skin.
* Added Toggle Settings and Toggle Parameters option to Program context menu just in case you need to unclutter the Inspector.
* Context menu for any block now available with right click on the block title.
* Re-styling of + buttons for a clearer and more coherent interface on the Inspector.
* Changed interface an behaviour o persistent variables to make it more intuitive. Now changes made during Editor mode are also persistant.
* Added shortcut (Cmd + Alt + G on Mac, Ctrl + Alt + G on Windows) for quickly adding GameFlow and any of its main blocks to the inspected GameObject.
* Added new "Toggle Link" option to Note blocks to show/hide a field that you can use as a simple way to link the note with a GameObject.
* Fixed issue whereby it was possible to drag and drop program parameters outside the program they belong.
* Disabled drag and drop of GameFlow components and block into another GameObjects for coherence with Unity.
* Fixed blocks falling into an invalid state after Undo + Redo.
* Full re-styling of the block selector windows to make them more standard (except for the bold font). It is now easier to see what is the selected item and the + buttons on the right of items have been removed for clearness, but you can still double click to get blocks added to the Inspector.
* Block selector windows now supporting Home, End, Page Up and Page Down keys.
* Blocks are now grouped in sections in the selector window for clearness with a "Frequently used" program section at the top.
* Styling of inner field buttons for textfields (= button) and object fields (+ button).
* Fixed some drag and drop related issues.
* Fixed random ocasional crashes after double clicking an item in the object selector window.
* The Collapse / Expand All icons now working also during Play mode.
* Fixed glitch when selecting Scene as listening range in event programs.
* Fixed Undo not working after selecting an object reference using double click in the object selection window.
* Fixed misplacement of block cursor after hiding/showing the parameters of a program.
* For convenience, when using the + button in output fields of object type = Variable, the created variable will be automatically declared Indirect.
* Fixed Indirect variables wrongly staying Indirect after changing its type.
* Action/Condition selector windows now remembering the last selected item and the last scroll position.
* Minor visual change to display action Output type as a separated right-aligned label.
* Double click on an empty GameFlow component will open the Add Block window.
* Double click on the row bottom of a sequence of a sequence will open the corresponding Add Block / Action / Condition window.
* Context menu option "Cut" removed for all blocks. This change was required due to limitations in the new block Copy/Paste strategy.
* Newly created blocks no longer adding a generated 4-digit suffix to their identifiers. In the case of Programs, the Program type will be used as identifier instead of "ProgramXXXX".

### Actions

* We have now more than 450 actions available.
* New generic Set Component Property action and new generic version of the Get Component Property. These generic actions use Reflection, which is great for some things but not for performance. So, whenever possible (and specially in On Update programs) use the Set / Get actions for concrete Component types.
* New Set / Get Animator Property actions.
* New Set / Get Animation Property actions.
* New Set / Get Animator Parameter actions allowing easy access to Mecanim animation parameters.
* New Ignore / Restore Collision actions. Disables / Enables detection of collisions between colliders or layers.
* New Get Instance Id action.
* New Get Input Button State action.
* New Get X / Y / Z actions.
* New Get GameObject action.
* New Trigger Custom Event action. Use it with the new On Custom Event program.
* New Find GameObject / Find GameObjects actions.
* New Set / Get VideoPlayer Property and Control VideoPlayer actions.
* New Control Particles action. Use it to control your Particle Systems easily.
* New Show In Window action to show the GameFlow behaviour the action belongs to in its own window with the Editor mode automatically enabled. The window will be configured (type, title, size) as specified by the GameFlow settings.
* The "Instance ID" property is no longer available in the Get Component Property action, use the Get Instance ID action istead.
* Fixed misplacement of some properties in Set Particle System Property action.
* Added properties Flip X and Flip Y to Set Sprite Renderer Property action.
* New Set Variable / Parameter Indirection actions allowing the creation of indirect variables on demand.
* Improved Add Hierarchy To List action: 1) Added "Exclude Root" option, 2) You can now specify None as "Hierarchy Root" to add all the top-level objects in the Hierarchy.
* Fixed position actions (Set Position, Set Random Position, Set Position Component) using always World space regardless of the Space chosen.
* Space field now showing options World and Self (instead of Local) for coherence with Unity API documentation.
* Get Radial Offset action now supporting Space specification.
* Set Orbit Rotation action renamed as Set Orbital Rotation and now supporting Space specification for the rotation Axis.
* Reordering of fields in Transform-related actions for consistency.
* Fixed Move and Move Randomly actions using always World space regardless of the Space chosen.
* Added Min and Max Distance properties to Attract and Attract2D actions to configure the area of attraction.
* Added plus button to Variable field in For action to create an assign an Integer Variable with one click.
* Target type in Move Randomly changed to Transform for coherence with the Move action.
* Improved precision of initial and end values in internal timer objects. All time actions (specially Interpolate actions) would benefit from this.
* Fixed time actions not executing their initial step thus causing a delayed start.
* Fixed some properties not showing a Value field in Set Camera Property action. Fix applies for the following properties: Culling Mask, Depth Texture Mode, Event Mask, Rendering Path, Target Texture and Transparency Sort Mode.
* Added additional Space option to Clone action for better positioning of clones.
* Fixed wrong positioning of clones created using the Clone action when the original GameObject was a prefab instance.
* Minor rewording in the editor interfaces of Clone and Instantiate actions.
* Fixed error on Console after executing the Invoke Method action when one of the method parameters was a Variable containing a null (None) value.
* Fixed issue preventing the execution of Invoke Method actions in Editor after an assembly reloading.
* Fixed property "MipMap Bias" not working in Set Texture Property action.
* Fixed wrong label in Stop Sound At Source action.
* New Change String Case action (Uppercase, Lowercase).
* Fixed issue preventing change of value for Color variables/parameters/properties. It affected the following actions: Set Variable Value, Set Parameter Value, Set Script Property and Set Component Property.
* New Bounds Condition action.
* Draw Bounds action now supporting Bounds type.
* Added section titles (Actions, Conditions) to all container actions (If, While, For, ...).
* Fixed errors in Set Joint 2D Property action when used to set the value of properties 'Motor Max Torque' and 'Motor Speed' of a Wheel Joint 2D component.
* Fixed cache mechanism for Invoke Method action not working reliabily in Editor.
* Improved return type management and error logging in Invoke Method action.
* New Add Torque / Add Torque 2D actions.
* Improved Load Scene action: now supporting scene name specification and featuring a nice scene selection window for human beings. Scene index specification is still available.
* New Get Nearest / Get Farthest actions.
* Added support for public property members to Set / Get Script Property actions. Previously only field members were supported.
* New Set / Get SO Property actions allowing easy interfacing with ScriptableObjects.
* Get Distance action now supporting "From Point" and "To Point" for references. Previously only Transforms were supported.
* Set / Get Collider Property now supporting Wheel Colliders.
* Fixed Min. Rotation value wrongly clamped to (0,0,0) in Set Random Rotation action. Minor rewording of labels.
* Fixed wrong positioning of clones when using Self space in Clone action.
* Clone action now supporting relative positioning in World space. Rewording of labels.
* Clone action no longer adding "(Clone)" suffix to the name of the created clone object when executed in Editor mode.
* Added Space and Relative fields to Instantiate action. Minor rewording of labels.
* Fixed issue in Draw Bounds and Draw Bounds Frame actions whereby the target Transform was always set to the same GameObject.
* Added a new 'Use Raycasting' option to Get World Point From Screen Point that you can disable to allow usage in 2D scenes.
* New Reset Variable Value action.
* Fixed type casting error for properties pixelWidth and pixelHeight in Get Camera Property action.
* Added new Custom easing option (+ additional Animation Curve field) to those actions already supporting easing: Interpolate, Move, Rotate, Look At, etc.
* Fixed a too strict validation in the Insert Item List action preventing insertion when index was < 0 or index was >= number of items in target list.
* New 'Add To String' action supporting special characters like newline or tab.
* Fixed numeric Set Parameter Value action not showing the value field when the specified target parameter is type Animation Curve.
* Set Distance now supporting Vector3 variables for Of and From fields.
* Improved Fade In / Out actions with an additional Initial Delay field.
* The Set Rotation, Set Rotation Component and Set Random Rotation actions will enable the Space field only when the Relative toggle is on.
* New Clamp Position action.
* New 'Local' (that is, working with local instead of world coordinates) version of the following actions: Clamp Position, Set Position, Set Position Component, Set Random Position, Clamp Rotation, Set Rotation, Set Rotation Component, Set Random Rotation.
* Fixed broken validation of the 'Random Wait' action which allowed its use with a duration inside of Update type programs.
* Added 'Direction' option to the 'Look At' action.
* The 'Loop' action is no longer executable in the editor to prevent undesired infinite loops.
* Fixed 'During' action not correctly skipped when executed in the Editor, thus causing infinite loops.
* Fixed 'For' action not working as expected when Start and End have the same value.
* New 'Loop In Current Frame' and 'Loop In Next Frame' actions to control whether looping actions (like 'While' or 'For') will wait for the next frame before executing the next iteration or not.
* Removed 'Enable Program' option in 'Restart Program' action. The specified program will be always made activated upon restarting it.
* Remove 'Restart' option in 'Execute Program' action. The specified program will be always made activated and restarted upon executing it.
* 'Wait' option in 'Execute Program' action will be available only when the specified program is not an Update type program and not the same calling program.
* New Enable / Disable Timer actions.
* New Enable / Disable State Machine actions.
* New Set Mouse Lock action. 
* During, Wait and the rest of time-based actions now showing a slider that will activate in play mode to indicate the elapsed time.
* Added 'Time Since Startup' option to Set Random Seed action.
* Fixed Get Item From List action getting null output when used with a List of type Variable.
* New Get Selection action.
* Fixed type conversion error in 'Target Graphic' property in the Set InputField Property and Set Toggle Property actions.
* Fixed error in the calculation of duration in the Look At action when using 'Velocity' mode.
* New Set World Up action. You can use it for advanced uses of the Look At action.
* Added warning message to time-based actions used in the context of an Update type program.
* The Duration fields are now modifiable during play-mode (only in actions not currently executing).
* Rotation related actions now making use of the Space field only when the Relative toggle is checked. Space defaults to World otherwise.
* New Display Dialog action.
* New Stop Animation action.
* New Get Selected GameObject action.
* Fixed some errors related to use of actions in states.
* Break action now correctly breaking the loop or program flow when executed in a On State action.
* Additional option in Set Scale action supporting the specification of a single value for all axis.

### Conditions

* We have now 30 conditions available.
* Variable Value Condition adapted to work with the new indirect variable type specification.
* New Item Count condition replacing the now obsolete List Count condition.
* New Input Button condition.
* New Program condition to test whether a program is executing, finished, etc.
* New State Machine condition.
* New Magnitude condition for using with vectors and forces.
* New Velocity condition for using with Animator, Camera, CharacterController, NavMesh Agent/Obstacle and Rigidbody[2D].
* Fixed Current State condition appearing as 'State' and misplaced in the condition selector window. The action interface is slightly changed to make it coherent with the fixed title.
* Added property labels to some conditions like Key Condition or List Condition for visual coherence.
* Changed titles of some conditions for coherence: Animator State (prev. was State), Variable Value (prev. was Value), Parameter Value (prev. was Value).
* Distance condition now supporting 'From Point' and 'To Point' for references. Previously only Transforms were supported.
* Key Condition now showing the evaluated comparison (Is Down, Is Up, etc.) in the block title.

### Prefabs

- The Prefabs folder is now organized in two subfolders: Gamefabs and Utilities.
- The Utilities subfolder contains ready-to-use Editor utilities programmed with GameFlow. Just double click the desired Utility prefab to show it in a floating window.
- All prefabs have been revised to 

### Documentation

* Added User Guide, Release Notes and About options under Tools > GameFlow menu.
* Documentation files are no longer included in the package but hosted online on a dedicated site. This will allow for an easier maintenance and more frequent updates.
* Context reference help options now opening the online version of the reference.
* Added Readme files to some subfolders with additional information on structure and caveats.
* Added alphabetical index and type filters to the online reference.
* New entries in the reference conveniently tagged to indicate which version they were introduced in.
* Added missing summary for Set Selectable Property action.

### API

* New 'Create Action' wizard (Tools > GameFlow or Project > Create > GameFlow) to generate .cs scripts for your custom actions. Several action types are currently supported: Action, Function, Time Action and Action for Macros.
* New 'Create Condition' wizard (Tools > GameFlow or Project > Create > GameFlow) to generate .cs scripts for your custom conditions.
* Added initial support for programmatically created custom behaviours.
* Instances of all block types using identifiers (State, Command, Program, etc.) now printing their IDs when logged to console using Log Message.
* Added [HideInSelector] attribute to prevent classes to appear listed in the Type selector window.

### Obsolete

* The following actions are now obsolete and will be automatically removed: Move To, Rotate To, Get Parameter, Limit Parameter, Set Parameter Property.
* Overview component is obsolete and will be removed from the GameObject. All its Link blocks will be automatically converted to notes.
* Overview window also no longer available. It will be replaced with an automatic and more sophisticated overview in future updates.
* Implementing the IVariableFriendly interface is no longer required to make your classes eligible as Object or Enum types for variables, parameters or lists. Your classes still need to extend UnityEngine.Object.

### Preferences

- Renewed Preferences pane. More compact.

### Other

* Source code for MenuItems.cs is now provided so users can customize (adding shortcuts, removing items, etc.) all GameFlow menu items.
* Options in GameObject menu no longer using current selected GameObject as parent for the GameObjects to be created.
* Removed unnecessary (in fact accidental) BaseObject class without namespace to avoid conflicts with other plugins.

### Known Issues

* Breakpoints are disallowed on purpose for cyclic programs (On Update, On Fixed Update, On Late Update).
* You could experience weird focus changes when scrolling through long programs using the mouse wheel.
* You could experience problems with some keys (F2, Return) not responding if there are components like Camera, Mesh Filter or AudioSource on top of the GameFlow component. For now the workaround is either collapsing those components or moving the GameFlow component to the top position in the Inspector.
* Selected action will be unfocused after hiding/showing the parameters of a program.
* References to program parameters will be reset after duplicating a program or changing its type using the context menu option.
* Macro key shorcuts won't work if the Game window has the focus. This is because the default shortcuts for macros use Alt, so you can try modifying them in the Scripts/Editor/MenuItems.cs script for a possible workaround.
