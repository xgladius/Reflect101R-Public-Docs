# Vector3

Vector3 is a type that stores coordinates X, Y, Z. Vector3 supports the arithmetic operators: Addition, Subtraction, Multiplication, and Division. 

Vector3 also supports normalized copies, dot products, cross products and vector distance.

An example use of using Vector3 is setting the local players position:
```lua
local player = World:GetPlayer()
player.SetPosition(Vector3(1, 5, 1))
```

## Constructors
***
```lua
Vector3(number x = 0, number y = 0, number z = 0)
```
Constructs a new Vector3 using the given x, y, and z numbers.
<br/><br/>
```lua
Vector3.new(number x = 0, number y = 0, number z = 0)
```
Constructs a new Vector3 using the given x, y, and z numbers.
***

## Properties
***
```lua
number Vector3.x
```
The Vector3's X coordinate
<br/><br/>
```lua
number Vector3.y
```
The Vector3's Y coordinate
<br/><br/>
```lua
number Vector3.z
```
The Vector3's Z coordinate
***

## Functions
***
```lua
number Vector3:Length()
```
Returns ((Vector3.x * Vector3.x) + (Vector3.y * Vector3.y) + (Vector3.z * Vector3.z)) ^ 0.5
<br/><br/>
```lua
Vector3 Vector3:GetNormalized()
```
Returns a normalized copy of the Vector3
<br/><br/>
```lua
number Vector3:Dot(Vector3 other)
```
Returns the dot product of two Vector3s
<br/><br/>
```lua
Vector3 Vector3:Cross(Vector3 other)
```
Returns the cross product of two Vector3s
<br/><br/>
```lua
number Vector3:Distance(Vector3 other)
```
Returns the distance between two Vector3s

***