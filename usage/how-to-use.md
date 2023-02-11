---
description: How do you use it?
---

# 🖥 How to use

Using this library is very simple! Just use the `VT.NET` namespace in any piece of code you want to use the library, as in: `using VT.NET;`

This library is categorized to four different classes to select your operation mode:

* `Filters`: filters the VT sequences from the text
* `Matches`: matches the VT sequences from the text
* `Queries`: queries the VT sequences from the text
* `Splits`: splits the VT sequences from the text

Each of these classes may be referenced statically in your application. Once done, you should be able to call the functions inside them, each with the specific filter for each VT sequence type:

* All VT sequences
* CSI sequences
* OSC sequences
* ESC sequences
* APC sequences
* DCS sequences
* PM sequences
* C1 sequences
