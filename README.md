<div align="center">

# 🎁 Swift Basics: Optionals

**A concise, runnable Swift Playground exploring optional types**

![Platform iOS](https://img.shields.io/badge/Platform-iOS-black?style=flat-square&logo=apple)
![Swift](https://img.shields.io/badge/Swift-FA7343?style=flat-square&logo=swift&logoColor=white)
![Playground](https://img.shields.io/badge/Xcode-Playground-147EFB?style=flat-square&logo=xcode&logoColor=white)
![Stars](https://img.shields.io/github/stars/ahmetbostanciklioglu/Optionals?style=flat-square&color=6E48AA)
![Last Commit](https://img.shields.io/github/last-commit/ahmetbostanciklioglu/Optionals?style=flat-square&color=4776E6)

</div>

## 📖 Overview

Optionals are Swift's way of expressing that a value may be present or may be absent (`nil`). Declaring a type as optional (for example `String?` or `Int?`) tells the compiler the variable can either hold a value of that type or hold nothing at all, which helps you handle missing data safely instead of crashing.

This repository is a small, runnable Xcode Playground that demonstrates the concept with a couple of short examples. It is meant as a concise learning reference rather than a full application.

## 📚 What it covers

- Declaring an optional variable and assigning `nil` to it (`var optionalString: String? = nil`).
- Reassigning a value to an optional after it was initialized as `nil`.
- Declaring optional stored properties inside a class, including one initialized to `nil`.
- Setting an optional property through an initializer.
- Assigning a value to an optional property on an existing instance.

## 🚀 Getting Started

```bash
git clone https://github.com/ahmetbostanciklioglu/Optionals.git
cd Optionals
```

Unzip `Optionals.playground.zip`, open `Optionals.playground` in Xcode, and run the playground to see each line evaluated in the results sidebar.

## 📋 Requirements

- Xcode 12 or later
- Swift 5+
- iOS playground target (as configured in `contents.xcplayground`)

## 🧑‍💻 Author

**Ahmet Bostancıklıoğlu** — [@ahmetbostanciklioglu](https://github.com/ahmetbostanciklioglu) · ahmetbostancikli@gmail.com

> ⭐ If this helped you, consider giving the repo a star!
