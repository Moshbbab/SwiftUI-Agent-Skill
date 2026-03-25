# SwiftUI Text Patterns Reference

## Table of Contents

- [Text Initialization: Verbatim vs Localized](#text-initialization-verbatim-vs-localized)

## Text Initialization: Verbatim vs Localized

Use the correct initializer based on whether the string should be localized.

```swift
// Localized - "Save" becomes the localization key, auto-exported to Localizable.strings
Text("Save")

// Non-localized - always displays "pencil", regardless of locale
Text(verbatim: "pencil")
```
