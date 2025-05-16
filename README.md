# fluent-library
![image](https://forgenet.gitbook.io/~gitbook/image?url=https%3A%2F%2F1481849050-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FqTYspa6M7hcHjeBMoysI%252Fuploads%252FDgmBN3trLINFncdvGN99%252Flogodark.png%3Falt%3Dmedia%26token%3Dcd8430d9-e0d2-4d17-8f18-0d9fb33bbeba&width=400&dpr=3&quality=100&sign=90acdcc4&sv=2)
### library fluent
```lua
local Fluent = loadstring(game:HttpGet("https://github.com/dawid-scripts/Fluent/releases/latest/download/main.lua"))()
local SaveManager = loadstring(game:HttpGet("https://raw.githubusercontent.com/dawid-scripts/Fluent/master/Addons/SaveManager.lua"))()
local InterfaceManager = loadstring(game:HttpGet("https://raw.githubusercontent.com/dawid-scripts/Fluent/master/Addons/InterfaceManager.lua"))()
```
### this Theme and Window
```lua

local Window = Fluent:CreateWindow({
    Title = "Fluent " .. Fluent.Version,
    SubTitle = "by dawid",
    TabWidth = 160,
    Size = UDim2.fromOffset(580, 460),
    Acrylic = true, -- to you think blur have been true or false
    Theme = "Dark",
    MinimizeKey = Enum.KeyCode.LeftControl -- this our the keybind this you PC
})
```
