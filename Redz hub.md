## Ui Lib
```lua
local redzlib = loadstring(game:HttpGet("https://raw.githubusercontent.com/realredz/RedzLibV5/refs/heads/main/Source.lua"))()
```

## Window
```lua
local Window = redzlib:MakeWindow({
  Title = "redz Hub : Blox Fruits",
  SubTitle = "by redz9999",
  SaveFolder = "testando | redz lib v5.lua"
})
```

## Icon 
```lua
Window:AddMinimizeButton({
    Button = { Image = "rbxassetid://71014873973869", BackgroundTransparency = 0 },
    Corner = { CornerRadius = UDim.new(35, 1) },
})
```

## Discord invite
```lua
Tab1:AddDiscordInvite({
    Name = "Name Hub",
    Description = "Join server",
    Logo = "rbxassetid://18751483361",
    Invite = "https://discord.com/invite/Dmg8EJ2neK",
})
```


## Tab
```lua
local Tab = Window:MakeTab({"Um", "cherry"})
```

## Codes for change theme of redz lib
Dark
```lua
  redzlib:SetTheme("Dark")
```
Darkers
```lua
  redzlib:SetTheme("Darker")
```
Purple
```lua
  redzlib:SetTheme("Purple")
```
## Start tab
```lua
Window:SelectTab(Tab2)
```
## Section
```lua
local Section = Tab2:AddSection({"Section"})
```

## Paragraph
```lua
local Paragraph = Tab2:AddParagraph({"Paragraph", "This is a Paragraph\nSecond Line"})
```
## Dialog
```lua
  local Dialog = Window:Dialog({
    Title = "Dialog",
    Text = "This is a Dialog",
    Options = {
      {"Confirm", function()
        
      end},
      {"Maybe", function()
        
      end},
      {"Cancel", function()
        
      end}
    }
  })
```
## Button
```lua
Tab1:AddButton({"Print", function()
print("Hello World!")
end})
```
## Toggle
```lua
local Toggle1 = Tab1:AddToggle({
  Name = "Toggle",
  Description = "This is a <font color='rgb(88, 101, 242)'>Toggle</font> Example",
  Default = false 
})
Toggle1:Callback(function(value)
 
end)
```

## Sliders
```lua
Tab1:AddSlider({
  Name = "Speed",
  Min = 1,
  Max = 100,
  Increase = 1,
  Default = 16,
  Callback = function(Value)
  game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = Value
  end
})
```

## Dropdown
```lua
local Dropdown = Tab2:AddDropdown({
  Name = "Players List",
  Description = "Select the <font color='rgb(88, 101, 242)'>Number</font>",
  Options = {"one", "two", "three"},
  Default = "two",
  Flag = "dropdown teste",
  Callback = function(Value)
    
  end
})
```
## Test script fun 
![Image Alt](https://github.com/tbao143/Library-ui/blob/fde12da5b8e3be4511125eac98eb24c968f55228/0ae1428d807b40f19e3f6ce750ff7034.png)
