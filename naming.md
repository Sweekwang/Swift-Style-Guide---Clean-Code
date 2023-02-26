# Naming

Naming of variables, functions, arguments, classes, and files should tell you **why it exists**, **what it does**, and **how it is used**. 
If a name requires a comment, then the name does not reveal its intent. If you need to rename anything at any point, free feel to do so.

## General
### Languages
Use US English spelling to match Apple's API.

**Preferred:**
```
let color = "red"
```

**Not Preferred:**
```
let colour = "red"
```

### Intention-Revealing Names

Do not use name that means nothing.

EXAMPLE: 
```
// WRONG - This date doesn't provide any information about WHAT is this date and how you should use
// If you can change the variable name and able to understand the meaning of the variable withput any comment
var date =  NSDate() // Today date

// CORRECT
var todayDate = =  NSDate()
```

## Minimal Imports

Preferred:

Preferred:

Not Preferred:

Not Preferred:
```
// Only using String. SHould use Foundation instead.
import SwiftUI

var deviceModels: [String]
```
<br/>
<br/>

## Functions
Function name must answer `What does function do` or `How would I use the data being returned?`.

