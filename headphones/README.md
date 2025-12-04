Implement a Design From Scratch
ALX Front-End Development – Week 7
Developed by: Mr.Mezgebo Hailu

This project focuses on building a fully functional and responsive webpage from scratch, using pure HTML5 and CSS3—no external libraries, no JavaScript.
It is designed to evaluate your mastery in semantic HTML, advanced CSS, responsive design, grid/flexbox, and accessibility principles.

The goal is simple: Recreate the provided Figma design exactly as shown.
The challenge is to achieve perfect accuracy while writing clean, maintainable, and accessible code.

🚀 Project Objective

Transform a professional UI/UX Figma design into a real webpage.

Practice full–scale front-end implementation without frameworks.

Strengthen mastery of:

Layout techniques (Grid & Flexbox)

Typography & spacing

Accessibility standards

Mobile-first responsive design

Pixel-perfect implementation

📁 Project Files

Your project should contain:

.
├── index.html
├── styles/
│   └── style.css
├── images/
│   └── (all exported assets from Figma)
└── README.md   <-- you are here

🎨 Figma Design

This webpage design was created by Nicolas Philippot (UI/UX Designer).

🔗 Links

Figma Project: Duplicate to your drafts to inspect sizes, colors, spacing, etc.

If you cannot access the design, the alternative Figma file is provided in the task page.

📝 Notes About Figma

Some measurements are floating values—round them appropriately.

Fonts required:

Source Sans Pro

Spin Cycle OT

Use the color picker and inspector to collect:

Font sizes

Font weights

Line heights

Colors

Margins / paddings

Container widths

Grid layouts

📌 Requirements
✔ You must:
Reproduce the design exactly as provided
Use only HTML + CSS
Ensure the website is responsive on all screen sizes
Follow semantic HTML5 structure

Make your page accessible (aria-labels, alt attributes, color contrast)

❌ You are NOT allowed to:

Use Bootstrap, Tailwind, or any external CSS framework
Use JavaScript
Use pre-built CSS libraries

🧩 What You Will Practice

CSS Grid for complex layouts
Flexbox for alignment
Responsive breakpoints
Custom fonts

Background images
Hover states
Buttons and components styling
Organizing CSS using reusable classes
Mobile-first workflow

🧠 Implementation Strategy (Recommended)

Start with the HTML skeleton

Semantic tags: header, section, nav, footer

Basic structure matching Figma frames

Set up global CSS styles

CSS reset

Typography (fonts, sizes, weights)

Colors

Variables:

:root {
  --primary-color: #...;
  --text-color: #...;
  --font-main: 'Source Sans Pro', sans-serif;
}

Build layout using mobile-first approach

Begin with small screens

Add breakpoints for medium/large screens

Use CSS Grid & Flexbox

Identify grid areas from Figma

Implement layouts section by section

Polish details

Border radius

Shadows

Line heights

Spacing consistency

Icons

Buttons states

Test accessibility

Keyboard navigation

Alt attributes

Contrast levels

Validate your HTML & CSS

W3C Validator

Lighthouse audit (Chrome DevTools)

📱 Responsive Design Approach

You should implement at least three breakpoints:

Mobile: 320–480px

Tablet: 768px

Laptop/Desktop: 1024px and above

Ensure:

Layout adjusts fluidly

Images scale properly

Text remains readable

Navigation adapts to smaller screens (e.g., stacked items)

📝 Usage

Clone your project:

git clone https://github.com/<your-username>/<project-repo>.git
cd project-repo
Open in browser:
index.html
No setup needed—no frameworks, no JS.

✔ Expected Outcome

A clean, professional, pixel-perfect webpage that looks identical to the Figma file and works flawlessly on mobile, tablet, and desktop devices.

📄 License

This project is prepared as part of the ALX Africa Front-End Engineering Programme.
Design credit: Nicolas Philippot.