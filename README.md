# Library Management Page

This project is a library management page that allows users to browse, search, filter, and rent books. It includes various modules and features to provide a user-friendly and efficient library experience.

## Front End

The front end of the library management page is built using modern web technologies and follows best practices for user interface design and development. The following modules and features are implemented:

### Loading Animation

An aesthetically pleasing and optimized loading animation is displayed while fetching data from the server or performing background operations. This provides a visually appealing and responsive experience to the users.

### User Signup and Login

The library management page includes a user signup and login functionality to ensure proper authentication and session management. Users can create new accounts, sign in using social media accounts, and verify their email and mobile numbers for enhanced security. Additional brownie points will be awarded for implementing social media integration and robust verification mechanisms.

### Book List

The page displays a list of books fetched from an actual endpoint (API). Instead of loading all the results on the page, an optimized pagination technique is implemented, such as infinite scrolling with lazy loading. This ensures that the page loads quickly and efficiently, even when dealing with a large number of books.

### Search Bar

The library management page includes a well-built search bar with suggestions, similar to popular search engines like Google Search or YouTube. The search functionality is implemented to search across all relevant fields, including book name, author name, genre, and year of publishing. This enables users to quickly find the books they are looking for.

### Book Availability and Details

Each book is presented with an exclusive indication of its availability and the number of copies available. This information is prominently displayed alongside the book's details, such as title, author, genre, and publish date. Users can easily determine the availability of a book before proceeding to rent it.

### Filtering and Sorting

Users can filter and sort the list of books based on various criteria, such as title, author, subject, and publish date. This allows users to refine their search and find books that match their preferences more effectively.

### Book Count

The library management page dynamically updates the count of books displayed upon search results and filtering. This provides users with real-time feedback on the number of books that match their search criteria and helps them evaluate the relevance of their search parameters.

### Cart Feature

A cart feature is implemented, allowing users to add books to their cart and proceed to rent them. When books are added to the cart, the availability and number of copies fields are updated accordingly. This ensures that users can keep track of their selected books and proceed with the rental process seamlessly.

## Technologies Used

The library management page is built using modern front-end technologies, including but not limited to HTML, CSS, and JavaScript. Additionally, relevant libraries and frameworks such as React, Vue.js, or Angular may be employed to enhance the development process and user experience.

## Usage

To run the library management page locally, follow these steps:

1. Clone the repository: `git clone https://github.com/rameshvtu16882/Ramesh-Devrev-Round2`
2. Install the dependencies: `npm install react react-dom react-scripts axios react-router-dom`
3. Configure the API endpoint in the code to fetch book data.
4. Build and run the project: `npm start`
5. Access the library management page in your browser at `http://localhost:3000` (or the specified port).

## Hosted website
[Library Management System](https://devrev-task-eta.vercel.app)

## Contribution

Contributions to the library management page are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request on the GitHub repository. Let's work together to create an outstanding library management experience!
