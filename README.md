# MI-349-Portfolio

A content full portfolio site structure for beguining of MI 349 final project. 

## Features

- Semantic HTML5 layout
- Navigation to each section
- Project showcase with Title shots or embedded YouTube trailer, team size, role, and responsibilities
- Light and dark mode support
- Responsive design that works on pc and mobile 
- Sticky header for navigation 

## Sections

**Intro**: Short greeting and brief summary 
**About**: Background, leadership experience, and personal interests
**Projects**: Summary for each game: TreeKeeper, The Last Halloween, Dragon's Hoard
**Contact**: fake email link

## Styling

**Font**: Open Sans (local files in the `Fonts` folder)
**Colors**: #0B294D, #FFFFFF, #4CA3E5, #11335A
**Custom properties**: `--color-dark`, `--color-white`, `--color-accent`, `--color-navy`, `--font-main`
**Layout**: Inline-block navigation and a centered content column
**Layout**: CSS Grid for the page and project; Flexbox for the navigation and inside project cards

## Responsive Design

**General Grid**: The header, main content, and footer are in a Grid
**Navigation **: Logo stacked above the links on phones, then a single row with logo the links on the two corners
**Project Cards**: One column on phones, two columns at 800px, and three columns at 1200px. Used flexbox so the buttons stay on the bottom of cards
**Text**: Headings use clamp to scalse with screen size

## AI Usage

    Claude code helped me with the responsive design changes to my Project Cards section.
    The prompt was, "Write the CSS for the Project Cards section so that 
    it uses CSS Grid for the layout of the section and Flexbox inside each 
    project card. Make sure it would work well on mobile."
    I already have Claude the whole HTML and CSS files just so it could tell 
    what the layout and content should be / what the intent was.
    The output was the #projects, #project h2, and the display/flex/width adjustments