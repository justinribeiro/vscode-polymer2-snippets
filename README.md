# Polymer 2 Snippets for Visual Studio Code

This extension for Visual Studio Code adds snippets for Polymer 2 for JavaScript and HTML.

[![Visual Studio Marketplace](https://vsmarketplacebadge.apphb.com/installs-short/justinribeiro.Polymer2Snippets.svg
?style=flat-square)](https://marketplace.visualstudio.com/items?itemName=justinribeiro.Polymer2Snippets)
[![Current Release](http://vsmarketplacebadge.apphb.com/version/justinribeiro.Polymer2Snippets.svg
?style=flat-square)](https://github.com/justinribeiro/vscode-polymer2-snippets/releases)

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
p-dispatchevent           // Fire custom event with this.dispatchEvent();
p-dispatchevent-composed  // Fire custom event through ShadowDOM
p-observers               // Polymer static get observers()
p-property-basic          // Polymer property w/type + default value
p-property-all            // Polymer property with everything
```

### HTML Snippets
```html
p-webcomponent            // Boilerplate Polymer Web Component
p-mixin                   // Boilerplate mixin class
p-mixin-dedup             // Boilerplate mixin class utilizing Polymer.dedupingMixin()
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
