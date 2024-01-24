# Fruit Slicing Frenzy

This is a loose clone of the mobile game 'Fruit Ninja' written in HTML/CSS/JavaScript to satisfy a final project constraint of only using CSS Animations to animate content.  
JavaScript was allowed to define spawning and game logic for this project.

&nbsp;

There is a live demo of this project hosted using GitHub Pages at the bottom of this README.

&nbsp;
&nbsp;


## HIGHLIGHTS

Aside from satisfying the project constraints, here are a few notable highlights about this project :
- Fruits are animated with real projectile physics using kinematic equations inside CSS `calc()` statements.
- Screenshake animation implemented in CSS. 
- DOM update optimizations.
- Detailed documentation included in the source files.

&nbsp;
&nbsp;


## PYTHON FILES

There are 2 python files : `generate-classvars2.py` and `generate-stage-shake-css.py` which are used to generate the CSS classes needed to animate the entities.

&nbsp;
&nbsp;


## DOM UPDATE OPTIMIZATIONS

This project tries to optimize DOM updates by first hiding the node to update before applying changes to the element then showing the updated element on the DOM which should result in fewer DOM updates overall.

&nbsp;
&nbsp;


## LIVE DEMO

[Click here to goto the live demo](https://bingjetli.github.io/fruit-ninja-clone-js/)
