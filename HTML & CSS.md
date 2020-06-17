## OOCSS (Object Oriented Cascading Style Sheets)
The purpose of **OOCSS** is to encourage code reuse, ultimately, faster and more efficient stylesheets that are easier to add and maintain. It works based in two main principles, such as

- Separation of Structure from Skin (Group common styles and add class for them to reuse).
- Separation of Cotainers from Content (Don't write the parent based styles to elements).

**Example 1:**
```css
Before Separating the Structure and Skin
.button {
  width: 200px;
  height: 50px;
  padding: 10px;
  border: solid 1px #ccc;
  background: linear-gradient(#ccc, #222);
  box-shadow: rgba(0, 0, 0, .5) 2px 2px 5px;
}

.box {
  width: 400px;
  overflow: hidden;
  border: solid 1px #ccc;
  background: linear-gradient(#ccc, #222);
  box-shadow: rgba(0, 0, 0, .5) 2px 2px 5px;
}

.widget {
  width: 500px;
  min-height: 200px;
  overflow: auto;
  border: solid 1px #ccc;
  background: linear-gradient(#ccc, #222);
  box-shadow: rgba(0, 0, 0, .5) 2px 2px 5px;
}

After Separating the Structure and Skin:

.button {
  width: 200px;
  height: 50px;
}

.box {
  width: 400px;
  overflow: hidden;
}

.widget {
  width: 500px;
  min-height: 200px;
  overflow: auto;
}

.skin {
  border: solid 1px #ccc;
  background: linear-gradient(#ccc, #222);
  box-shadow: rgba(0, 0, 0, .5) 2px 2px 5px;
}
```

**Example 2:**
```css
Before Separating Containers and Content

.sidebar h3 {
  font-family: Arial, Helvetica, sans-serif;
  font-size: 2em;
  line-height: 1;
  color: #777;
  text-shadow: rgba(0, 0, 0, .3) 3px 3px 6px;
}
.footer h3 {
  font-family: Arial, Helvetica, sans-serif;
  font-size: 1.5em;
  line-height: 1;
  color: #777;
  text-shadow: rgba(0, 0, 0, .3) 2px 2px 4px;
}

After Separating Containers and Content (Short hand property used)

h3 {
  font: 1.5em/1 Arial, Helvetica, sans-serif;
  color: #777;
  text-shadow: rgba(0, 0, 0, .3) 2px 2px 4px;
}
.sidebar h3{
  font-size: 2em;
}
```
**Guidelines to implement OOCSS:**
- Avoid the descendent selector ( don't use .sidebar h3 as default style ).
- Avoid ID's as selectors.
- Avoid attaching classes to elements in your stylesheet.
- Except some rare cased, avoid using !important.
- Use Grids and Flex-Box to create layout.
- Use moduler class names ( **my-20** to apply margin top and Bottom, **di** for display: inline property ). 


## BEM (Block, Element and Modifier)
- **Block**: Block are made up of multiple elements / sub blocks and block name shoud be unique throughout the project ( like header, main, footer, aside etc ).
```css
.header{}
.section{}
.form{}
.footer{}
```
- **Element**: Element represents simple html elements and element names should be unique within block ( like header-logo, header-contact, header-emain etc).
```css
.header-logo{}
.header-email{}
.footer-version{}
.form-row{}
.form-group{}
```
- **Modifier**: Modifier represents the different state of an Element (like normal background color and onhover background color).
```css
.header.header-dark{} or .header.dark{}
.btn.btn-primary{} or 
```
<!--stackedit_data:
eyJwcm9wZXJ0aWVzIjoiZXh0ZW5zaW9uczpcbiAgcHJlc2V0Oi
BnZm1cbiIsImhpc3RvcnkiOlstMTk1NjQwNDcwMSwtODEwMjA1
NDIxLC02Mzc3OTM3NTksLTEzODgwMzkzMywtMjA3MzY2NTMyMy
wtNDQxMTM4NDUwLDE2NDY1ODUwMjQsLTE3Mjg4MTkxOTMsLTE4
NzE1OTIxNDRdfQ==
-->