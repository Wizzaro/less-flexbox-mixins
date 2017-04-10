# Wizzaro Less Flexbox Mixins

## Basic information

This is a set of less mixins for CSS Flexible Box Layout.
For more information about layout look on: https://www.w3.org/TR/css-flexbox-1/

Browsers Support:
- Chrome 21+
- Firefox 18+
- Opera 12.1+
- Safari 6.1+
- Edge
- IE10+

This mixins supports old browsers flexbox syntax.

## Install
`bower install wizzaro-less-flexbox-mixins`

## Usage mixins
### Mixins for the Parent Element
#### Display
```
.display-flex();
.display-inline-flex();
```
#### Flex direction
```
.flex-direction([@value: row]);
```
#### Flex wrap
```
.flex-wrap([@value: nowrap]);
```
#### Flex flow
```
.flex-flow([@direction: row][, @wrap: nowrap]);
```
#### Justify content
```
.justify-content([@value: flex-start]);
```
#### Align items
```
.align-items([@value: stretch]);
```
#### Align content
```
.align-content([@value: stretch]);
```
### Mixins for the Item Element
#### Align self
```
.align-self([@value: auto]);
```
#### Order
```
.order([@int: 0]);
```
#### Flex grow
```
.flex-grow([@int: 0]);
```
#### Flex shrink
```
.flex-shrink([@int: 0]);
```
#### Flex basis
```
.flex-basis([@value: auto]);
```
#### Flex
```
.flex([@flex-grow: 0][, @flex-shrink: 0][, @flex-basis: auto]);
```
## Licence

Licensed under MIT.
