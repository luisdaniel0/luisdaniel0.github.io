# **CS-499 ePortfolio**

## **Introduction**
   Hello, my name is Luis Sanchez, this ePortfolio showcases the culmination of my work in the Computer Science program at SNHU. Throughout this project, I have refined and enhanced key software engineering skills, particularly in software design, algorithms, data structures, databases, and professional code review practices.

## **Self Assesment** 
  Throughout my time in the Computer Science program at SNHU, I have completed numerous courses that have strengthened my skills in software engineering, algorithm design, and database management. The enhancements I made to my projects not only demonstrate my ability to work with full-stack technologies but also support my aspirations to become a Software Engineer. These enhancements directly align with the program outcomes in areas such as software design, algorithms and data structures, databases, and software development best practices. Courses like CS340 gave me valuable insight into how databases function, how to create and store data effectively, and how to secure that data so only authorized users can access it. Database security is crucial because allowing unrestricted access could lead to manipulation, which would create serious issues. 

  Additionally, CS465 equipped me with foundational skills for building robust, full-stack web applications, essential for my pursuit of a career in software engineering. In this course, I learned how to connect client interfaces with server-side functionality and manage databases like MongoDB. I also gained experience with version control tools like Git, preparing me to collaborate effectively in a team environment and communicate with stakeholders, which is vital in the field of software engineering. Clear communication with stakeholders ensures that project requirements are met and helps align technical solutions with business needs.

