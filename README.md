# Polymer 2 Snippets for Visual Studio Code

*WORK IN PROGRESS* This extension for Visual Studio Code adds snippets for Polymer 2 for JavaScript and HTML.

## Usage
Type part of a snippet, press `enter`, and the snippet unfolds.

### JavaScript Snippets
```javascript
p-customelement           // Polymer Custom Element
p-lifecycle-constructor   // constructor()
p-lifecycle-connected     // connectedCallback()
p-lifecycle-disconnected  // disconnectedCallback()
p-lifecycle-attrchanged   // attributeChangedCallback()
p-lifecycle-ready         // Polymer specific ready()
p-dispatchevent           // this.dispatchEvent();
p-observers               // Polymer static get observers()
```

### HTML Snippets
```html
p-webcomponent            // Polymer Web Component
p-slot                    // <slot name="">
p-dom-repeat-inside       // dom-repeat inside Polymer managed template
p-dom-if                  // dom-if 
```

Alternatively, press `Ctrl`+`Space` (Windows, Linux) or `Cmd`+`Space` (OSX) to activate snippets from within the editor.

## Installation

1. Install Visual Studio Code 1.10.0 or higher
2. Launch Code
3. From the command palette `Ctrl`-`Shift`-`P` (Windows, Linux) or `Cmd`-`Shift`-`P` (OSX)
4. Select `Install Extension`
5. Choose the extension
6. Reload Visual Studio Code
