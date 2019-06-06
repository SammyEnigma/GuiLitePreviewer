# GuiLite Previewer - 所code即所得
- [GuiLite](https://gitee.com/idea4good/GuiLite)是最轻量，最简单，最稳定的GUI库，它只有5千行代码
- GuiLite Previewer是一个Visual Studio Code插件，它可以自动读取源代码的GUI布局信息，并实时显示在“预览”页面上
- 有了这个插件，开发者可以完全沉浸在Visual Studio Code中，完成所有的开发工作（例如：代码，UI编辑，编译，运行，调试）
- 通过这种方式，各种GUI库，无需再开发各自独有的UI编辑工具（或IDE）

## Demo
![demo](demo.gif)

## 如何编译?
- Download npm, and install
- `cd GuiLitePreviwer`
- `npm install` 
- Open this project in VS Code 1.25+
- `F5` to start debugging

## 如何预览你的GUI?
1. Open your source code(e.g. GUiLitePreviewer/UIcode.cpp) with VS Code
2. `ctrl + shift + p`, and input `GuiLite: preview layout`
3. You will see your GUI layout in preview page