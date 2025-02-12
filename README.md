# About
Asrua UI is a short example of a roblox ui library!

![](https://cdn.discordapp.com/attachments/1300229088426065992/1339203510952005664/293468761-ef4d58b8-93a2-434b-963e-a93e20432faf.jpg?ex=67adddf6&is=67ac8c76&hm=0519024bd79029d5054f005d7585a9702e6bb1fdb94a9f1f0598ea9eaff0eb7d&)
# Usage
Load and Create Asrua UI
```lua
local Lib = loadstring(game:HttpGet("https://raw.githubusercontent.com/sourcersknz/sigma-library/refs/heads/main/sursa.lua"))():MakePrototypeLibrary("Asra UI")
```
Make a Tab
```lua
local CuteTab = Lib:MakeTab("my little adorable tab", true) -- true to make it open by default (optional)
```
Make a Comment (Info Text)
```lua
CuteTab:Info("i love cute cats")
```
Make a Button
```lua
CuteTab:Button("click for a cookie", function()
print("biscuit")
end)
```
Make a Toggle
```lua
CuteTab:Toggle("press me", function(value)
print(value)
end)
```
