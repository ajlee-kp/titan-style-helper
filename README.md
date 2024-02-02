## To Add New Style

1. Create new style in Titan on the element, give it a name
2. Preview or publish and inspect the element
3. Figure out what its' root style id is by checking console
   
    a. Should be like .ft--<b>e###</b>--root
   
5. Add that to <b>_template-ids.scss</b> as a new variable (probably with same name as style in Titan)
6. Now you can use the `titanClassWithID` mixin to style that element

## Insert new css into Titan

1. run cmd `>> npm i` in repo dir
2. copy the generated css in `style.css`

In Titan Project:
```
|--> Project Settings (gear icon on left side)
   |--> Tools
      |--> Custom Styles
         |+++ Paste the css into the content of the custom style and apply
```
