### Features:
- List items in vertical or horizontal layout
- Hardware accelerated Animations
- Cross-dragging between list containers
- Individual height or width of list items
- Optional margin between list items
- Option to disallow drop to container when above height (dropLimit option)
- Add and remove items from containers
- Callback function after animation on remove method
- Automatically remove and prepend items to containers to prevent overflow (cutOff option)
- Multiple instances on the same page
- reLayout method is added to allow repositioning and updates to position data in object instances. Can be fired after window resize event(which is also fired on orientation change on mobile devices)
- No longer uses jquery plugin structure. Instantiate object using new keyword. Ex var myList = new Loremsition(divElem, options)
- layoutCompleteAll after all instances have been initialized
- Animation speed logic to determine when to speed up animations.
- Dragging with touch, mouse or pointer
- Lock/unlock methods which prevents dragging to and from instance
- The crossDistance method. The crossing distance to the adjacent container
<!-- - Shuffle method -->
- onReorder callback
- Allow for nested elements in list items - [span,button]
- Allows dragging/dropping between n numnber of instances
- Allow individual width of instance container in vertical mode.
- Use css grid to position containers or set to absolute or percentage values;
- ie9+ support (ie9 without animations)
- Smooth animations on mobile using requestAnimationFrame