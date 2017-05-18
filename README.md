# Sublime Text 2/3 - CMake Package #

[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/zyxar/Sublime-CMakeLists?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

* Simple auto-indentation support.
* Syntax highlighting, based on [CMake 3.0][1].
* Basic snippets.
* Basic keybindings.

## Available Snippets

* `cmake_minimum_required`
* `foreach`
* `if`
* `option`
* `project`
* `set`
* `while`

If an argument to a command is optional, it is selectable when you tab through
the snippet, and you can then press escape to remove the optional argument.

## Available Key Bindings

* Select a word, and type the dollar-sign character (`$`) to wrap the selection
  as a [variable substitution][3]. The newly inserted text will stay selected, 
  so that you can press the double-quotes character (`"`) to enclose the 
  selection in double-qoutes too. Press tab to get out of the selection if you 
  don't want  double-quotes.
* Select a word, and type the less-than character (`<`) to wrap the selection
  as a [generator expression][2] with an argument.
* Select a word, and type the greater-than character (`>`) to wrap the selection
  as a [generator expression][2] without an argument.

[1]: https://cmake.org/cmake/help/v3.0/manual/cmake-language.7.html
[2]: https://cmake.org/cmake/help/v3.0/manual/cmake-generator-expressions.7.html
[3]: https://cmake.org/cmake/help/v3.0/manual/cmake-language.7.html#variable-references
