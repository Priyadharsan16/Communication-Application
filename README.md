# Communication Application

A web-based application that allows users to upload and manage documents, manage user profiles, and engage in simple chat functionalities. This project is built with HTML, CSS, and JavaScript and uses browser `localStorage` for data storage.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [How to Run the Application](#how-to-run-the-application)
- [Functionality Overview](#functionality-overview)
- [LocalStorage Structure](#localstorage-structure)
- [Contact Author](#contact-author)

## Features
- **User Authentication**: Login and registration with client-side validation.
- **Document Management**:
  - Upload files with descriptions.
  - Edit and delete uploaded files.
  - View a list of all uploaded files.
- **Chat System**:
  - Engage in chat conversations with other users.
  - Simple real-time chat interface (within the same browser session).
- **User Management**:
  - Edit user profile information (username and password).
  - Manage logged-in sessions.
  
## Technologies Used
- **Frontend**: HTML5, CSS3
- **JavaScript**: Core logic for user authentication, document handling, chat, and profile management.
- **Browser LocalStorage**: Used for storing user information, uploads, and chat history.

## How to Run the Application
1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/Communication-Application.git
    cd Communication-Application
    ```

2. **Open the application**:
   Open the `welcome.html` file in your web browser:
    ```bash
    open welcome.html
    ```
    Alternatively, you can directly drag the `welcome.html` file into your browser.

3. **Usage**:
   - **Register** a new user account, or log in with existing credentials.
   - Upload and manage documents from the dashboard.
   - Engage in chat conversations from the chat section.
   - Edit profile details in the profile section.
   
## Functionality Overview
### 1. Login & Registration
- Users can register by providing a username and password.
- Authentication is done client-side and stored in `localStorage`.

### 2. Document Management
- **Upload**: Upload files (with only the filename and description stored).
- **Edit/Delete**: Modify file descriptions or delete files entirely.

### 3. Chat System
- Simple chat interface allowing users to communicate.
- Messages are stored and displayed using `localStorage` during the session.

### 4. User Profile Management
- Edit profile information (username and password).

## LocalStorage Structure
The application uses `localStorage` to store all the data locally on the user's browser. The data structure is organized as follows:

- **Users**: Stored under `users`, with each user having a `username` and `password`.
- **Logged In User**: The currently logged-in user is stored under `loggedInUser`.
- **Uploads**: Stored under `myUploads`, where each file has a `fileName` and `label` (description).
- **Chat History**: Stored under `chatHistory`, with messages saved per user chat session.
- **username**: Name of the user is stored in variable `username`.

## Future Enhancements
- Implement server-side functionality for secure data storage.
- Enable file download and more robust document management.
- Introduce real-time chat with WebSocket.
- Implement password encryption and better user session management.

## Contact Author
Sri Priyadharsan K

sripriyadharsan@gmail.com
