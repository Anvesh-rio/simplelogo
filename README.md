# Purpose
### The goal of this project is to demonstrate a simple yet visually appealing effect where an outer box rotates continuously, while the content inside the box remains stationary. This effect is commonly seen in UI elements like loading spinners or in visual presentations to highlight stability within motion.

### Key Concepts
### CSS Animation:

# The rotation of the outer box is achieved using the @keyframes rule in CSS, which defines the steps of the animation.
# The outer box is animated to rotate from 0deg to 360deg, creating a continuous loop of rotation.
# CSS Transform:

The transform property is used both to rotate the outer box and to counteract the rotation for the inner content.
By applying a negative rotation (-360deg) to the inner content, it visually cancels out the rotation applied to the outer box, making the inner content appear stationary.
How It Works
Outer Box:

The .outer-box element is the container that rotates. It is given a CSS animation that continuously rotates the box around its center.
The display: flex; property is used to center the inner content both horizontally and vertically within the outer box.
Inner Box:

The .inner-box element contains the content that should appear stationary.
By applying a counter-rotation to this inner box or its contents, the effect of rotation is nullified, making it look like the content is not moving even though the outer box is rotating.
Visual Example
Imagine you have a rotating globe (outer box) with a compass (inner content) inside it. While the globe spins, the compass needle (inner content) points to the true north, staying stable and unaffected by the globe's rotation. This project replicates a similar effect using CSS.

Real-World Applications
Loading Animations: The rotating box can be used as a loading spinner, where the inner content (like a logo or text) remains readable and doesn't rotate.
Interactive UI Elements: This effect can be used in interactive web elements to draw attention to specific content while adding dynamic movement to the interface.
Visual Presentations: In presentations, this effect can highlight the concept of stability within change, or show a focal point amidst dynamic motion.
This project serves as a foundation that can be built upon or customized for various creative uses.
###