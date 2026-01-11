# 📑 Accessible Tabs Component

## Overview
This project demonstrates a **simple accessible tabs component** built using **HTML, CSS, and vanilla JavaScript**.  
It uses **WAI-ARIA roles and attributes** to ensure the tabs are usable with screen readers and keyboard navigation.

## Features
- Click-based tab switching
- Displays only the active tab panel
- Uses ARIA roles for accessibility
- Screen-reader friendly structure
- Clean and minimal JavaScript logic
- No external libraries or frameworks

## Tech Stack
- HTML5
- CSS3
- JavaScript (ES6)

## How It Works
- Each tab element uses `role="tab"`
- Each content panel uses `role="tabpanel"`
- Tabs are connected to panels using the `aria-controls` attribute
- Clicking a tab:
  - Marks all tabs as unselected
  - Hides all panels
  - Selects the clicked tab
  - Displays the associated panel

## JavaScript Logic
- All tabs are selected using `[role="tab"]`
- All panels are selected using `[role="tabpanel"]`
- Event listeners handle tab clicks
- The `hidden` property is used to show or hide panels
- `aria-selected` keeps screen readers informed about the active tab

## Example Behavior
- Clicking a tab activates it
- Only one tab is active at a time
- Only one panel is visible at a time

## Learning Outcomes
This project helps in understanding:
- DOM manipulation
- Event handling in JavaScript
- ARIA roles and attributes
- Accessible UI patterns
- State-based UI updates

## Use Case
- Accessible tab navigation
- Content switching interfaces
- UI component practice
- Accessibility-focused learning projects

## project structure
- `index.html`: The main HTML file containing the tab structure.    
- `styles.css`: The CSS file for styling the tabs and panels.
- `tablist.js`: The JavaScript file for handling tab interactions.
- `README.md`: This documentation file. 
- `.gitignore`: Git ignore file to exclude unnecessary files from version control.
- LICENSE: License information for the project.

## live demo
You can view a live demo of the project [here](https://your-live-demo-link.com).