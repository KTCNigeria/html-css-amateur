# Task Two - CSS Grid Layout 

In this task, we'll explore creating a grid layout using CSS to structure the visual layout of a web page. Just like forms are essential for user input, grids help in organizing content on a web page in a structured manner.

## Grid Layout Basics

CSS grid layout is a powerful tool to create two-dimensional layouts with rows and columns. You can define a grid container and place items within it using grid properties.


Here's a simple example of creating a 2x2 grid:

```css
.container {
  display: grid;
  grid-template-columns: 1fr 1fr;
  grid-template-rows: 1fr 1fr;
}

.item {
  border: 1px solid #000;
  padding: 20px;
}
```

Reference practice video : <a style="color: red;" href="https://geek4ktc.pythonanywhere.com/ktc/resources/css-grid" target="_blank">Css grids </a>

## Your Task

Imagine you want to create a simple grid layout for a login page:

-   Create a grid container with two rows and one column.
-   Inside the grid container, add three items:
    -   One for the username input.
    -   One for the password input.
    -   One for the "Sign In" button.
-   Use CSS grid properties to position these items in a structured layout.
