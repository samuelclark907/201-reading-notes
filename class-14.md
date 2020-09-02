# CSS Transforms

- The `transform` property comes in two different settings, two-dimensional and three-dimensional. Each of these come with their own individual properties and values.

## Transform Syntax

- The transform property followed by the value. ex. `transform: scale(1.5);`

## 2D Transforms

- Elements may be distorted, or transformed, on both a two-dimensional plane or a three-dimensional plane.

- Two-dimensional transforms work on the x and y axes, known as horizontal and vertical axes. 

- Three-dimensional transforms work on both the x and y axes, as well as the z axis.

- `Rotate` - The rotate function rotates the element clockwise by an angle defined with a single value.

- The `skew` function tilts the element by using one or two angle values.

- The `scale` function resizes the entire element when using one or two unitless numbers.

# Transitions and Animations

- You have the potential to alter the appearance and behavior of an element whenever a state change occurs.

- Allow the appearance and behavior of an element to be altered in multiple keyframes.

- The easiest way for determining styles for different states is by using the :hover, :focus, :active, and :target pseudo-classes.

## Transitional Property 

- The `transition-property` determines exactly what properties will be altered in conjunction with the other transitional properties.

- Not all properties may be transitioned, only properties that have an identifiable halfway point.

## Transion Duration

- The duration in which a transition takes place is set using the `transition-duration` property.

- When transitioning multiple properties you can set multiple durations, one for each property.

- If multiple properties are being transitioned with only one duration value declared, that one value will be the duration of all the transitioned properties.

# Animations

- When more control is required, transitions need to have multiple states is where animations take over.

## Animation Keyframes

- To set multiple points at which an element should undergo a transition, use the `@keyframes` rule.

- The `@keyframes` rule includes the animation name, any animation breakpoints, and the properties intended to be animated.

## Animation Name

- Once the keyframes for an animation have been declared they need to be assigned to an element.  

- The `animation-name` property is used with the animation name, identified from the `@keyframes rule`, as the property value. The animation-name declaration is applied to the element in which the animation is to be applied to.

## Customizing Animations

- Animations also provide the ability to further customize an element’s behavior, including the ability to declare the number of times an animation runs, as well as the direction in which an animation completes.












