# generative-art
Experiments in Generative Art with P5.js

Published link: https://jonburdon.github.io/generative-art/

Inspiration and original code:
https://levelup.gitconnected.com/generative-art-3-fundamental-concepts-to-get-you-started-44205dae167b

https://medium.com/@shvembldr/how-to-make-your-first-generative-art-with-p5-js-3f10afc07de2

https://codepen.io/alzajac/pen/LYGmyjb

Color codes from: https://coolors.co/

Color Convertor: https://www.webfx.com/web-design/hex-to-rgb/

P5 Online Editor: https://editor.p5js.org/

The purpose of this project is to explore the P5.js library in terms of a potential tool for generative art.

Examples will show various ways to refactor similar code.

### Notes and programming principles

#### Randomness
Core technique in generative art. Used to effect the curveVertex function of p5js

#### Repetition & Structure
The Triangles are based on a repeating grid of alternating rectangles. When randomness is introduced, the points on the grid can be moved around to produce the interlocking effect.

#### Recursion
The Hypnotic Squares effect uses recursion within the drawrect function. This function calls itself repeatedly with a reducing sized square until the steps are reduced to zero

Future plans:
1. [done] Add interactions so the user can change colours and elements within the art by mouse interactions
2. Unique Project - Sushi Wall
* Staggered Grid
* Grid can be any size
* Different styled circles
* Circles appear in groups, dependent on each other
* Mouse interactions
