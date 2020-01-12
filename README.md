# V UI 0.0.1

<img src='https://raw.githubusercontent.com/vlang/ui/master/examples/users/screenshot.png' width=712>


**This is pre-alpha software.**

V UI is a cross-platform UI toolkit for Windows, macOS, Linux, and soon Android, iOS and the web (JS/WASM).
V UI uses native widgets on Windows and macOS, on all other platforms the widgets are drawn by V UI.
Right now only the non-native widgets are available.

This is a very early version of the library, lots of features are missing (layouts, certain widgets, etc),
lots of things will change.

There will be a declarative version of the API, similar to SwiftUI.

V UI is licensed under GPL3. A commercial license will be available. Open-source projects will have access to the commercial license for free. Every single feature will be open-sourced right away and available under both licenses. At some point in the future the library will be relicensed under MIT.

### Installation
```bash
git clone https://github.com/vlang/ui
ln -s /path/to/ui ~/.vmodules/ui
```

### Dependencies

Binaries built with V UI will have no dependencies.

But to develop with V UI you need to install `glfw` and `freetype`. `glfw` dependency will soon be removed.
