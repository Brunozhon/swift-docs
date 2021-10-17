# Initalizers for `Text`

- [init(\_:)](#init_)
- [init(verbitm:)](#initverbitm)

## init(\_:)

`init(_:)` displays localized text. For example, an app with English and Chinese localization with this code:

```swift
Text("Hello!")
```

will display "Hello!" in English and other languages except Chinese.

## init(verbitm:)

`init(verbitm:)` displays unlocalized text.

```swift
Text(verbitm: "pencil") // Displays pencil in all languages.
Text("pencil") // Displays pencil, localized based on the app's localization.
```
