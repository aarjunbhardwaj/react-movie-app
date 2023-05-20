MovieWeb is a web application built using React that allows users to search for movies and view details about each movie. The application utilizes the OMDb API (omdbapi.com) to fetch movie data.

Key Features:

Global State Management: MovieWeb uses the useContext hook for global state management. This helps in avoiding prop drilling by providing a centralized state that can be accessed by multiple components.

AppContext.Provider: The AppContext.Provider component is used to share data across different components in the application. It acts as a wrapper around the components that need access to the shared data.

Timed Operations with useEffect: The useEffect hook is used to manage timed operations in MovieWeb. It allows the application to perform actions, such as fetching movie data, when certain dependencies change or when the component mounts or unmounts.

State Management with useState: The useState hook is utilized for handling values in state variables. It enables MovieWeb to store and update data dynamically, such as search results or selected movie details.

Async/Await for Sequential Execution and Error Handling: MovieWeb utilizes async/await to perform asynchronous operations, such as fetching data from the API. This allows for sequential execution of code and simplifies error handling by using try/catch blocks to catch and handle any potential errors.

React Router for Creating Routes: MovieWeb uses the "react-router-dom" package, specifically version 6.4.3, for creating routes within the application. This enables navigation between different pages or components, allowing users to search for movies, view movie details, and explore different sections of the application.

Additionally, the application imports Google Fonts to load the "IBM Plex Serif", "Lora", and "Poppins" fonts, which are used for typography and enhance the visual presentation of the MovieWeb project.

Overall, MovieWeb is a React-based web application that leverages the power of React hooks, global state management, async/await, and routing to provide users with an intuitive and interactive movie search and information viewing experience.
