# Task 4 - CSS Units, Box Model and Fonts

## About Project

In this task I created a simple webpage using HTML and CSS.  
The page contains:
- one image
- one button
- spacing using viewport units

Main focus of this task was learning:
- viewport units
- box model
- spacing
- gradient button styling

---

## Files Used

- index.html
- style.css
- README.md

---

## Why I Used 25vw and 10vh

I used 25vw for left and right spacing because the assignment asked for equal spacing of 25% from both sides of the screen.

vw means viewport width.

So:
- left spacing = 25vw
- right spacing = 25vw

This leaves the remaining center area for the content.

I used 10vh for top and bottom spacing.

vh means viewport height.

This helps keep spacing responsive according to screen size.

---

## Difference Between Viewport Units and Percentage Units

Viewport units depend on screen size.

Examples:
- vw = viewport width
- vh = viewport height

Percentage units depend on parent element size.

Example:
- 50% means 50% of parent width
- 50vw means 50% of screen width

---

## How box-sizing:border-box Helps

I used:

```css
box-sizing:border-box;