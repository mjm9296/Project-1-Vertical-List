# ddd-steps-list

A vertical steps list web component

## Features
- Each step is styled and numbered automatically
- Only valid child nodes (`<ddd-steps-list-item>`) allowed
- Invalid elements (e.g., `<div>`, `<h2>`) are removed on render
- Responsive layout: adjusts to screen size
- Uses HAX toolchain and DDD design tokens
- Fully customizable with `ddd-primary` color prop

## Usage
```html
<ddd-steps-list ddd-primary="5">
  <ddd-steps-list-item title="First Step">
    <p>Details for the first step...</p>
  </ddd-steps-list-item>
</ddd-steps-list>
```

## Installation
1. Clone the repo
2. Run `npm install`
3. Run `npm start`
4. Open your browser to the provided local address

## Live Demo
[Insert Vercel Deployment Link Here]

## Built With
- [Lit](https://lit.dev/)
- [HAX](https://haxtheweb.org/)
- [DDD Design System](https://www.psu.edu/resources/first-year-students/2plus2plan)

## Folder Structure
```
project-root/
├── index.html
├── package.json
├── README.md
└── src/
    ├── ddd-steps-list.js
    └── ddd-steps-list-item.js
```
