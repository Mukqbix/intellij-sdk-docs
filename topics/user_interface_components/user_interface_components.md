<!-- Copyright 2000-2023 JetBrains s.r.o. and contributors. Use of this source code is governed by the Apache 2.0 license. -->

# User Interface Components

<link-summary>Introduction to UI Components provided by IntelliJ Platform.</link-summary>

<tldr>

**Platform UI Guidelines:** [Overview](https://jetbrains.design/intellij/)

</tldr>

The IntelliJ Platform includes a large number of custom [Swing](https://en.wikipedia.org/wiki/Swing_(Java)) components.
Using those components in your plugins will ensure that your plugin looks and works consistently with the UI of the rest of the IDE, and can often reduce the code size compared to using the default Swing components.

> Use [UI Inspector](internal_ui_inspector.md) to locate the underlying Swing component implementation or to inspect an existing UI at runtime.
>

> It is recommended to build UI forms like [dialogs](dialog_wrapper.md) or [settings pages](settings.md) by using the [Kotlin UI DSL](kotlin_ui_dsl_version_2.md) (IntelliJ Platform 2021.3+).
>
> Using _UI Designer_ plugin with Kotlin is [not supported](https://youtrack.jetbrains.com/issue/KTIJ-791).
>
{style="note"}

Please refer to [Writing short and clear](https://jetbrains.design/intellij/text/writing_short/) in IntelliJ Platform UI Guidelines on writing UI-related texts.

> See [UI Kit](https://jetbrains.design/intellij/resources/UI_kit/) when using [Figma](https://www.figma.com) to design UI.
>


The following components are particularly noteworthy:

*  Menus and toolbars are built using [](basic_action_system.md)
*  [](tool_windows.md)
*  [](dialog_wrapper.md)
*  [](popups.md)
*  [](notifications.md)
*  [](file_and_class_choosers.md)
*  [](editor_components.md)
*  [](lists_and_trees.md)
*  [](status_bar_widgets.md)
*  Tables (TableView) (TBD)
*  Drag & Drop Helpers (TBD)
*  [](misc_swing_components.md)
    *  Messages
    *  JBSplitter
    *  JBTabs

<include from="snippets.md" element-id="missingContent"/>
