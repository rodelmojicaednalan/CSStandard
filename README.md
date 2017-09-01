# CSStandard

## Requirements
* NodeJS for package manager

## Covered Topics
* SASS npm install -g node-sass
* LESS npm install -g autoless
* SMACSS
* BEM

## Command we will use
* node-sass -w src -o dist
* autoless src dist


**What is BEM (Block, Element, Modifier)**
```
block__element--modifier
block__element
block--modifier
```
**What is SMACSS (Scalable and Modular Architecture CSS)**
```
base - applies to HTML, no class/ID selectors
layout - big page sections
modules - encapsulated models and re-usable
state - overrides the default
themes - optional , if theming is needed
```

**CSS Priority**
```
li            {...}  /* a=0 b=0 c=1 -> specificity =   1 */
ul li         {...}  /* a=0 b=0 c=2 -> specificity =   2 */
ul ol li      {...}  /* a=0 b=0 c=3 -> specificity =   3 */
li.red        {...}  /* a=0 b=1 c=1 -> specificity =  11 */
ul ol li.red  {...}  /* a=0 b=1 c=3 -> specificity =  13 */
#list         {...}  /* a=1 b=0 c=0 -> specificity = 100 */
```
