# Change Log
All notable changes to the "vscode-polymer2-snippets" extension will be documented in this file.

## 2.0.0 (2019-09-23)
- Added Snippets
  - `l-properties` - Lit-Element properties by implementing a static properties getter
  - `l-get-styles` - Lit-Element styles in a static styles property
  - `l-get-styles-super` - Lit-Element static styles property with super class
  - `l-firstUpdated` - Lit-Element firstUpdated()
  - `l-shouldUpdate` - Lit-Element shouldUpdate()
  - `l-requestUpdate` - Lit-Element requestUpdate()
  - `l-updateComplete` - Lit-Element `await this.updateComplete;`
  -
- Breaking
  - `p-polymer-customelement` - Removed (out of date)

## 1.0.0 (2018-05-18)
- Added Snippets
  - `p-polymer-element` - Polymer 3 Web Component defintion
  - `p-lit-element` - Lit-Element Web Component definition
  - `p-mixin` - ES6 arrow function subclass return
  - `p-mixin-dedup` - Sharable mixin utilizing Polymer's dedupingMixin
- Breaking
  - `p-polymer-customelement` - Removed (out of date)

## 0.1.0 (2017-11-17)
- Added Snippets
  - `p-hybridbehaviors` - Polymer.mixinBehaviors()
  - `p-properties` - Polymer static get properties()
  - `p-property-observer` - Polymer property w/type + default value + observer
  - `p-property-computed` - Polymer property w/type + computed
- Updated
  - `p-mixin-dedup` - Added Namespace definition to match revised Polymer documentation
  - Minor spacing fixes, add trailing commas on properties

## 0.0.4 (2017-08-21)
- Updated
  - `p-webcomponent`  - Now asks for LowerCaseDashedName and PascalCaseName (save on search/replace)
  - `p-customelement` - Now asks for LowerCaseDashedName and PascalCaseName (save on search/replace)
  - Added JSDoc style documentation for each item (lifecycle callbacks use descriptions use from https://developers.google.com/web/fundamentals/architecture/building-components/customelements?hl=en)

## 0.0.3 (2017-06-07)
- Added Snippets
  - `p-mixin`                  - Boilerplate mixin class
  - `p-mixin-dedup`            - Boilerplate mixin class utilizing Polymer.dedupingMixin()
- Updated
  - `p-property-basic` - added comment block for better Polymer IDE support
  - `p-property-all` - added comment block for better Polymer IDE support
  - `p-webcomponent` - added comment block for better Polymer IDE support

## 0.0.2 (2017-05-24)
- Added Snippets
  - `p-dispatchevent`          -  Fire custom event with this.dispatchEvent();
  - `p-dispatchevent-composed` - Fire custom event through ShadowDOM
  - `p-property-basic`         - Polymer property w/type + default value
  - `p-property-all`           - Polymer property with everything
- Updated
  - `p-customelement` - now implements Polymer.RenderStatus.afterNextRender() in ready() as per Polymer docs
  - `p-webcomponent` - now implements Polymer.RenderStatus.afterNextRender() in ready() as per Polymer docs

## 0.0.1 (2017-05-23)
- Initial release