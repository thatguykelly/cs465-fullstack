# cs465-fullstack
Full Stack Dev with MEAN
# Module 8 Journal #

Architecture:
•	Compare and contrast the types of frontend development you used in your full stack project, including Express HTML, JavaScript, and the single-page application (SPA).

They all used some level of static HTML and CSS. Express and the SPA both dynamically built the pages based on the content needed. They went about it far differently. In Express, there were many pages that shared common elements and repeated content.  In Express, you edit the header handlebar and that's it, it loads from that single file every time you run a page load, across the entire website. The SPA only loads a page once. All the HTML and CSS and images are downloaded on the first page load. This makes navigation faster and smoother and reduces server load.

•	Why did the backend use a NoSQL MongoDB database?

For one, the schema is not essential, and we were able to set flexible parameters. We were also able to index based on a few of those parameters while creating our own simple schema. Another is that MongoDB uses JavaScript, which fits directly in with the rest of the MEAN stack. This enabled us to code in JavaScript on the database, back end, and front end. MongoDB is also a lightning-fast database capable of delivering data in real time.


Functionality:
•	How is JSON different from JavaScript and how does JSON tie together the frontend and backend development pieces?

JSON is JavaScript Object Notation. It breaks objects up into key/value pairs. It is different because you can't do things in JSON. It holds data in a usable and readable format for easy use by JavaScript. JSON ties together with frontend development because the frontend uses JavaScript objects to hold JSON data and then do things with it. MongoDB stores objects in BSON, which is very similar to JSON, and converts it well with JSON. The frontend can send JSON data to the MongoDB calls and create, update, or delete records. It can also send JSON to a read function to display information. A wide variety of programming languages support JSON's usage. A more efficient development process is possible because of this.

•	Provide instances in the full stack process when you refactored code to improve functionality and efficiencies and name the benefits that come from reusable user interface (UI) components.

We first refactored when taking the html into the static JSON and directed the html to point to certain data groups in JSON. This shortened the lines of code significantly. Then we refactored to pull the dynamic JSON data from the database. Within this refactor we were also able to make the access to CRUD available to users who had that level of admin privileges. Reusable UI components can be used in different parts of the application. This helps to improve efficiency and maintain consistency. Reusable UI components can also be customized to meet the needs of different users. This helps to improve the user experience. 

Testing:
•	Methods for request and retrieval necessitate various types of API testing of endpoints, in addition to the difficulties of testing with added layers of security. Explain your understanding of methods, endpoints, and security in a full stack application.

An endpoint is simply a specific URL that corresponds to a specific resource or action. Testing is essential to ensure that a full stack application works as expected. Endpoints must be tested to ensure that they return the correct data, and that they behave correctly in different situations. One common security measure is to encrypt data in transit, so that even if it is intercepted, it would be difficult for an attacker to read it. Another common security measure is to authenticate users before allowing them to access sensitive data. This ensures that only authorized users can access the data. Security must be tested to ensure that data is properly encrypted and that only authorized users can access sensitive data. Testing is a complex process, but it is essential to ensuring that a full stack application works correctly. 

Reflection:
•	How has this course helped you in reaching your professional goals? What skills have you learned, developed, or mastered in this course to help you become a more marketable candidate in your career field?

This course has helped me by being the initial introduction into working with the MEAN stack. It gave me knowledge to setup and work with code for a dynamic website. Incorporating HTML, CSS, JavaScript, and JSON. Using API’s and ways to test to make sure the connections are working. Creating and double checking the data being written to the database. Spending time working with the many different libraries and packages that are needed to talk to each other correctly and securely. Introduction into the Model, View, and Controller (MVC) model for web apps. I have learned and developed my skills about security and where the gate’s need to be within a web app system and environment for constant protection. Always nice to get more practice in shell/terminal! This class has been a great foundation for my career in software. I look forward to furthering my knowledge.
