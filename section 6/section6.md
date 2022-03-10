`position`  `static` is the default for the document flow from top to bottom from html => body => etc.

`postion` 
    => `static` 
    `absolute`
    `relative`
    `fixed`
    `sticky`
we are specifying we want to change the position. They can be position in all 4 directions 
you are changing their position in the document flow defining the positioning context

apply changes to position will only take place if they are different from static

for inline elements changing the width has no impact 

fixed naviagtion can be done by setting the position to fixed making the element stick to the viewport 

`z-index` adding a index to element without a position will not change the index position
where the elements sits affects the z-index that you place div1 => div2 div1 sits above it 

`position: absolute` position context if the parent dosnt have anything applied it will be the HTML if we have a position ancestor it will be the set to it
`relative` does not take the element from the document context
`fixed` always applied to the html

`sticky`  will also need a directional property like `top` ,`bottom` etc.
elements zindex canot be less than the parent

each element that is fixed have their own z-index general order 

## document flow 
the default positiing bheavour of html elemnts 
cant be changed with position 
elements can ramin in the documents flow or be excluded

## positioning context
