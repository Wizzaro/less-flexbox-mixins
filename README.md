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
.flex-direction([@value]) //default @value: row
.flex-direction-row();
.flex-direction-row-reverse();
.flex-direction-column();
.flex-direction-column-reverse();
```
#### Flex wrap
```
.flex-wrap([@value]); //default @value: nowrap
.flex-wrap-nowrap();
.flex-wrap-wrap();
.flex-wrap-wrap-reverse();
```
#### Flex flow
```
.flex-flow([@direction][, @wrap]); //default @direction: row, @wrap: nowrap
.flex-flow-row-nowrap();
.flex-flow-row-wrap();
.flex-flow-row-wrap-reverse();
.flex-flow-row-reverse-nowrap();
.flex-flow-row-reverse-wrap();
.flex-flow-row-reverse-wrap-reverse();
.flex-flow-column-nowrap();
.flex-flow-column-wrap();
.flex-flow-column-wrap-reverse();
.flex-flow-column-reverse-nowrap();
.flex-flow-column-reverse-wrap();
.flex-flow-column-reverse-wrap-reverse();
```
#### Justify content
```
.justify-content([@value]); //default @value: flex-start
.justify-content-flex-start();
.justify-content-flex-end();
.justify-content-center();
.justify-content-space-between();
.justify-content-space-around();
```
#### Align items
```
.align-items([@value]); //default @value: stretch
.align-items-flex-start();
.align-items-flex-end();
.align-items-center();
.align-items-baseline();
.align-items-stretch();
```
#### Align content
```
.align-content([@value]); //default @value: stretch
.align-content-flex-start();
.align-content-flex-end();
.align-content-center();
.align-content-space-between();
.align-content-space-around();
.align-content-stretch();
```
### Mixins for the Item Element
#### Align self
```
.align-self([@value]); //default @value: auto
.align-self-auto();
.align-self-flex-start();
.align-self-flex-end();
.align-self-center();
.align-self-baseline();
.align-self-stretch();
```
#### Order
```
.order([@int]); //default @int: 0
```
#### Flex grow
```
.flex-grow([@int]); //default @int: 0
```
#### Flex shrink
```
.flex-shrink([@int]); //default @int: 0
```
#### Flex basis
```
.flex-basis([@value]); //default @value: auto
```
#### Flex
```
.flex([@flex-grow][, @flex-shrink][, @flex-basis]); //default @flex-grow: 0, @flex-shrink: 0, @flex-basis: auto
```
## Licence

Licensed under MIT.
