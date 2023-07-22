# Search Engine Project






This project is an implementation of a simple search engine with term frequency-based web crawling using Java and various web technologies. The search engine allows users to search for information and retrieves the top 30 results according to their query. Additionally, it displays the search history of previous queries.

## Features
1. **Web Application Interface:** The project will include a web application with a user-friendly search bar , a search button and History button. 


    ![se11](https://github.com/Ojas-Pratap-Singh/Search-Engine/assets/128834924/d89f95e4-dc78-4db4-9f02-34f5fbd14c81)

2. **Search Functionality:** Users can enter their search query in the search bar and click the search button to retrieve the top 30 relevant results from the database.
    ![se1](https://github.com/Ojas-Pratap-Singh/Search-Engine/assets/128834924/239e7fae-328f-4a2d-985b-bfa2ae5c40ad)

3. **Search History:** The search engine stores and displays the history of previous search queries made by users, allowing them to easily revisit past searches.
    ![se22](https://github.com/Ojas-Pratap-Singh/Search-Engine/assets/128834924/472dab75-f2bd-4d2d-a5ba-aa0b68338281)


## Web Application Design

The search engine web application consists of three major components:

1. **Front-end:** This is the client-side of the application, where users interact with the application. It is responsible for rendering the user interface and handling user input.

2. **Back-end:** The server-side of the application, which processes requests from the client and generates responses. It contains multiple servlets, including the search servlet and history servlet, to handle different operations.

3. **Database:** The database stores web page data obtained by the web crawler. It is used for search operations and to keep track of the search history.

## Technologies Used

The project utilizes a combination of Java and web technologies:

- **Java Servlets:** Used for the back-end implementation to handle different operations like search and history retrieval.

- **Java Server Pages (JSP):** Used to connect the front-end to the back-end by allowing Java code to be written inside HTML files.

- **HTML and CSS:** Used for creating the user interface and styling the web pages.

- **MySQL:** The database management system used for storing and managing data, including web pages and search history.

## Getting Started

To run the search engine project on your local machine, follow these steps:

1. Clone the repository to your local machine using the following command:
   git clone https://github.com/Ojas-Pratap-Singh/Search-Engine.git

2. Open the project in your preferred Java Integrated Development Environment (IDE) (e.g., IntelliJ IDEA).

3. Set up the required dependencies, including Java Servlet API, MySQL Connector, and other libraries specified in the `pom.xml` file.

4. Create the MySQL database with appropriate tables for storing web pages and search history. The SQL queries to create the tables can be found in the project's documentation.

5. Compile and run the web application using your IDE's built-in server or an external application server (e.g., Apache Tomcat).

6. Access the search engine in your web browser by entering the appropriate URL (e.g., `http://localhost:8080/search-engine/`).

 

