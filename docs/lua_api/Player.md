# Player

Player is a wrapper type that encapsulates the local player object. From the player, you can access the current quest, the players camera, the current player position, and much more.

An example use of getting the player
```lua
local player = World:GetPlayer()
player.Position = player.CurrentQuest.Position
```

## Metamethods
```lua
String Player:__tostring()
```
Returns the name of the current player. Ex. "Christo Stormshade"
## Properties
***
```lua
Quest Player.CurrentQuest
```
The current quest that is actively being seeked by the player.
<br/><br/>
```lua
Vector3 Player.Position
```
The current position at which the player is located.
<br/><br/>
```lua
String Player.Name
```
The name of the current player. Ex. "Christo Stormshade"
***

## Functions
***
```lua
Vector3 Player:GetPosition()
```
Returns the current position at which the player is located.
<br/><br/>
```lua
Vector3 Player:GetCurrentQuest()
```
Returns the current quest that is actively being seeked by the player.
<br/><br/>
```lua
Vector3 Player:GetName()
```
Returns the name of the current player. Ex. "Christo Stormshade"
***