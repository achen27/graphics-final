# Graphics Final Project 
### Amanda Chen (Period 10)

## Adding Existing MDL Commands
  * light
     * Add a light to the symbol table
     * When calculating diffuse and specular: loop through all the lights
## Modified Existing MDL Commands
  * New Primitive Shapes:
    * Cone
      * cone x y z radius height
      * (x,y,z) is the center of the base
    * Semi-Sphere (Dome)
      * dome x y z r
      * (x,y,z) is the center of the base
      * possibly add a parameter to make quarter-sphere, 3/4 sphere, etc.
    * Cylinder
      * cylinder x y z r h
      * (x,y,z) is center of bottom base
  * Changing Behavior of Vary
    * Adding a parameter to calculate change over time using functions including:
      * Linear, Quadratic, Cubic, etc.
      * Exponential
      * Logrithmic