### **Artifact**
  The original artifact submitted for the portfolio is a Trivia App built with HTML/CSS/Javascript. This app was designed and built in a coding bootcamp course I completed in 2022. The app is a quiz that gives the user ten random questions regarding music albums, the user then has to select one of four multiple choices to answer which artist the album belongs to. A total score is given to the user at the end of the quiz, and the user can restart it after completion. This project serves as a testament to my skills across three key areas of computer science: software design and engineering, algorithms and data structures, and databases.

  In the Software Design and Engineering category, I focused on modernizing the application's architecture by transitioning from a traditional codebase to a more structured and maintainable framework. This involved implementing best practices in UI/UX design to create a more engaging and interactive user experience.

  For the Algorithms and Data Structures enhancement, I introduced a binary search tree (BST) algorithm to efficiently sort and retrieve trivia questions in alphabetical order. This improvement not only optimized the app's performance but also showcased my understanding of data structures and algorithmic principles, demonstrating my ability to enhance functionality through efficient coding practices.

  In the Databases category, I integrated a MySQL database to store trivia questions, user answers, and scores, allowing for persistent data management. This enhancement reflects my knowledge in database design and management, ensuring that user data is stored securely and can be accessed seamlessly.

  These enhancements illustrate my approach to software development, highlighting my technical knowledge and ability to apply computer science principles to real-world applications.

  [Original Artifact Repository](https://github.com/luisdaniel0/trivia-game)

## **Code Review**

[Code Review Link](https://www.youtube.com/watch?v=xxfROwJEXEE)

## **Enhancement One: Software Design and Engineering**
  I selected the Trivia app artifact for this enhancement because it showcases a wide range of software development skills, from front-end design to efficient state management and component-based architecture. This project demonstrates my ability to build interactive, dynamic web applications, emphasizing user experience and functionality. Originally built with vanilla JavaScript, the app was significantly enhanced by transitioning to React and Vite, demonstrating my ability to modernize and optimize a codebase using modern web development frameworks and tools. This enhancement highlights my proficiency in component-based architecture, state management, and user interface design in React. By using Vite as the build tool, I also improved the performance and developer experience of the application, showcasing my ability to implement cutting-edge tools and methodologies. 
  
  
  Transferring the trivia app from vanilla JavaScript to React introduced new challenges, particularly with managing component state and React’s one-way data flow. Handling state across multiple components while ensuring the quiz logic functioned correctly required a deeper understanding of React’s architecture. Incorporating Vite into the development process also introduced a learning curve, but it allowed me to set up a more efficient development environment, improving the app's performance. This experience reinforced my skills in modern web development and helped me apply design patterns that make the application more scalable and easier to maintain.

  When transferring the trivia app from vanilla JavaScript to React + Vite, I broke the app down into smaller, reusable components and implemented React’s state management to handle dynamic changes. The first step was setting up the project with Vite, a modern build tool that offers a faster development environment. I then structured the app into a functional component using React’s useState hook to manage the quiz's state, such as the current question index, the user’s score, and whether the quiz was completed.

  One of the key changes was moving from directly manipulating the DOM to React’s virtual DOM, which allows for more efficient updates. Each time a user selects an answer, the handleChoiceChange function updates the state, and the quiz dynamically renders the next question by incrementing the question index. The logic for checking answers and updating the score was managed within the checkAnswer function, which also controls the flow of the quiz by checking if there are more questions or if the quiz has finished.
  ![SWE](/imgs/swe.png)

  This enhancement demonstrates my ability to apply well-founded and innovative techniques, skills, and tools in software development to create efficient and maintainable solutions. Specifically, it showcases software design principles such as modularity, reusability, and maintainability, aligning with outcomes related to software engineering best practices. By transitioning the app to React, I showcased my ability to adapt to new frameworks and design interactive, dynamic web applications using modern development techniques.

  ![Enhanced Software Design and Engineering Repo](https://github.com/luisdaniel0/EnhancementOne-Software-Design-and-Engineering)

## **Enhancement Two: Data Structures and Algorithms** 
  I chose the Trivia App artifact for this enhancement because it represents a comprehensive application of data structures and algorithm, specifically the use of the Binary Search Tree for managing and organizing quiz questions to enhance the functionality and performance of the application. 

  The key aspects of this artifact is the implementation of a Binary Search Tree to store and retrieve quiz questions and display them in order. The questions are inserted into the tree based on the lexicographical order of the question text, and an in-order traversal ensures that the questions are presented to the user in alphabetical order. This implementation showcases my understanding of data structures and the ability to manipulate them for practical use.

  The artifact improved in many ways. I implemented this BST to dynamically sort the trivia questions in alphabetical order based on their text. This addition showcases the use of algorithms and data structures to solve a real-world problem. With the implementation of this BST, the app is now more scalable, allowing for the addition of new questions without affecting the overall efficiency. With the app efficiently organizing and retrieving questions in a lexicographical order, the time complexity of insertion and sorting is handled more efficiently compared to manual sorting methods. The in-order traversal of the BST guarantees that questions are presented in the correct order, improving both the user experience and the underlying performance.

  The course outcome I planned to meet was: Design and evaluate computing solutions that solve a given problem using algorithmic principles and computer science practices and standards appropriate to its solution while managing the trade-offs involved in design choices. I met this outcome by implementing a BST that leverages key algorithmic concepts, such as inserting elements based on their order and traversing the tree in order to retrieve the sorted list.

  The BST has an average time complexity of O(log n) for insertions and O(n) for traversals, which is efficient for the small dataset I’m working with. One of the trade-offs I had to manage was, that if the dataset grows, considerations about balanced trees may need to be made to avoid worst-case O(n) behavior during insertions. This BST fits the scale of the application, managing the trade-off between simplicity and efficiency.

  Implementing a BST taught me the benefits of choosing the right data structure based on the problem. Sorting the questions alphabetically through the BST’s in-order traversal is a clear example of how data structures can help organize and manage data more efficiently than manually coding for such tasks.

  I’ve never used a BST before so implementing it was challenging at first, mainly the logic for insertion and ensuring the tree balanced itself during operation. Understanding how to properly traverse the tree in order to display the questions in a sorted manner was a key challenge that required multiple redo’s to get right.

  ![BST](/imgs/dsa.png)
  The insert method inserts a new question into the BST. If the tree is empty, the new question becomes the root node, otherwise, it calls a helper method to find the correct position in the tree. This method ensures the new question is inserted in the correct position in the tree based on lexicographical order. If the new question's text is smaller than the current node's text, it goes to the left. If it's larger, it goes to the right. It recursively traverses the tree to find the appropriate spot.






## **Enhancement Three: Databases**
  I chose the Trivia App artifact for this enhancement because it demonstrates my ability to develop a full-stack application with both a front-end interface and a back-end powered by a MySQL database. This Trivia App integrates multiple areas of software development, including database design, server-side programming, and client-side rendering of dynamic content. It reflects my proficiency in developing a structured, data-driven application, from setting up the database schema to handling user interactions in a browser-based interface. The artifact improved from having all the questions stored in a single array of objects to having all the questions stored in a MySQL database.

  In the original artifact, questions were hard-coded and stored in a JavaScript array of objects, but with the implementation of the MySQL database, I transitioned to a more dynamic data storage approach. This enhancement allows for easier management of trivia questions, enabling the app to retrieve, update, and delete questions as needed without altering the codebase.

  I utilized Express.js for the back-end server and MySQL as the database to store quiz questions, showing my skills in full-stack development. I implemented asynchronous fetch requests to ensure the app could dynamically retrieve questions from the server without reloading the page, which enhances user experience—a key industry goal in web development.

  Additionally, I applied CORS techniques to handle security policies, ensuring that data from the server could be accessed by the client-side code, reflecting my understanding of real-world security practices. By combining front-end JavaScript with database-driven content, I showcased how modern computing practices can be used to create a seamless, interactive experience that delivers value by allowing users to engage with dynamically generated quiz content.

  While enhancing and modifying the database-backed Trivia App artifact, I learned a lot about integrating front-end functionality with a back-end database and how different components communicate to create a dynamic, interactive user experience. 

  One of the key challenges was managing data flow between the server, database, and client-side code, particularly with the implementation of CORS and fetching data asynchronously. Setting up a MySQL database and ensuring the right data is retrieved for the quiz questions was also tricky, as it required understanding SQL queries and ensuring the database was structured correctly. Another challenge was ensuring that the quiz app remained responsive and interactive, even when fetching data from the server, and handling issues such as missing or incorrect data. This required testing and troubleshooting server responses, as well as improving the user interface to handle errors gracefully. 


  All of the course outcomes were met in this enhancement by designing the database schema to store quiz questions efficiently. I used structured SQL queries to retrieve data dynamically based on user input. This highlights my understanding of algorithmic efficiency when dealing with relational data, ensuring that database operations were optimized for performance. I made trade-offs between various approaches for data handling. For example, I opted for a relational database over storing data in a JSON file for scalability, despite the added complexity of setting up a MySQL server. This decision allowed for better query performance. 

  ![Database](/imgs/databasemysql.png)

  I also demonstrated an ability to use well-founded and innovative techniques, skills, and tools in computing practices for the purpose of implementing computer solutions that deliver value and accomplish industry-specific goals. This project demonstrates how innovative tools like Node.js, MySQL, and Fetch API can be used to accomplish industry-specific goals, such as building responsive, scalable web applications. It also shows how important connecting various components such as the client, server, and database, in an efficient and effective manner, ensuring the solution is both functional and user-friendly.

  I also accomplished the course outcome of designing, developing, and delivering professional-quality oral, written, and visual communications that are coherent, technically sound, and appropriately adapted to specific audiences and contexts.
  The process taught me valuable lessons in managing both front-end and back-end development, handling real-world constraints like security policies, and refining code to ensure scalability and performance.






