# Topics for section 7 

- Understanding the `background` property
- image & background images
- Gradients
- Filters

## Notes

In a background property you can add `background-color`, repeat, no-repeat and other image attributes, but in the background-image property you are only allowed to add image.

### background-size

`background-size` setting one value sets it to the with and repeats. your setting width and height `auto` would take the full amount of space. `cover` finds which part of container (width or height) which aspect ratio to take. cover makes sure there is no white space.
`contain` makes sure that the image dosnt fill it insures the entire image is available.
`background-repeat` defines if it should repeat the image on Y or X axises

### background-position

`background-position` you can define a value for it. 
first value defines the x axis and second value y axis
With percentage value you can define how much of excess space is filled.
`center` will perfectly center the image 50% on both axis is set to crop
it can also be set with `left` `top` where ever you don't want cropping

### background

`background` is a shorthand property for: 
 - `background-color`: set a background color.
 - `background-image`: set one or more background image and has 3 properties that it apply
 - `background-position`: set initial position, relative to background position layer => only applies to `background-image`
 - `background-size`: sets size of background image =>  only applies to `background-image`
 - `background-repeat`: defines how background images are repeated => only applies to `background-image`
 - `background-origin`: set background positioning area defined by => `background-position`

 `background-clip` `background-attachment` `background-color` 

### background-origin
`background-origin` content-box the content without border or padding
the default is padding-box 
border-box filles the image
`background-clip` we define where the image should be clipped
`background-attachment`  for a fixed element that we can scroll through

### background shorthand
`background: url(#) left 10% bottom 20%/cover`
=
```
background-image:  url("freedom.jpg");
    background-size: cover;
    background-position: left 10% bottom 20%;
```
we can also add no-repeat for repeat

as well as origin and repeat in that order and attachment

`height:100%` it will use the origin hight not its container
setting it as inline-block it will use its height

`background-image` is outside the document flow.

`inline-image` white space can be removed with `vertical-align: top;`

### gradients 
- gradients are treated as images

### radial gradients
- shaped as an ellipse and will start at the middle
- it can also be set as a circle 
- you can also change its position with `at`
- you can set the position 
- they can be stacked as well

you can pass linear-graidant to your image which are stacked
`background: linear-gradient(to top, rgba(80,60,18,0.6) 10%, transparent), url('image') left 20% cover no-repeat border-box,`

## filters
`filter` used to change the content i.e `blur`, `gray-scale` etc.

## svg
`fill` `stroke` and `stroke-width` are used to style svg