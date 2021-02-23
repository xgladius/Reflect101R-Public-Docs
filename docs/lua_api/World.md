# World

World is a global variable wrapping global world helpers such as GetPlayer, getting the current fog, entity list, and many other modifiable properties.

An example use of getting global objects:
```lua
local player = World:GetPlayer()
player.Position = Vector3.new(1,50,1)
World.Fog = Color3.new(255, 22, 100)
```

## Properties
***
```lua
Color3 World.Fog
```
The current RGB fog value (will soon include intensity)
***

## Functions
***
```lua
Player World:GetPlayer()
```
Returns Player object
***