# Current Documentation of Rusted-Script.

## If Statements.

  

### Examples

```css

var x = 30

if x == 1 * 30 /* if 30 equals 30 ... */

then /* do something (if 30 equals 30)*/ elif 0 * 30 then /* do something (if 0 is true) */

  

if 15 == 7 /* if 15 equals 7 */

then /* do something (if 15 equals 7) */ else /* do something (if 15 DOES NOT equal 7) */

```

Note: When dealing with ``` if ``` Statements, if you wish to compare two values and see if they are equal or not. You must include a double "="

Example

Correct:

```css

if 15 == 14

```

Incorrect

```css

if 15 = 14

```

## Variables and data types

  

### Explanation

Variable (noun)

**:** a quantity that may assume any one of a set of values

### Variable data types

#### boolean

```css

var varible_name = true

var varible_name = false

```

  

#### String

```css

var my_name = "Oak Atsume"

var varible_name = "Blah Blah Blah"

```

### Integer

```css

var my_age = 16

var variable_name = 69

```

Haha, funny number.

Extra: Variables are stored in the system's memory and be used to store and retreat values at any time in a script.

  

  

## Comments

```css

// This is a comment

# This is a comment

/* This is a comment

```

## Modules

Not Included still!

  

  

## External file sourcing.

  

### Description.

If you want to source data (function, variables) from another ```.rusted``` file. You can use the ``` use()``` function to import/source a file.

  

### Examples

  

#### File_one.rusted

```css

var my_password = "This is my super safe password!"

```

#### File_two.rusted

Source the "my_password" varible to the second one.

```css

use("File_one.rusted")

```

  

## Math

  

### Adding

```css

var x = 4 + 4

# x = 8

```

or

```css

if x == 4 + 4

then

# Do something

else

# Do something

```
