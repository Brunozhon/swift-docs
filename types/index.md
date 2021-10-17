# Types

- [Strings](#strings)

## Strings

A string is a basic thing used for storing anything like this:

```swift
"Hello, world!"
```

You can store it in a variable.

```swift
var myString = "Hello, world!"
```

And you can print them!

```swift
print("Hello, world!")
```

You can print multiple things!

```swift
print("Hello, world!", "The second string.", "Each will be separated by a space.")
```

You can append strings.

```swift
var helloPlusWorld = "Hello," + " world!"
helloPlusWorld = helloPlusWorld + "Hello, world!"
print("Hello" + ", " + "world!")
```

Appending strings like that can be time-consuming.

```swift
var aExtremelyExtremelyLongVariableNameInSwift = "Time-consuming"
aExtremelyExtremelyLongVariableNameInSwift = aExtremelyExtremelyLongVariableNameInSwift + " and you can spell it wrong."
aExtramelyExtremelyLongVariableNameInSwift = aExtremelyExtremelyLongVariableNameInSwift + "Not a good way." // Spelling error.
```
