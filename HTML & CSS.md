# HTML and CSS docs

## BEM and ABEM
- BEM   : Block Element and Modifier
-  ABEM: Atomic Block Element and Modifier

BEM (Block Element and  Modifier) is popular naming convention for CSS that makes CSS easier to maintain. 

BEM's syntax:
```css
block-name__element-name--modifier-name{}
card{}
card__header{}
card--active{}
```

ABEM's syntax:
```css
[a/m/o]-blockName__elementName -modifierName{}
o-card{}
m-card__header{}
-active{}
```
- Atoms (a):  represents the simple components that contains single element like button, form input etc.
- Molecules (m): represents the groups of elements or components like form group contains label and input field.
- Organisms (o): represents large complex components made up of many molecules and atom components.


<!--stackedit_data:
eyJwcm9wZXJ0aWVzIjoiZXh0ZW5zaW9uczpcbiAgcHJlc2V0Oi
BnZm1cbiIsImhpc3RvcnkiOlstOTkzNjY5NzMyLDE2NDY1ODUw
MjQsLTE3Mjg4MTkxOTMsLTE4NzE1OTIxNDRdfQ==
-->