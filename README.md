# web50-projects-2020-x-0
Project 0 fo CS50 for more detail see https://docs.cs50.net/web/2020/x/projects/0/project0.html

Your stylesheet(s) must use at least five different CSS properties, 
  background-color
  border-width
  boarder-style
  boarder-color
  border-collapse


and at least five different types of CSS selectors. You must use the #id selector at least once, and 

the .class selector at least once.

CSS selectors used
  element - table, td, th elements use solid blue table borders
  id  - bart row has a green background
  class - pic class has red color text
  attribute - number inputs have yellow backgrounds
  :hover button hover uses and orange background


Your stylesheet(s) must include at least one mobile-responsive @media query, such that something 

about the styling changes for smaller screens.

/* If the browser window is 600px or smaller, the background color will be lightblue: */		
@media only screen and (max-width: 800px) {
  body {
    background-color: lightblue;
  }


You must use Bootstrap 4 on your website, taking advantage of at least one Bootstrap component
  The page uses the Alert component to warn users when they reach the bottom of the hello page  


, and using at least two Bootstrap columns for layout purposes using Bootstrap’s grid model.
    3 bootstrap columns are used to enforce an 8.3% margin to the left and right of the page.

Your stylesheets must use at least one SCSS variable
  $tablebordercolor: blue;

, at least one example of SCSS nesting
  The body nesting structure is used 

, and at least one use of SCSS inheritance.
  @extend td  (table data); is used to share the boarder properties with th tags (table header)
