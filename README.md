# web50-projects-2020-x-0\
Project 0 for CS50. For the project assignment details see https://docs.cs50.net/web/2020/x/projects/0/project0.html

The goal of this project was to make a personal website. I chose to create a showcase website that I could show potential employers. This web site contains the lessons I have learned so far in CS50. The website is hosted at https://bart-source.github.io/web50-projects-2020-x-0

The 11 requirements of this project and how they were implemented are listed below:

1\. The website must contain at least four different .html pages, and it should be possible to get from any page on your website to any other page by following one or more hyperlinks.

    The site uses 4 html pages: index.html, hello.html, mystyle.html, and readme.html.\
    The index page contains a link to hello.html, mystyle.html, and readme.html.\
    At the bottom of each page is a link that returns to the index page.

    The purpose of each page is:\
      index.html - Provides links to all of the other pages in the website\
      hello.html - Provides a table of HTML and CSS examples\
      mystyle.html - Displays the style sheet mystyle.CSS used by hello.html\
      readme.html - Displays the project details

2\. The website must include at least one list (ordered or unordered), at least one table, and at least one image.\
     The site has 1 ordered and 1 unordered list example. There is one table. There are 2 images (1 local and 1 wiki image)

3\. The website must have at least one stylesheet file.\
     The site uses 1 style sheet for hello.html named mystyle.css

4\. Your stylesheet(s) must use at least five different CSS properties:

    The file mystyle.css sets these 5 properties\
      background-color\
      border-width\
      boarder-style\
      boarder-color\
      border-collapse

5\. Your stylesheet(s) must use at least five different types of CSS selectors. You must use the #id selector at least once, and\
the .class selector at least once.

      The file mystyle.css uses these 5 types of CSS selectors:\
        element - table, td, th elements use solid blue table borders\
        id  - bart row has a green background\
        class - pic class has red color text\
        attribute - number inputs have yellow backgrounds\
        :hover button hover uses and orange background

6\. Your stylesheet(s) must include at least one mobile-responsive @media query, such that something about the styling changes for smaller screens.

    The file mystyle.css uses:\
      /* If the browser window is 600px or smaller, the background color will be light blue */\
      @media only screen and (max-width: 800px) {\
        body {\
          background-color: lightblue;\
        }

7\. You must use Bootstrap 4 on your website, taking advantage of at least one Bootstrap component\
    The hello.html page uses the Alert component to warn users when they reach the bottom of the page

8\. Use at least two Bootstrap columns for layout purposes using Bootstrap's grid model.\
    3 bootstrap columns are used to enforce an 8.3% margin to the left and right of the hello.html page.

9\. Your stylesheets must use at least one SCSS variable\
      mystyle.scss uses:\
      $tablebordercolor: blue;

10\. Your stylesheets must use at least one example of SCSS nesting\
      mystyle.scss uses:\
      The body nesting structure

11\.  Your stylesheets must have at least one use of SCSS inheritance.\
       mystyle.scss uses:\
          @extend td  (table data); is used to share the boarder properties with <th> tags (table header)
