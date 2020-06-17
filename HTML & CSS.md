# HTML and CSS docs

## BEM and ABEM
- BEM   : Block Element and Modifier
-  ABEM: Atomic Block Element and Modifier

BEM (Block Element and  Modifier) is popular naming convention for CSS that makes CSS easier to maintain. 

BEM's syntax:
```css
block-name__element-name--modifier-name{}

Block-name looks like 'card'
Element-name looks like 'card__header'
Modifier-name looks like 'card__header--active'
```

ABEM's syntax:
```css
[a/m/o]-blockName__elementName -modifierName
'A' stands for Atom which represents the simple components that contains single element like button, form input etc.
'M' stands for molecule which represents the groups of elements or components like form group contains label and input field.
'O' stands for Organism which represents large complex components made up of many molecules and atom components.
```
<!--stackedit_data:
eyJwcm9wZXJ0aWVzIjoiZXh0ZW5zaW9uczpcbiAgcHJlc2V0Oi
BnZm1cbiIsImhpc3RvcnkiOlstMTg3MTU5MjE0NF19
-->