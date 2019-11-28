This is a version of [MoonSharp](https://github.com/moonsharp-devs/moonsharp) that is modified for use with the [RedOnion](https://github.com/evandisoft/RedOnion) project.

We've made the following changes:
1. Renamed the AssemblyName to `MunSharp` in order to avoid conflicts with other KSP mods' uses of MoonSharp.
2. Modified the auto-registration of classes to not throw an error when one member name hides another without overriding it, but
instead to overwrite the member that should be hidden.
