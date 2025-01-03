# reward_practice

## Project Description
This project demonstrates an interactive **hover blur effect** implemented using HTML and CSS. When a user hovers over one element, all other elements are blurred, creating a visually appealing focus effect. The project showcases a rewards card interface that highlights individual rewards while dimming the rest.

## Features
- **Interactive Hover Effect:** On hovering over an element, all other elements are blurred to direct user focus.
- **Responsive Design:** The layout is designed to fit varying screen sizes using flexible styling.
- **Smooth Transitions:** Elements feature smooth hover animations with ease-in transitions.

## Technologies Used
- **HTML**: Structure and content.
- **CSS**: Styling and hover effects.
- **GSAP Library (optional)**: Included for potential advanced animations.

## How It Works
1. **HTML Structure**:
   - A `div` container (`main`) contains multiple reward cards (`box`).
   - Each reward card includes an image, a description, and a link to redeem points.

2. **CSS Styling**:
   - Basic layout styling using Flexbox for alignment.
   - Individual card (`box`) styling with background, rounded corners, and hover effects.
   - `:hover` pseudo-class combined with a parent selector to reduce opacity of non-hovered elements.

3. **Hover Effect**:
   - The `box:hover` rule creates elevation and a transition effect.
   - The `.main:hover >:not(:hover)` selector reduces the opacity of other elements, creating the blur effect.

