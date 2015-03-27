# Pure CSS - Parallel park
Pure CSS - Parallel park is step by step tutorial on how to perfect parallel park.

![image](http://s24.postimg.org/iqjkl0mwz/parallel_park_gif.gif)

[Click here to see a live demo](teles.github.io/pure-css-parallel-park/) or love it on [codepen](codepen.io/teles/pen/gbKeLR).

## Dependences
To generate the css file from the sass code you will only need compass. If you don't have it, [install it](http://compass-style.org/install/)

## Running the project

To compile the sass project use `compass compile`.

To watch changes in the project use `compass watch`, everytime you change something in the sass code running `grunt watch` the css will be compiled again.

## Folders structure
The sass code is divided in folders, which folder has its own purpose. 
In helpers folder there are stylesheets which don't generated css.
In core folder there are styles for html tags and typo.
In components folder you will find the components like car, park and breadcrumbs.

## "How do you animate the car without using javascript?"
The animations are all css3, they are made using keyframes, but the interactions are using a simple combination beetwen hidden inputs and labels.
Happens like this: when the user checks the start button he is checking a hidden input and the first animations starts after it, so it happens in the steps 2, 3 and finish. Quite simple :)


