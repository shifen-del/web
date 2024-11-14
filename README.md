# Project Overview
This project is a pet information management system designed with a front-end and back-end separation architecture. It allows administrators to perform CRUD (Create, Read, Update, Delete) operations on pet information. The front end is built using Vue.js and ElementUI, while the back end is powered by Spring Boot and MyBatis. Data exchange between the front-end and back-end is handled via RESTful APIs. Key features of the system include administrator login, registration, permission verification, and pet information management. This system aims to provide administrators with an efficient and user-friendly interface for managing pet data.
# Key Features

# 
1.Front-End and Back-End Separation: The project employs Vue.js for the front-end framework and Spring Boot for the back end, enhancing system flexibility and maintainability. The front-end communicates with the back end through RESTful APIs and Axios, making the system more modular and scalable.
# 
2.Permission Management and Security: The system utilizes Spring Security and custom interceptors for user authentication and authorization, ensuring that only logged-in administrators can access and manage pet information. This provides a secure environment for handling sensitive data.
# 
3.User Experience Enhancements: With the use of ElementUI, the system offers a responsive, aesthetically pleasing interface. Features like password visibility toggling contribute to an improved user experience while maintaining security standards.
# 
4.Cross-Origin Resource Sharing (CORS) Support: The project addresses potential CORS issues that may arise in a front-end/back-end split architecture, ensuring smooth operation in different environments.
#
5.Error Handling Mechanism: A comprehensive error handling strategy is implemented with custom exception classes and global exception handling to ensure that any errors are communicated clearly to users, improving the system's robustness.

# Development Approach
The development of this system follows a clear modular approach, with distinct modules for user management and pet information management. Initially, the system's requirements were analyzed, and core features were defined. The front-end and back-end were developed independently but designed to communicate through APIs using JSON. For user management, Vue.js handles login and registration, while the back-end uses Spring Security for authentication. For pet information management, the front-end provides interfaces for adding, viewing, updating, and deleting pet data, while the back-end manages these operations with MyBatis and MySQL. Throughout the development process, error handling, performance optimization, and system testing were prioritized to ensure a reliable and efficient product. Once developed and tested, the system was deployed to ensure accessibility and scalability.
