## [Internal Debug](InternalDebug/Runtime/InternalDebug.cs)
 
This is a static `InternalDebug` wrapper class for the `UnityEngine.Debug` class.
Any call from this class will only be present when the build is either a Development Build or build in
Development Mode.

```csharp
InternalDebug.Log("Hello World!"); // Will not run in production builds unlike Debug.Log
```

*Modified from: https://github.com/JoebRogers/UnityDebug/blob/master/src/InternalDebug_NoNamespace.cs*
