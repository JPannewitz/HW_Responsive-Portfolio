# HW_Responsive-Portfolio
Homework assignment #2 Part 1
# HW_Responsive-Portfolio
Homework assignment #2 Part 1

## Live Link
jpannewitz.github.io/HW_Responsive-Portfolio
 

## Requirements to complete HW assignment

- Use previous homework assignment (Basic-Portfolio) to build a responsive web app
- Add media queries to the bottom of the style.css file
- Make the layout match the provided screenshots at the following widths: 640px, 768px, 980px

## Technologies Used
- HTML
- CSS

## Code Explaination
- added `@media screen` tags to control how the layout would look at different specs
-For example
@media screen and (min-width: 769px) and (max-width: 980px) {
  #masthead {
    width: 100%;
  }
  #logo {
    margin-left: 50px;
  }
  nav {
    margin-right: 50px;
  }
  .main-section {
    margin-left: 50px;
    width: 50%;
  }
  .sidebar {
    margin-right: 50px;
  }

  .work {
    width: 100%;
  }
}

changed the layout when the page is between the widths of 768px and 980px

-------------