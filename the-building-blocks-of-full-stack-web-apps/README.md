# ![Intro to Full Stack Development - The Building Blocks of Full Stack Web Apps](./assets/hero.png)

**Learning objective:** By the end of this lesson, students will be able to define the three components of a full stack: front-end, back-end, and database.

## Frameworks and libraries

Frameworks and libraries are vital tools in software development. They leverage pre-written code to help accomplish common tasks without having to start from that work from scratch. They can help us by:

- Simplifying complex tasks by *abstracting* them. This boosts developer productivity and development speed.
- Many frameworks and libraries are widely used and have been tested by many other developers. This typically means that they're more reliable than custom-coded solutions.
- This same community is also a huge asset for troubleshooting and problem-solving.

These are just a few examples of the benefits. While it's possible to build full-stack applications without using frameworks or libraries, it would make the work more tedious and cause the scope of our work to massively increase. In many cases, we would be left to recreate the functionality present in existing libraries or frameworks from scratch.

> 📚 *Abstraction* is the process of hiding technical complexity and details not fully relevant to solving a given problem. It allows programmers to interact with complex systems at a simplified level without having to understand the underlying details.

Libraries and frameworks are not programming languages; they are are just code written using existing languages.

### The differences between frameworks and libraries

Frameworks and libraries are similar but do differ in key ways. Libraries handle specific tasks - like working with dates, formatting strings, and presenting UI elements. They don't enforce how the overall application is structured or behaves.

Frameworks provide a foundation on which you build and organize your application. They'll typically provide a set of conventions to help standardize development, which means different applications built using that framework will largely look the same (for example, they'll have a similar directory structure).

This analogy from [freeCodeCamp](https://www.freecodecamp.org/news/the-difference-between-a-framework-and-a-library-bd133054023f/) may further your understanding:

>A library is like going to IKEA. You already have a home, but you need a bit of help with furniture. You don't feel like making your table from scratch. IKEA allows you to pick and choose different things to go in your home. You are in control.
>
> A framework, on the other hand, is like building a model home. You have a set of blueprints and a few limited choices when it comes to architecture and design. Ultimately, the contractor and blueprint are in control. And they will let you know when and where you can provide your input.

## Front end

The front end of a web application is the part that users interact with directly. It displays the user interface and handles user input.

Browsers natively handle HTML, CSS, and JavaScript code.

**HTML** defines a web page's structure of the web page, **CSS** adds styles to the web page, and **JavaScript** adds interactivity.

Several frameworks and libraries exist to help construct front-end web applications, such as Angular, Vue.js, React, and jQuery.

![Common front-end technologies](./assets/originals/frontend.png)

tktk hunter -- also stole this from mongodb site. it may not be necessary but idk i kinda like it if you wanna redo it. (could you include some frameworks in here too)

## Back end

A back-end system handles the behind-the-scenes functionality of a web application.

The back end processes user requests, makes decisions based on *business logic*, and determines the data that should be sent to the front end.

> 📚 *Business logic* is the part of an application's behavior that accounts for real-world business rules.
>
> Using an e-commerce application as an example, the business logic may include:
>
> - Rules for calculating the total cost of items in a shopping cart.
> - Applying any discounts.
> - Handling inventory stock updates.

The most important reason to handle these tasks on the back-end is security - doing this work there means that users cannot easily see or tamper with them. This is crucial for operations involving personal data, financial transactions, or sensitive business operations.

Beyond this, the back end handles user authentication, communicates with other systems, and more.

Common back-end languages used in web development include JavaScript (executed by Node.js), Python, Ruby, Java, C#, and PHP.

Just like on the front end, several frameworks and libraries can be used to help construct back-end web applications, such as:

- Express.js (JavaScript)
- Flask (Python)
- Java Spring (Java)
- ASP.NET Core (C#)

![Common back-end technologies](assets/originals/backend.png)

tktk hunter - same as above

It's also the job of the back end to interact with databases.

## Database

The data related to an application is persisted in a database. Certain kinds of data, such as textual, numeral, and boolean data, are highly suitable to be stored in a database as they can be easily cataloged, searched for, and retrieved.

Many database technologies are available, but some of the most popular are MongoDB, PostgreSQL, Oracle, and MySQL. Each of these has strengths and weaknesses.

### The two types of databases

There are two main types of databases: **relational databases** and **non-relational databases**.

**Relational databases** store data in tables made up of rows and columns. Each row represents a single record, and each column represents a single attribute of that record.

Relational databases are the most common type of databases and are used by a wide variety of applications. MySQL and PostgreSQL are examples of relational databases.

**Non-relational databases** store data in various formats, such as documents, key-value pairs, and graphs.

Non-relational databases are often used for applications that store and retrieve large amounts of unstructured data. MongoDB is an example of a non-relational database.

### How the three components work together

Together, a full-stack web application's front-end, back-end, and database create a complete user experience.

When a user visits a website, the front end displays the user interface and handles the user input. It may also send data to or request data from the back end. The back end processes information sent to it from the front end and generates responses.

The back end may also send information to or request information from the database. The database is where data for the application is stored, and it responds to the server similarly to how the back end responds to the front end.

tktk Hunter: could use a diagram like the following, but more generic that only shows server and db without the driver, terminal, and database partitions:

![here](https://git.generalassemb.ly/Software-Engineering-Immersive-Remote/SEIR-Ewoks/blob/master/unit_2/w04d04/instructor_notes/Client_Server.png)

For example, when a user searches for a product in the search bar of an e-commerce site, the front end will send that product name to the back end.

The back end will then query the database for products matching the user's search and generate a response containing the matching products. This response will be sent to the front end, displaying the list of matching products to the user.
