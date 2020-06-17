# HTML and CSS docs

## OOCSS (Object Oriented Cascading Style Sheets)
The purpose of **OOCSS** is to encourage code reuse, ultimately, faster and more efficient stylesheets that are easier to add and maintain. It works based in two main principles, such as

- Separation of Structure from Skin (Group common styles and add class for them to reuse).
- Separation of Cotainers from Content (Don't write the parent based styles to elements).

#### Example:
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
```

<!--stackedit_data:
eyJwcm9wZXJ0aWVzIjoiZXh0ZW5zaW9uczpcbiAgcHJlc2V0Oi
BnZm1cbiIsImhpc3RvcnkiOlsxOTQxODY5ODE5LC0xMzg4MDM5
MzMsLTIwNzM2NjUzMjMsLTQ0MTEzODQ1MCwxNjQ2NTg1MDI0LC
0xNzI4ODE5MTkzLC0xODcxNTkyMTQ0XX0=
-->