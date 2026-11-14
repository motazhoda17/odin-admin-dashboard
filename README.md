# Admin Dashboard

A dashboard layout built for [The Odin Project](https://www.theodinproject.com/lessons/node-path-intermediate-html-and-css-admin-dashboard) Intermediate HTML and CSS course, using CSS Grid for almost all of the layout.

## How the layout works

- **Page:** a 2-column, 2-row grid using `grid-template-areas` (sidebar | header, sidebar | main)
- **Sidebar, header, cards, panels:** each is its own grid inside the page grid
- **Project cards:** `repeat(auto-fit, minmax(300px, 1fr))`, so the number of columns changes as the window resizes

## Credits

- Icons from [Material Design Icons](https://pictogrammers.com/library/mdi/)
- Font: Roboto from Google Fonts
- Design from The Odin Project
