# Reference

## Action (Class)

Base class for implementing custom Action blocks.

## ActionEditor (Class)

Base class for implementing the user interface of a custom Action blocks.

## ActivationEvent (Class)

Event fired when a GameObject is activated.

#### Properties

| Property | Description                       | Type       |
| -------- | --------------------------------- | ---------- |
| source   | The GameObject that was activated | GameObject |

#### Remarks

Events of this type are managed by the [On Activate](..\reference.md#OnActivate) program.

## ApplicationFocusEvent (Class)

Event fired when the Application gets or losts the input focus.

#### Properties

| Property  | Description                                          | Type |
| --------- | ---------------------------------------------------- | ---- |
| isFocused | Whether the application is currently focused or not. | bool |

#### Remarks

Events of this type are managed by the [On Application Focus](OnApplicationFocus) program.

## ApplicationInitEvent (Class)

Event fired when the Application starts.

#### Remarks

Events of this type are managed by the [On Application Init](OnApplicationInit) program.

## ApplicationPauseEvent (Class)

Event fired when the Application enters or exits pause.

The term "Pause" here refers to OS level pause, not to be confused with [GamePauseEvent](GamePauseEvent).

#### Properties

| Property | Description                                         | Type |
| -------- | --------------------------------------------------- | ---- |
| isPaused | Whether the application is currently paused or not. | bool |

#### Remarks

Events of this type are managed by the [On Application Pause](OnApplicationPause) program.

## ApplicationQuitEvent (Class)

Event fired when the Application is about to close.

#### Remarks

Events of this type are managed by the [On Application Quit](OnApplicationQuit) program.

## BuiltinVariable (Class)

Base class for implementing built-in Variables.

## ClickEvent (Class)

Event fired when a click is detected in the area of an UI element.

#### Properties

| Property | Description                                   | Type       |
| -------- | --------------------------------------------- | ---------- |
| source   | The GameObject where the event was originated | GameObject |
| position | The current screen coordinates of the pointer | Vector2    |

#### Remarks

Events of this type are managed by the [On Click](OnClick) program.

## CollisionEnterEvent (Class)

Event fired when a collider/rigidbody has begun touching another rigidbody/collider.

#### Properties

| Property         | Description                                               | Type       |
| ---------------- | --------------------------------------------------------- | ---------- |
| source           | The GameObject that was collided                          | GameObject |
| other            | The GameObject that collided with 'source'                | GameObject |
| contactPoint     | The 3d world coordinates of the collision contact point   | Vector3    |
| relativeVelocity | The relative linear velocity of the two colliding objects | Vector3    |

#### Remarks

Events of this type are managed by the [On Collision Enter](OnCollisionEnter) program.

## CollisionExitEvent (Class)

Event fired when a collider/rigidbody has stopped touching another rigidbody/collider.

#### Properties

| Property         | Description                                               | Type       |
| ---------------- | --------------------------------------------------------- | ---------- |
| source           | The GameObject that was collided                          | GameObject |
| other            | The GameObject that collided with 'source'                | GameObject |
| contactPoint     | The 3d world coordinates of the collision contact point   | Vector3    |
| relativeVelocity | The relative linear velocity of the two colliding objects | Vector3    |

#### Remarks

Events of this type are managed by the [On Collision Exit](OnCollisionExit) program.

## CollisionStayEvent (Class)

Event fired while (that is, every frame) a collider/rigidbody is touching another rigidbody/collider.

#### Properties

| Property         | Description                                               | Type       |
| ---------------- | --------------------------------------------------------- | ---------- |
| source           | The GameObject that was collided                          | GameObject |
| other            | The GameObject that collided with 'source'                | GameObject |
| contactPoint     | The 3d world coordinates of the collision contact point   | Vector3    |
| relativeVelocity | The relative linear velocity of the two colliding objects | Vector3    |

#### Remarks

Events of this type are managed by the [On Collision Stay](OnCollisionStay) program.

## Command (Class)

Class implementing the Command block.

## Condition (Class)

Base class for implementing custom Condition blocks.

## ConditionEditor (Class)

Base class for implementing the user interface of a custom [Condition](#condition-class) blocks.

## CustomEvent (Class)

Event typically fired by the [Fire Custom Event](FireCustomEvent) action.

#### Properties

| Property | Description                                            | Type       |
| -------- | ------------------------------------------------------ | ---------- |
| source   | The origin of the event                                | GameObject |
| kind     | A literal descriptor / identifier useful for filtering | string     |
| data     | Data attached to the event                             | Variable   |

## Methods

`public void AddListener(IEventListener listener)`

Subscribes the specified listener to next events of this type.

`public void RemoveListener(IEventListener listener)`

Removes the specified listener from the subscription list for events of this type.

### Remarks

Events of this type are managed by the [On Custom Event](OnCustomEvent) program.

## DeactivationEvent (Class)

Event fired when a GameObject is deactivated.

#### Properties

| Property | Description                         | Type       |
| -------- | ----------------------------------- | ---------- |
| source   | The GameObject that was deactivated | GameObject |

#### Remarks

Events of this type are managed by the [On Deactivate](OnDeactivate) program.

## Description (Class)

Class implementing the [Description](Description) block.

## DeselectEvent (Class)

Event fired when a selectable UI element is deselected.

#### Properties

| Property | Description                                   | Type       |
| -------- | --------------------------------------------- | ---------- |
| source   | The GameObject where the event was originated | GameObject |

#### Remarks

Events of this type are managed by the [On Deselect](OnDeselect) program.

## DrawGizmosAction (Class)

Base class for implementing special custom Action blocks that only work within [On Draw Gizmos](OnDrawGizmos) Programs.

## DrawGizmosActionEditor (Class)

Base class for implementing the user interface of a custom block extending the [DrawGizmosAction](#drawgizmosaction-class) class.

## During (Class)

Class implementing the [During](During) Action block.

## EndEditEvent (Class)

Event fired when the editing of an InputField has ended.

#### Properties

| Property | Description                              | Type       |
| -------- | ---------------------------------------- | ---------- |
| source   | The GameObject that originated the event | GameObject |
| value    | The text in the InputField               | String     |

### Remarks

Events of this type are managed by the [On End Edit](OnEndEdit) program.

## EvaluateConditions (Class)

Class implementing the [Evaluate Conditions](EvaluateConditions) Action block.

## ExternalMessageEvent (Class)

Event fired when a message from the host browser is received.

#### Properties

| Property      | Description                                         | Type     |
| ------------- | --------------------------------------------------- | -------- |
| stringMessage | The received message as string                      | string   |
| intMessage    | The received message as signed 32-bit integer value | int      |
| floatMessage  | The received message as 32-bit floating-point value | float    |
| dataType      | The data type of the received message               | DataType |

#### Remarks

Events of this type are managed by the [On External Message](OnExternalMessage) program.

## For (Class)

Class implementing the [For](For) Action block.

## ForEach (Class)

Class implementing the [For Each](ForEach) Action block.

## Force (Class)

Class implementing the Force block.

## Function (Class)

Base class for implementing custom Action blocks that return a result value.

## FunctionEditor (Class)

Base class for implementing the user interface of custom [Function](#function-class) blocks.

## GameOverEvent (Class)

Event fired by the [Game Over](GameOver) action.

#### Remarks

Events of this type are managed by the [On Game Over](OnGameOver) program.

## GamePauseEvent (Class)

Event fired by the [Pause Game](Pause Game) action.

#### Remarks

Events of this type are managed by the [On Game Pause](OnGamePause) program.

## GameResumeEvent (Class)

Event fired by the [Resume Game](ResumeGame) action.

#### Remarks

Events of this type are managed by the [On Game Resume](OnGameResume) program.

## GameStartEvent (Class)

Event fired by the [Start Game](StartGame) action.

#### Remarks

Events of this type are managed by the [On Game Start](OnGameStart) program.

## Group (Class)

Class implementing the [Group](Group) Action block.

## If (Class)

Class implementing the [If](If) Action block.

## Key (Class)

Class implementing the Key block.

## KeyDownEvent (Class)

Event fired when a [Key](Key) is pressed.

#### Properties

| Property | Description              | Type |
| -------- | ------------------------ | ---- |
| key      | The key that was pressed | Key  |

## KeyUpEvent (Class)

Event fired when a [Key](Key) that was pressed is released.

#### Properties

| Property | Description               | Type |
| -------- | ------------------------- | ---- |
| key      | The key that was released | Key  |

## LanguageEvent (Class)

Event fired when the current language is changed.

#### Properties

| Property | Description              | Type     |
| -------- | ------------------------ | -------- |
| language | The new current language | Language |

#### Remarks

Events of this type are managed by the [On Language Set](OnLanguageSet) program.

## LimitValueAction (Class)

Base class for implementing custom Action blocks.

## LimitValueActionEditor (Class)

Base class for implementing the user interface of a custom Action blocks.

## List (Class)

Class implementing the List block.

## ListAction (Class)

Base class for implementing custom Action blocks that work with a List.

## ListActionEditor (Class)

Base class for implementing the user interface of a custom Action blocks.

## ListFunction (Class)

Base class for implementing custom Action blocks that work with a List and return a result value.

## ListFunctionEditor (Class)

Base class for implementing the user interface of custom [Function](#function-class) blocks.

## ListIndexAction (Class)

Base class for implementing custom Action blocks that work with a List and an Index property.

## ListIndexActionEditor (Class)

Base class for implementing the user interface of a custom Action blocks.

## ListIndexFunction (Class)

Base class for implementing custom Action blocks that work with a List and an Index property and return a result value.

## ListIndexFunctionEditor (Class)

Base class for implementing the user interface of custom [Function](#function-class) blocks.

## ListItemAction (Class)

Base class for implementing custom Action blocks that work with a List and an Item property.

## ListItemActionEditor (Class)

Base class for implementing the user interface of a custom Action blocks.

## ListItemFunction (Class)

Base class for implementing custom Action blocks that work with a List and an Item property and return a result value.

## ListItemFunctionEditor (Class)

Base class for implementing the user interface of custom [Function](#function-class) blocks.

## ListItemIndexAction (Class)

Base class for implementing custom Action blocks that work with a List, an Index and an Item property.

## ListItemIndexActionEditor (Class)

Base class for implementing the user interface of a custom Action blocks.

## ListItemIndexFunction (Class)

Base class for implementing custom Action blocks that work with a List, an Index and an Item property and return a result value.

## ListItemIndexFunctionEditor (Class)

Base class for implementing the user interface of custom [Function](#function-class) blocks.

## Localization (Class)

Class implementing the Localization block.

## Loop (Class)

Class implementing the [Loop](Loop) Action block.

## Macro (Class)

Class implementing the Macro Program block.

## MouseDownEvent (Class)

Event fired when any mouse button is pressed in the area of an UI element or Collider.

#### Properties

| Property | Description                                         | Type       |
| -------- | --------------------------------------------------- | ---------- |
| source   | The GameObject where the event was originated       | GameObject |
| position | The current screen coordinates of the mouse pointer | Vector2    |

#### Remarks

Events of this type are managed by the [On Mouse Down](OnMouseDown) program.

## MouseDragEvent (Class)

Event fired when the mouse is dragged in the area of an UI element or Collider.

#### Properties

| Property | Description                                                  | Type       |
| -------- | ------------------------------------------------------------ | ---------- |
| source   | The GameObject where the event was originated                | GameObject |
| position | The current screen coordinates of the mouse pointer          | Vector2    |
| delta    | The mouse movement since last frame expressed as relative screen coordinates | Vector2    |

#### Remarks

Events of this type are managed by the [On Mouse Drag](OnMouseDrag) program.

## MouseEnterEvent (Class)

Event fired after the mouse pointer enters the area of an UI element or Collider.

#### Properties

| Property | Description                                         | Type       |
| -------- | --------------------------------------------------- | ---------- |
| source   | The GameObject where the event was originated       | GameObject |
| position | The current screen coordinates of the mouse pointer | Vector2    |

#### Remarks

Events of this type are managed by the [On Mouse Enter](OnMouseEnter) program.

## MouseExitEvent (Class)

Event fired after the mouse pointer exits the area of an UI element or Collider.

#### Properties

| Property | Description                                         | Type       |
| -------- | --------------------------------------------------- | ---------- |
| source   | The GameObject where the event was originated       | GameObject |
| position | The current screen coordinates of the mouse pointer | Vector2    |

#### Remarks

Events of this type are managed by the [On Mouse Exit](OnMouseExit) program.

## MouseOverEvent (Class)

Event fired while (that is, every frame) the mouse pointer is inside the area of an UI element or Collider.

#### Properties

| Property | Description                                         | Type       |
| -------- | --------------------------------------------------- | ---------- |
| source   | The GameObject where the event was originated       | GameObject |
| position | The current screen coordinates of the mouse pointer | Vector2    |

#### Remarks

Events of this type are managed by the [On Mouse Over](OnMouseOver) program.

## MouseUpEvent (Class)

Event fired when any mouse button is released in the area of an UI element or Collider.

#### Properties

| Property | Description                                         | Type       |
| -------- | --------------------------------------------------- | ---------- |
| source   | The GameObject where the event was originated       | GameObject |
| position | The current screen coordinates of the mouse pointer | Vector2    |

#### Remarks

Events of this type are managed by the [On Mouse Up](OnMouseUp) program.

## Note (Class)

Class implementing the [Note](Note) block.

## NumericParameterAction (Class)

## NumericParameterActionEditor (Class)

Base class for implementing the user interface of a custom Action blocks.

## NumericVariableAction (Class)

## NumericVariableActionEditor (Class)

Base class for implementing the user interface of a custom Action blocks.

## OnActivate (Class)

Class implementing the [On Activate](OnActivate) Program block.

## OnApplicationFocus (Class)

Class implementing the [On Application Focus](OnApplicationFocus) Program block.

## OnApplicationInit (Class)

Class implementing the [On Application Init](OnApplicationInit) Program block.

## OnApplicationPause (Class)

Class implementing the [On Application Pause](OnApplicationPause) Program block.

## OnApplicationQuit (Class)

Class implementing the [On Application Quit](OnApplicationQuit) Program block.

## OnAwake (Class)

Class implementing the [On Awake](OnAwake) Program block.

## OnClick (Class)

Class implementing the [On Click](OnClick) Program block.

## OnCollisionEnter (Class)

Class implementing the [On Collision Enter](OnCollisionEnter) Program block.

## OnCollisionEnter2D (Class)

Class implementing the [On Collision Enter 2D](OnCollisionEnter2D) Program block.

## OnCollisionExit (Class)

Class implementing the [On Collision Exit](OnCollisionExit) Program block.

## OnCollisionExit2D (Class)

Class implementing the [On Collision Exit 2D](OnCollisionExit2D) Program block.

## OnCollisionStay (Class)

Class implementing the [On Collision Stay](OnCollisionStay) Program block.

## OnCollisionStay2D (Class)

Class implementing the [On Collision Stay 2D](OnCollisionStay2D) Program block.

## OnCustomEvent (Class)

Class implementing the [On Custom Event](OnCustomEvent) Program block.

## OnDeactivate (Class)

Class implementing the [On Deactivate](OnDeactivate) Program block.

## OnDeselect (Class)

Class implementing the [On Deselect](OnDeselect) Program block.

## OnDestroy (Class)

Class implementing the [On Destroy](OnDestroy) Program block.

## OnDrawGizmos (Class)

Class implementing the [On Draw Gizmos](OnDrawGizmos) Program block.

## OnEndEdit (Class)

Class implementing the [On End Edit](OnEndEdit) Program block.

## OnExternalMessage (Class)

Class implementing the [On External Message](OnExternalMessage) Program block.

## OnFixedUpdate (Class)

Class implementing the [On Fixed Update](OnFixedUpdate) Program block.

## OnGameOver (Class)

Class implementing the [On Game Over](OnGameOver) Program block.

## OnGamePause (Class)

Class implementing the [[On Game Pause](OnGamePause) Program block.

## OnGameResume (Class)

Class implementing the [On Game Resume](OnGameResume) Program block.

## OnGameStart (Class)

Class implementing the [On Game Start](OnGameStart) Program block.

## OnLanguageSet (Class)

Class implementing the [On Language Set](OnLanguageSet) Program block.

## OnLateUpdate (Class)

Class implementing the [On Late Update](OnLateUpdate) Program block.

## OnMouseDown (Class)

Class implementing the [On Mouse Down](OnMouseDown) Program block.

## OnMouseDrag (Class)

Class implementing the [On Mouse Drag](OnMouseDrag) Program block.


## OnMouseEnter (Class)

Class implementing the [[On Mouse Enter](OnMouseEnter) Program block.

## OnMouseExit (Class)

Class implementing the [On Mouse Exit](OnMouseExit) Program block.

## OnMouseOver (Class)

Class implementing the [On Mouse Over](OnMouseOver) Program block.

## OnMouseUp (Class)

Class implementing the [On Mouse Up](OnMouseUp) Program block.

## OnParameterChange (Class)

Class implementing the On Parameter Change](OnParameterChange) Program block.

## OnPointerDown (Class)

Class implementing the [On Pointer Down](OnPointerDown) Program block.

## OnPointerEnter (Class)

Class implementing the [On Pointer Enter](OnPointerEnter) Program block.

## OnPointerExit (Class)

Class implementing the [On Pointer Exit](OnPointerExit) Program block.

## OnPointerUp (Class)

Class implementing the [On Pointer Up](OnPointerUp) Program block.

## OnProgramFinish (Class)

Class implementing the [On Program Finish](OnProgramFinish) Program block.

## OnSceneLoad (Class)

Class implementing the [On Scene Load](OnSceneLoad) Program block.

`1.2`

## OnSelect (Class)

Class implementing the [On Select](OnSelect) Program block.

## OnStart (Class)

Class implementing the [On Start](OnStart) Program block.

## OnState (Class)

Class implementing the [On State](OnState) Action block.

## OnTimerExpire (Class)

Class implementing the [On Timer Expire](OnTimerExpire) Program block.

## OnTriggerEnter (Class)

Class implementing the [On Trigger Enter](OnTriggerEnter) Program block.


## OnTriggerEnter2D (Class)

Class implementing the [On Trigger Enter 2D](OnTriggerEnter2D) Program block.

## OnTriggerExit (Class)

Class implementing the [On Trigger Exit](OnTriggerExit) Program block.

## OnTriggerExit2D (Class)

Class implementing the [On Trigger Exit 2D](OnTriggerExit2D) Program block.

## OnTriggerStay (Class)

Class implementing the [On Trigger Stay](OnTriggerStay) Program block.

## OnTriggerStay2D (Class)

Class implementing the [On Trigger Stay 2D](OnTriggerStay2D) Program block.

## OnUpdate (Class)

Class implementing the [On Update](OnUpdate) Program block.

## OnValueChange (Class)

Class implementing the [On Value Change](OnValueChange) Program block.

## OnVariableChange (Class)

Class implementing the [On Variable Change](OnVariableChange) Program block.

## Parameter (Class)

Class implementing the Parameter block.

## ParameterAction (Class)

## ParameterActionEditor (Class)

Base class for implementing the user interface of a custom Action blocks.

## ParameterChangeEvent (Class)

Event fired when the value of a [Parameter](Parameter) is changed.

#### Properties

| Property  | Description             | Type       |
| --------- | ----------------------- | ---------- |
| parameter | The Parameter changed   | Parameter  |

#### Remarks

Events of this type are managed by the [On Parameter Change](OnParameterChange) program.

## Path (Class)

Class implementing the Path block.

## PointerDownEvent (Class)

Event fired when the pointer is down in the area of an UI element.

#### Properties

| Property | Description                                   | Type       |
| -------- | --------------------------------------------- | ---------- |
| source   | The GameObject where the event was originated | GameObject |
| position | The current screen coordinates of the pointer | Vector2    |

#### Remarks

Events of this type are managed by the [On Pointer Down](OnPointerDown) program.

## PointerEnterEvent (Class)

Event fired when the pointer enters the area of an UI element.

#### Properties

| Property | Description                                   | Type       |
| -------- | --------------------------------------------- | ---------- |
| source   | The GameObject where the event was originated | GameObject |
| position | The current screen coordinates of the pointer | Vector2    |

#### Remarks

Events of this type are managed by the [On Pointer Enter](OnPointerEnter) program.

## PointerExitEvent (Class)

Event fired when the pointer exits the area of an UI element.

#### Properties

| Property | Description                                   | Type       |
| -------- | --------------------------------------------- | ---------- |
| source   | The GameObject where the event was originated | GameObject |
| position | The current screen coordinates of the pointer | Vector2    |

#### Remarks

Events of this type are managed by the [On Pointer Exit](OnPointerExit) program.

## PointerUpEvent (Class)

Event fired when the pointer stops being down in the area of an UI element.

#### Properties

| Property | Description                                   | Type       |
| -------- | --------------------------------------------- | ---------- |
| source   | The GameObject where the event was originated | GameObject |
| position | The current screen coordinates of the pointer | Vector2    |

#### Remarks

Events of this type are managed by the [On Pointer Up](OnPointerUp) program.

## Pool (Class)

Class implementing the Pool block.

## ProgramFinishEvent (Class)

Event fired after a [Program](Program) finished.

#### Properties

| Property | Description               | Type    |
| -------- | ------------------------- | ------- |
| program  | The Program that finished | Program |

#### Remarks

Events of this type are managed by the [On Program Finish](OnProgramFinish) program.

## Ray (Class)

Class implementing the Ray block.

## Repeat (Clase)

Class implementing the [Repeat](Repeat) Action block.

## RepeatUntil (Clase)

Class implementing the [Repeat Until](RepeatUntil) Action block.

## SceneLoadEvent (Class)

Event fired after a Scene is completely loaded.

`1.2`

#### Properties

| Property | Description                         | Type |
| -------- | ----------------------------------- | -- |
| scene    | The loaded scene                    | Scene |
| loadMode | The mode used for loading the scene | LoadSceneMode |

#### Remarks

Events of this type are managed by the [On Scene Load](OnSceneLoad) program.

## SelectEvent (Class)

Event fired when a selectable UI element is selected.

#### Properties

| Property | Description                                   | Type       |
| -------- | --------------------------------------------- | ---------- |
| source   | The GameObject where the event was originated | GameObject |

#### Remarks

Events of this type are managed by the [On Select](OnSelect) program.

## Separator (Class)

Class implementing the [Separator](Separator) block.

## State (Class)

Class implementing the [State](State) block.

## StateMachine (Class)

Class implementing the [State Machine](StateMachine) block.

## TimeAction (Class)

## TimeActionEditor (Class)

Base class for implementing the user interface of a custom Action blocks.

## TimeFunction (Class)

Base class for implementing custom Action blocks that return a result value.

## TimeFunctionEditor (Class)

Base class for implementing the user interface of custom [Function](#function-class) blocks.

## Timer (Class)

## TimerExpireEvent (Class)

Event fired after a [Timer](Timer) expires.

#### Properties

| Property | Description            | Type  |
| -------- | ---------------------- | ----- |
| timer    | The Timer that expired | Timer |

#### Remarks

Events of this type are managed by the [On Timer Expire](OnTimerExpire) program.

## TransformAction (Class)

Base class for implementing custom Action blocks.

## TransformAction2D (Class)

Base class for implementing custom Action blocks.

## TransformAction2DEditor (Class)

Base class for implementing the user interface of a custom Action blocks.

## TransformActionEditor (Class)

Base class for implementing the user interface of a custom Action blocks.

## TriggerEnterEvent (Class)

Event fired when the area of a trigger type Collider is entered by another Collider or Rigidbody.

#### Properties

| Property | Description                                                  | Type       |
| -------- | ------------------------------------------------------------ | ---------- |
| source   | The GameObject containing the entered trigger Collider       | GameObject |
| other    | The GameObject containing the Collider that entered 'source' | GameObject |

#### Remarks

Events of this type are managed by the [On Trigger Enter](OnTriggerEnter) program.

## TriggerExitEvent (Class)

Event fired when the area of a trigger type Collider is no longer intersected by another Collider or Rigidbody.

#### Properties

| Property | Description                                                  | Type       |
| -------- | ------------------------------------------------------------ | ---------- |
| source   | The GameObject containing the intersected trigger Collider   | GameObject |
| other    | The GameObject containing the object that intersected 'source' | GameObject |

#### Remarks

Events of this type are managed by the [On Trigger Exit](OnTriggerExit) program.

## TriggeStayEvent (Class)

Event fired while (that is, every frame) the area of a trigger type Collider is intersected by another Collider or Rigidbody.

#### Properties

| Property | Description                                                  | Type       |
| -------- | ------------------------------------------------------------ | ---------- |
| source   | The GameObject containing the trigger Collider being intersected | GameObject |
| other    | The GameObject containing the object that is intersecting the 'source' Collider | GameObject |

#### Remarks

Events of this type are managed by the [On Trigger Stay](OnTriggerStay) program.

## ValueAction (Class)

## ValueActionEditor (Class)

Base class for implementing the user interface of a custom Action blocks.

## ValueChangeEvent (Class)

Event fired when when the value of a UI Component (of type InputField, Toggle, Slider or Scrollbar) is changed.

#### Properties

| Property      | Description                                         | Type     |
| ------------- | --------------------------------------------------- | -------- |
| source   | The GameObject where the event was originated | GameObject |
| stringValue | The new value as string (InputField). | string   |
| toggleValue | The new value as boolean (Toggle) | bool |
| floatValue | The new value as 32-bit floating-point value (Slider and Scrollbar) | float    |
| dataType      | The data type of the changed value           | DataType |

#### Remarks

Events of this type are managed by the [On Value Change](OnValueChange) program.

## ValueCondition (Class)

Base class for implementing custom Condition blocks.

## Variable (Class)

## VariableAction (Class)

## VariableActionEditor (Class)

Base class for implementing the user interface of a custom Action blocks.

## VariableChangeEvent (Class)

Event fired when the value of a [Variable](Variable) is changed.

#### Properties

| Property  | Description           | Type      |
| --------- | --------------------- | --------- |
| variable  | The Variable changed  | Variable  |

#### Remarks

Events of this type are managed by the [On Variable Change](OnVariableChange) program.

## While (Clase)

Class implementing the [While](While) Action block.
