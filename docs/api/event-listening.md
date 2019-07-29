# Event listening

The GameFlow API also exposes a series of subclasses of `GFEvent` that represent the different events that GameFlow is able to manage. These classes are the following:

| Scope | Event Classes |
|-------|---------------|
| Application | [ApplicationFocusEvent](reference.md#applicationFocusEvent-class), [ApplicationInitEvent](reference.md#applicationInitEvent-class), [ApplicationPauseEvent](reference.md#applicationPauseEvent-class), [ApplicationQuitEvent](reference.md#applicationQuitEvent-class) |
| Physics | [CollisionEnterEvent](reference.md#collisionEnterEvent-class), [CollisionExitEvent](reference.md#collisionExitEvent-class), [CollisionStayEvent](reference.md#collisionStayEvent-class), [TriggerEnterEvent](reference.md#triggerEnterEvent-class), [TriggerExitEvent](reference.md#triggerExitEvent-class), [TriggerStayEvent](reference.md#triggerStayEvent-class) |
| User Interface | [ClickEvent](reference.md#clickEvent-class), [DeselectEvent](reference.md#deselectEvent-class), [EndEditEvent](reference.md#endEditEvent-class), [PointerDownEvent](reference.md#pointerDownEvent-class), [PointerEnterEvent](reference.md#pointerEnterEvent-class), [PointerExitEvent](reference.md#pointerExitEvent-class), [PointerUpEvent](reference.md#pointerUpEvent-class), [SelectEvent](reference.md#selectEvent-class), [ValueChangeEvent](reference.md#valueChangeEvent-class) |
| Activation | [ActivationEvent](reference.md#activationEvent-class), [DeactivationEvent](reference.md#deactivationEvent-class) |
| Customization | [CustomEvent](reference.md#customEvent-class) |
| Communication | [ExternalMessageEvent](reference.md#externalMessageEvent-class) |
| Game | [GameOverEvent](reference.md#gameOverEvent-class), [GamePauseEvent](reference.md#gamePauseEvent-class), [GameResumeEvent](reference.md#gameResumeEvent-class), [GameStartEvent](reference.md#gameStartEvent-class) |
| Keyboard | [KeyDownEvent](reference.md#keyDownEvent-class), [KeyUpEvent](reference.md#keyUpEvent-class) |
| Localization | [LanguageEvent](reference.md#languageEvent-class) |
| Mouse | [MouseDownEvent](reference.md#mouseDownEvent-class), [MouseDragEvent](reference.md#mouseDragEvent-class), [MouseEnterEvent](reference.md#mouseEnterEvent-class), [MouseExitEvent](reference.md#mouseExitEvent-class), [MouseOverEvent](reference.md#mouseOverEvent-class), [MouseUpEvent](reference.md#mouseUpEvent-class) |
| Timer | [TimerExpireEvent](reference.md#timerExpireEvent-class) |
| Program | [ProgramFinishEvent](reference.md#programFinishEvent-class) |
| Data | [VariableChangeEvent](reference.md#variableChangeEvent-class), [ParameterChangeEvent](reference.md#parameterChangeEvent-class) |
| Scenes | [SceneLoadEvent](reference.md#sceneLoadEvent-class) |

### Event subscription

Any object that implements the `IEventListener` interface can be added to the list of subscribers that will receive a notification when an event of a certain type is triggered. This allows your own scripts to react to events triggered by GameFlow programs.

The steps to follow to do this are:

1. Implement in our script the `IsListening()` and `EventReceived()` methods of the `IEventListener` interface to filter and respond to events.
2. Invoke the `AddListener()` static method of the type of event to which we want an instance of our script to subscribe.

In the following example, each instance of our `MyEventHook` script is subscribed to receive notifications of events of type `GameStart`. Each time one of these events is received, we will post a message on the console as an answer:

```c#
using GameFlow;
using UnityEngine;

namespace MyNamespace {

public class MyEventHook : MonoBehaviour, IEventListener {

	void Start() {
		GameStartEvent.AddListener(this);
	}

	public void EventReceived(GFEvent e) {
		Debug.Log("Game started!");
	}

	public bool IsListening() {
		return true;
	}

}

}
```
