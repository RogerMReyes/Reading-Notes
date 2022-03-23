# CSS Transforms, Transitions, and Animations

## Transforms

- Transforms come in two different settings: **two-dimensional** and **three-dimensional**
- vendor prefixes can be added to help browser support
- two dimensional transforms work on an x and y axis basis
- `rotate` allows you to rotate the element 0 - 360 degrees
- `scale` alters the appeared size of the element
- `translate` will affect the positioning of the element without altering the normal flow
- `skew` is used to distort the element along the x and y axis
- Three dimensional transforms require a **perspective** to transform
- skew is the only transform that is unavailable in a three dimension transformation

## Transitions & Animations

- A change of state can be set off using `:hover`, `:focus`, `:active`, and `:target`
- There are also four popular transition related properties
  - `transitions-property` - determines what will be altered
  - `transition-duration` - duration of how long the transition takes place
  - transition-timing-function` - determines the speed of the transition
  - `transition-delay` - delays the transition by the set value
- Animations extend further with transitions that need to have multiple states
- These points are outlined in a `@keyframes`
- After coding the keyframes it must then be attached to the element

[Return to Code 201 Table of Contents](https://rogermreyes.github.io/Reading-Notes/Code-201-Reading-Notes)
