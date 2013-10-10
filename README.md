sass-bootcamp
=============

Sass Bootcamp @PDXSass

Slides available at http://goo.gl/NOjAuT

See also this excellent tutorial at: http://sass-lang.com/tutorial.html

The idea here is to take the main.css from the HTML5 Boilerplate, created by Initializr, and begin to refactor it into Sass.

Each branch reveals a new example of refactoring CSS3 into Sass.

1. After cloning the repository into your local instance, begin with branch "first-stylesheet":

   git checkout first-stylesheet

   This will show how the css/main.css was renamed sass/main.scss

   Then in the project root directory, run from the command line: 
   
   sass --watch sass:css 

   This watches all .scss files in the sass directory and processes them into their .css counterparts in the css directory.


2. git checkout ex1-variables

   Refactors colors into variables.

3. git checkout ex2-nesting

   Refactors a nav block into a nested Sass block.

4. git checkout ex3-math

   Refactors a commented formula into an actual mathmatic formula using Sass.

5. git checkout ex4-functions

   Refactors the $dark-orange variable to use the darken() function instead of an assigned hex value.

6. git checkout ex5-mixins

   Refactors a border-box declaration with browser specific declarations into a mixin using arguments and interpolation.

7. git checkout ex6-import

   Removes variables and mixins into their own files and uses @import to include them in the main.scss file.


Last updated by Amber Himes, October 10, 2013, at 10:40 AM PDT. 


