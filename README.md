# Online ToDo List Application – MERN Stack

## Screenshots / Demo

A demo video demonstrating the working of the system and project source files are included in the uploaded project report.

---

## About the Project

The ToDo List Application is a full-stack task management system developed using the **MERN stack (MongoDB, Express.js, React.js, and Node.js)**. It allows users to efficiently manage their daily tasks by adding, updating, deleting, and viewing tasks in a structured manner. The system provides a simple and responsive interface to improve productivity and task organization.

---

## Project Overview

The application consists of a React-based frontend and a Node.js + Express backend connected to a MongoDB database. The backend handles API requests for task operations, while the frontend provides an interactive user interface for managing tasks.

Users can create tasks with a title and description, view all tasks, update existing tasks, and delete completed or unnecessary tasks. The system uses RESTful APIs to communicate between frontend and backend.

---

## How the Project Works

### User Interaction
Users enter task details (title and description) through the React frontend.

### Create Task
When submitted, the task is sent to the backend using a POST API and stored in MongoDB.

### View Tasks
All tasks are fetched from the database using a GET API and displayed on the UI.

### Update Task
Users can edit a task, and changes are updated in MongoDB using a PUT API.

### Delete Task
Users can remove tasks, which deletes the record from MongoDB using a DELETE API.

### Real-Time UI Update
After every operation (add, update, delete), the frontend state is updated instantly for a smooth user experience.

---

## Database (MongoDB)

The system uses MongoDB to store task data.

### Collection Name

| Collection | Purpose |
|------------|--------|
| todos      | Stores task details such as Title and Description using a schema-based model |

### Schema Structure

- Title (String, Required)  
- Description (String)

This schema ensures structured storage and easy retrieval of task data.

---

## Key Features

- Add new tasks with title and description  
- View all tasks in a list format  
- Edit and update existing tasks  
- Delete tasks with confirmation  
- Real-time UI updates using React state  
- REST API-based communication  
- Simple and responsive interface  
- MongoDB integration for persistent storage  

---

## Tools & Technologies Used

- React.js (Frontend)  
- Node.js (Backend runtime)  
- Express.js (REST API framework)  
- MongoDB (Database)  
- Mongoose (ODM for MongoDB)  
- CORS (Cross-origin handling)  
- VS Code (Development environment)  
- Postman (API testing tool)  

---

## Project Goals

- Build a simple and efficient task management system  
- Learn full-stack MERN development workflow  
- Implement CRUD operations using REST APIs  
- Improve productivity through task tracking  
- Understand frontend-backend integration  
- Handle real-time UI updates using React state management  

---

## Applications

- Personal task management system  
- Daily productivity tracking tool  
- Student assignment and deadline tracking  
- Basic foundation for advanced project management apps (like Trello clone)  
- Practice project for MERN stack development  

---

## Problems Faced

- Handling state synchronization between frontend and backend  
- Managing real-time UI updates after CRUD operations  
- Ensuring smooth API communication between React and Express  
- Debugging MongoDB connection and schema issues  
- Handling edit mode logic in React components  
- Preventing duplicate or inconsistent state updates  

---

## Conclusion

The ToDo List Application demonstrates the practical implementation of the MERN stack for building a full-stack web application. It successfully integrates React frontend with Node.js and Express backend, along with MongoDB for data storage. The project supports complete CRUD operations and provides a smooth user experience with real-time updates.

It serves as a strong foundation for understanding full-stack development and can be further extended with authentication, deadlines, and cloud deployment features.
