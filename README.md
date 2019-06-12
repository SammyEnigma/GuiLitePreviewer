# GuiLite Previewer - WYSIWYG extension for GuiLite 
- [GuiLite](https://github.com/idea4good/GuiLite) is the smalles/simplest/stablest GUI library for all platforms, it has only 5,000 line C++ code.
- GuiLite Previewer is a Visual Studio Code extension, could extract GUI information from C++ code and preview GUI at preview page(What you see is what you get)
- No need for drag-and-drop widgets, Developer could do all things(e.g. code/design/build/run/debug your GuiLite App) by coding in VS Code
- No need for special GUI editor(e.g. Qt designer)
- No need for Extensible Markup Language(e.g. xml, xaml)

## Demo
![demo](demo.gif)

## How to build GuiLite Previewer?
- Download npm, and install
- `cd GuiLitePreviwer`
- `npm install` 
- Open this project in VS Code 1.25+
- `F5` to start debugging

## How to use GuiLite Previewer?
1. Open your source code(e.g. test.cpp) with VS Code
2. `ctrl + shift + p`, and input `GuiLite: preview layout`
3. You will see your GUI layout in preview page
 