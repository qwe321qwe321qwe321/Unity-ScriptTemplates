# Unity-ScriptTemplates
There are some script templates and the namespace filler script for Unity.

It is just a backup for personal use and it's a constant work in progress.

---
### Usage

Just put `ScriptTemplates` folder into `Assets/` and restart Unity Editor.

![Demo](./screenshot1.png)

### Namespace Filler

By default, it will fill in a namespace automatically by the path of script that you created.

Examples:
* `Assets/Pedev/Example/Scripts/Foo.cs` -> `Pedev.Example`
* `Assets/Pedev/ExampleEditor/Editor/Foo.cs` -> `Pedev.ExampleEditor`

You can rewrite the namespace rule in `ScriptTemplates/NamespaceFiller.cs`.