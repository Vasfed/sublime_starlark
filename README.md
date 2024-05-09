# SublimeText Starlark syntax

Minimal package to get syntax highlighting working for [Starlark](https://bazel.build/rules/language)([on github](https://github.com/bazelbuild/starlark))
in [Sublime Text](https://www.sublimetext.com/).

![highlight example](/media/example.png?raw=true "highlighting example")

## Installation

The recommended way is to use [Package Control](https://packagecontrol.io/installation) to automatically receive the latest updates and make the entire process much simpler.

### Package Control Installation
(this should work once [pull request is accepted to Package Control](https://github.com/wbond/package_control_channel/pull/8916))

1. Open Sublime Text and press `Shift+Ctrl+P` (`Cmd+Shift+P` on Mac).
2. Type `install` and press enter.
3. Another text box should appear, type `Starlark` and you should see this plugin highlighted. Press Enter to install it.

### Manual installation

1. Download this Git Repository's master branch as a .zip file. (Or you can download the latest release.)
2. Navigate to `Preferences > Browse Packages...` (or `Settings -> Browse Packages...`)
3. Put the folder from the .zip into the location that was opened.
4. Restart Sublime.

## Usage

Use `Set syntax: Starlark` to apply to current file. Newly opened files with `.star`/`.bzl`(and some others, see [starlark.sublime-syntax](starlark.sublime-syntax)) should already have syntax applied.

## See also
- https://github.com/google/starlark-go/blob/master/syntax/grammar.txt
- https://github.com/bazelbuild/starlark/blob/master/spec.md
- https://github.com/phgn0/vscode-starlark
