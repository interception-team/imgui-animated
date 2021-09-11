# imgui-animated

imgui-animated is a collection of templates for animating imgui functions or adding a new one

At the moment it has in itself:

* [ButtonScrollable(Ex)](#buttonscrollableex-usage)
* [Toggle](#toggle-usage)

# ButtonScrollable(Ex) usage:

```cpp
...
ImGui::ButtonScrollable("Button Scrollable", ImVec2(100.f, 0.f));
ImGui::ButtonScrollable("Button Scrollable that fits in button size", ImVec2(350.f, 0.f));
ImGui::ButtonScrollableEx("Button Scrollable (Right-click only!)", ImVec2(100.f, 0.f), ImGuiButtonFlags_MouseButtonRight);
...
```

# Toggle usage:
```cpp
ImGui::Toggle( "Toggle button", &toggle_button );
```
