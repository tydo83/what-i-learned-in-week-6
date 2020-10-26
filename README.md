# What I learned in week 6

## DRY and WET
* DRY - don't repeat yourself
* WET - write everything twice
---
---
## Object.assign
```
const newEnemy = object.assign(obj1, obj2)
// assign obj 2 to obj1
```
* Object order doesn't matter 
---
## spread
```
{...{h},...a,...b}
```
---
## Blueprint function / Factory function
* function making object
---
## Default parameter
```
test = (a, b, c = 1)
// if c is undefined, assign 1 to c 
```
---
## Slice can have negative parameter as well
```
name.slice(3, -2)
```
---
## Require
```
const requireExample = require('./path');
```
* You don't have to code in one file. 
* In real world, this is commonly used.
---
## git init 
* initialized repository
---
## parseInt
* Method to change string to int 
* almost same as Number
* parseInt(100, 2) // change 100 to binary 
---
### Ways to check NaN value 
* isNan
* Number
* findIndex