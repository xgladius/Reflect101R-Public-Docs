# Color3

Color3 is a type that stores a color as Red, Green, Blue. 

An example use of using Color3 is setting the Worlds fog color:
```lua
World.Fog = Color3(255, 127, 40)
Sleep(500)
World.Fog = Color3(127, 127, 255)
Sleep(500)
World.Fog = Color3.random()
```

## Constructors
***
```lua
Color3(number r = 0, number g = 0, number b = 0)
```
Constructs a new Color3 using the given Red, Green, and Blue numbers.
<br/><br/>
```lua
Color3.new(number r = 0, number g = 0, number b = 0)
```
Constructs a new Color3 using the given Red, Green, and Blue numbers.
***

## Properties
***
```lua
number Color3.r
```
The Color3's red value
<br/><br/>
```lua
number Color3.g
```
The Color3's green value
<br/><br/>
```lua
number Color3.b
```
The Color3's blue value
***

## Functions
***
```lua
Color3 Color3.random()
```
Returns a random Color3 value
***