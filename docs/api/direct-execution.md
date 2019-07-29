# Direct execution of actions

Another possibility offered by the GameFlow API is to be able to execute the internal code of the actions directly from your own scripts, thus taking advantage of GameFlow not only as an extension for the Editor but also as a function library.

To make this possible, the GameFlow action classes offer one or more static execution methods that by convention are always called `Execute()`. Therefore, it is only necessary to know the name of the action class to be used and invoke the appropriate method.

If, for example, we wanted to color in Red the GameObject referred to by `target`, we could do it taking advantage of the action [Set Color](../reference.md#set-color) in this way:

```c#
SetColor.Execute(target, Color.red);
```

The static methods of execution as well as the properties available for each action can be found in the [API Reference](reference.md).

> **Note:** This is a feature that was added late to the API so it is still being implemented. This means that some actions may not yet offer this possibility, but we are working so that in future versions all actions can be executed through static methods.

