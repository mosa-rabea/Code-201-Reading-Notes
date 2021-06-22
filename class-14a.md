# CSS transitions: an introduction
### Transforms:

* ### With CSS3 came new ways to position and alter elements. Now general layout techniques can be revisited with alternative ways to size, position, and change elements. All of these new techniques are made possible by the transform property.

### Let’s start with CSS transitions. Transitions are the grease in the wheel of CSS transforms. Without a transition, an element being transformed would change abruptly from one state to another. By applying a transition you can control the change, making it smooth and gradual
## Transitions & Animations :

#### One evolution with CSS3 was the ability to write behaviors for transitions and animations. Front end developers have been asking for the ability to design these interactions within HTML and CSS, without the use of JavaScript or Flash, for years. Now their wish has come true.
### Hover below:

### In this post I’ll be using transitions in conjunction with transforms. However, transitions can also be used elsewhere where elements change from one style to another (e.g., when a button changes color on hover).

### There are two properties that are required in order for the transition to take effect:

1. transition-property
2. transition-duration



### Here’s the full shorthand sequence. Again, the first two properties are required.


`div {
  transition: [property] [duration] [timing-function] [delay];
}`


### transition-duration (required)
### The transition-duration property specifies the time span of the transition. You can specify in seconds or milliseconds.

### CSS syntax example for transition-duration
  `div {
    transition-duration: 3s;
  }`
### Shorthand example for transition-duration
`div {
  transition: all 3s;
}`
### transition-timing (optional)
### The transition-timing-function property allows you to define the speed of the transition over the duration. The default timing is ease, which starts out slow, quickly speeds up, and then slows down at the end. The other timing options are: linear, ease, ease-in, ease-out, and ease-in-out.

### Here’s an example of the different timing options (used with the transform: translate property):


### For more advanced timing options, you can define a custom timing function with a cubic-bezier.

### CSS syntax example for transition-timing-function
`div {
  transition-timing-function: ease-in-out;
}`
### Shorthand example for transition-timing-function
`div {
  transition: all 3s ease-in-out;
}`
### transition-delay (optional)
### The transition-delay property allows you to specify when the transform will start. By default, the transition starts as soon as it is triggered (e.g., on mouse hover). However, if you want to transition to start after it is triggered you can use the transition delay property.

CSS transforms: an introduction
Now that we reviewed how to make smooth and gradual transitions, let’s look at CSS transforms - how to make an element change from one state to another. With the CSS transform property you can rotate, move, skew, and scale elements. (This post will only cover 2D transforms, but stay tuned for future blog posts on 3D transforms.)

Transforms are triggered when an element changes states, such as on mouse-hover or mouse-click. The examples in this post will demonstrate transforms on mouse-hover.

For simplicity, I’ll only be using the unprefixed versions in my examples. However, you may want to include prefixes to ensure it works in modern browsers.

scale
The scale value allows you to increase or decrease the size of an element.

For example, the value 2 would transform the size to be 2 times its original size. The value 0.5 would transform the size to be half its original size.