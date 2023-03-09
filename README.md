# CSS_animation
## Transforms
Transforms are a newer CSS technology that allow us to move elements on the page by translating them, rotating them, scaling them, and more. Sometimes these transforms are used in isolation, but they're more commonly found in conjunction with CSS animations

- transform: CSS transforms change the shape and position of the affected content and allow you
to translate, rotate, scale, and skew elements.

A transformation is an effect that lets an element change shape, size and position. Here are a few of the methods that can be values of transform property:

- translate - The translate() method moves an element from its current position. For example, if you give an element the rule transform: translate(50px,100px);, the element will be 50 pixels to the right and 100 pixels down.

- rotate - The rotate() method rotates an element clockwise or counter-clockwise according to a given degree. For example, if you give an element the rule transform: rotate(90deg);, the element will rotate 90° clockwise.

- scale - The scale() method increases or decreases the size of an element (according to the parameters given for the width and height). For example, if you give an element the rule transform: scale(2,3);, the element will scaled 200% horizontally and 300% vertically.

## Transitions
Transitions allow us to perform animations without using JavaScript.

- Transition - They provide a way to set and control animation speed when changing CSS properties. Instead of having property changes take effect immediately, you can cause the changes in a property to take place over a period of time

## Animations
CSS property called animation which we can use to define custom animations purely using CSS. CSS animations make it possible to create complex animation transitions from one CSS style configuration to another.

To create our animation ..... we need two things: an animation property on the relevant HTML element, and a set of keyframes that describe the animation we're trying to build

ex: animation: shapeshift 6s infinite

The 6s indicates how long it should take to complete our animation, while the infinite ensures that the animation will play on loop, rather than stopping after one cycle

This is the basic syntax for defining custom animations using keyframes. Inside of the curly braces, we can define several different keyframes, which describe the state of our div at different points in the animation

