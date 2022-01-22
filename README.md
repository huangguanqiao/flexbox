# flexbox
## Review: Flexbox
1. display: flex changes an element to a block-level container with flex items inside of it.
2. display: inline-flex allows multiple flex containers to appear inline with each other.
3. justify-content is used to space items along the main axis.
- flex-end will set all items to be positioned in order, with the last item starting on the right side of the parent container, with no extra space between or after them.
4. align-items is used to space items along the cross axis.
- The align-items property makes it possible to space out flex items vertically.
5. flex-grow is used to specify how much space (and in what proportions) flex items absorb along the main axis.
6. flex-shrink is used to specify how much flex items shrink and in what proportions along the main axis.
7. flex-basis is used to specify the initial size of an element styled with flex-grow and/or flex-shrink.
8. flex is used to specify flex-grow, flex-shrink, and flex-basis in one declaration.
- The flex property can have two values to declare either the flex-grow and flex-shrink properties or the flex-grow and flex-basis properties.
- When there are only two values of the flex property, the first value is used to set flex-grow.
9. flex-wrap specifies that elements should shift along the cross axis if the flex container is not large enough.
10. align-content is used to space rows along the cross axis.
11. flex-direction is used to specify the main and cross axes.
12. flex-flow is used to specify flex-wrap and flex-direction in one declaration.
13. Flex containers can be nested inside of each other by declaring display: flex or display: inline-flex for children of flex containers.
- inline-flex allows us to create flex containers that are also inline elements.
- Given there is enough space, the .box elements will have the width of 300px, but if not, they will shrink to fit the screen.
