# imgui-animated

imgui-animated is a collection of templates for animating imgui functions or adding a new one

At the moment it has in itself:

* [ButtonScrollable(Ex)](#buttonscrollableex-usage)
* [Toggle](#toggle-usage)

# ButtonScrollable(Ex) usage:
https://user-images.githubusercontent.com/47151102/132950549-46cd755a-4104-4d39-b175-2f5bfb8f7dca.mp4
```cpp
...
ImGui::ButtonScrollable("Button Scrollable", ImVec2(100.f, 0.f));
ImGui::ButtonScrollable("Button Scrollable that fits in button size", ImVec2(350.f, 0.f));
ImGui::ButtonScrollableEx("Button Scrollable (Right-click only!)", ImVec2(100.f, 0.f), ImGuiButtonFlags_MouseButtonRight);
...
```

# Toggle usage:
https://user-images.githubusercontent.com/47151102/132950560-aeb77c0d-3c1f-46bc-9cb3-c0a974f92600.mp4
```cpp
ImGui::Toggle( "Toggle button", &toggle_button );
```
