
# Contact Management Application

This is a full-stack web application for managing contacts, built with **ReactJS** on the frontend and **JSON** on the backend. It allows users to create, view, update, and delete contacts. The app is designed to be fast, responsive, and user-friendly.

## Features

### Frontend
- Built using **ReactJS** with a modern, component-based architecture.
- Interactive UI with live updates for adding, viewing, and editing contacts.
- **Bootstrap** integration for an elegant, responsive design.
- Error handling and loading states with spinners for a smooth user experience.

### Backend
- Powered by **JSON-server**, with a scalable and efficient REST API.
- **JSON** is used for database management.
- Well-structured CRUD operations with proper HTTP status responses.

## Technologies Used

- **ReactJS** for building the user interface.
- **Axios** for HTTP requests.
- **React Router** for page navigation.
- **JSON-server** for backend services.
- **JSON** for database management.

## Setup and Installation

### Backend (Json-server)

1. Clone the repository:
2. Clone the repository: You clone the project from GitHub to your local machine (download zip file and extract it in your system).
3. create server folder in location ContactManagerApp/server (not in src folder)
4. Now to run Json server you need to install node_module folder inside server folder.
```bash
npm install
```
5. inside that add files/paste files from my server folder (follow structure as shown in server folder)
- eg. db.json, package.json, Contactservices.jsx
6. Now install json-server
```bash
npm i json-server --save
```

### Frontend (ReactJS)
  1. Open vsCode terminal (Use Following Commands)
  2. In your project directory: npm install
  3. Create new react Application : npx create-react-app ContactManagerApp
  4. Install bootstrap : npm install bootstrap
  5. Install fontAwesome: npm i @fortawesome/fontawesome-free
  6. Connect fontawesome with html page:	Visit fontawesome (fortawesome/fontawesome-free) official website copy the cdn link and paste in index.html.
  7. Install Axios: npm i axios
  8. Install React-Router: npm install react-router-dom@6
  9. All defendancy setup done....
  10. Now inside src file create folders & components structure (refer ContactManagerApp file and components code).
  11. Now run application : npm start

### API Endpoints
- POST /contacts: Add a new contact.
- GET /contacts: Get all contacts.
- GET /contacts/{id}: Get a contact by ID.
- PUT /contacts/{id}: Update a contact by ID.
- DELETE /contacts/{id}: Delete a contact by ID.
- Make sure API will be same in both service component & Controller class.

### Run the Application
- npm start
### Run the Server
1. cd server
2. npm start

### Screenshots
![image](https://github.com/user-attachments/assets/d81c5b4f-88a6-4cab-92aa-66f3afdeec62)
![image](https://github.com/user-attachments/assets/b4ded839-b239-4fb3-b00c-6c4730cbddd7)
![image](https://github.com/user-attachments/assets/8b2c9a1d-8529-4182-a248-2605a1640411)
![image](https://github.com/user-attachments/assets/f45dd4d4-ff7a-46ef-8ec9-abca2c857802)





