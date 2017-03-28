# Sample Flourish template: draggable circle

This sample template builds on the [simple circle example](https://github.com/kiln/example-template-circle),
and demonstrates how user interaction can change the state. This template can be used in the
Flourish Story Editor to create a story in which a circle moves about. It also demonstrates the
use of the [smooth-resize module](https://www.npmjs.com/package/@flourish/smooth-resize) to
update smoothly as the window is resized.

This example demonstrates the correct way to handle user interaction in a Flourish template: user interaction should update the state, and then the `update()` function can be used to update the graphic from the state. Following this pattern means your templates will work as intended in the Flourish Story editor.

Use the [Flourish SDK](https://www.npmjs.com/package/@flourish/sdk) to try it out.

The main code file for the template is [`src/index.js`](src/index.js).
