# Assignment 4 - Components

## TODO List Application From A2 In React and Express

Glitch Link: [https://a4-mahirsowad3.glitch.me/](https://a4-mahirsowad3.glitch.me/)

Note about Glitch Link: If you get a **Cannot GET /** error upon loading the Glitch project, please just refresh the page and it should work on the refresh.

This is a remake of the TODO List Application from A2 using React for the frontend and Express for the backend. In order to serve both the frontend and backend from the same server port, the vite-express module was utilized. I had some challenges setting this up in the beginning but was able to figure it out with some help from Akim, the class TA. For this assignment, I took my index.html file from A2 and split it up into smaller and more modularized components. I thought that React improved the development experience for me. It made me think more carefully about the design of my application, break it up into logical and more maintainable components. The large index.html file that I had from A2 was getting very complex and difficult to make changes to. In React, I split up my components into a logical structure that made more sense in terms of long-term maintainability. I split up the index.html into 3 broad components: Header, Main, and Footer components, which correspond to the header, main body, and footer sections of the webpage respectively. Inside of the Main component, I split the content up even further into a Form and ResultsTable component. And inside of the ResultsTable, I populated it with a list of TableRow components. I was having some difficulty at first wrapping my head around passing functions down through multiple child components, but it made more sense to me as I neared the completion of the remake. Also, achieving things such as rendering multiple rows, displaying JS varaibles in HTML, and updating all visual instances that uses the value of a certain variable is very straightforward and simple to accomplish in React in contrast to Vanilla JavaScript.

### Note: I have been granted an extension approved by Professor Roberts
