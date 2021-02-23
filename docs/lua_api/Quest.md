# Quest

Quest is a wrapper type that encapsulates the current quest object. From the Quest wrapper, you can access it's current position, name, .

An example use of getting and using the Quest type
```lua
local player = World:GetPlayer()
local quest = player.CurrentQuest
player.Position = quest.Position
print(quest.Name) -- Prints current quests name
```

## Metamethods
```lua
String Quest:__tostring()
```
Returns the name of the current quest. Ex. "The Fire and The Fury"
## Properties
***
```lua
Vector3 Quest.Position
```
The position at which the current quest is located.
<br/><br/>
```lua
String Quest.Name
```
The name of the current quest. Ex. "The Fire and The Fury"
***

## Functions
***
```lua
Vector3 Quest:GetPosition()
```
Returns the position at which the current quest is located.
<br/><br/>
```lua
String Quest:GetName()
```
Returns the name of the current quest. Ex. "The Fire and The Fury"
***