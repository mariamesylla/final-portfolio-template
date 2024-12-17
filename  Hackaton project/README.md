## Project #3

**Security Controls Manager**

Give a high-level overview of the project purpose:
- **What are the users?**
  - Security teams and IT professionals who need to document and manage security controls.
- **What job does it perform for them?**
  - Provides functionality to add, edit, delete, and view security controls along with their descriptions and artifacts.
- **What inspired you to make it?**
  - The need for an organized system to manage and document security controls efficiently.
- **What features are the most important?**
  - CRUD operations for managing security controls.
  - Persistent storage using **LocalStorage** to ensure data remains available across browser sessions.
  - State management using **Redux**.
  - Responsive design with **Tailwind CSS**.

### STAR Interview Questions:
- **(Situation):**
  - The Security Controls Manager was created to streamline the process of managing security controls by enabling CRUD operations with persistent storage.
- **(Task):**
  - Design and build a frontend application that allows users to manage security controls efficiently, ensuring data persists even after closing the browser.
- **(Action):**
  - Developed the application using **React** for the frontend.
  - Managed state using **Redux**, integrating **redux-persist** to sync data with **LocalStorage**.
  - Styled the application with **Tailwind CSS** for a modern and responsive design.
- **(Result):**
  - Delivered a fully functional Security Controls Manager that supports adding, editing, deleting, and viewing controls with persistent storage.

### Screenshots
**Main App Interface**:
![Main App Interface](./img/elec4.png)
![Main App Interface](./img/elec2.png)

**Control Editing Interface**:
![Control Editing](./img/elec3.png)
![Control Editing](./img/elec1.png)


---

## Technologies
- **React**: For building the frontend interface.
- **Redux**: For state management.
- **redux-persist**: For syncing Redux state with LocalStorage.
- **Tailwind CSS**: For responsive and modern styling.
- **LocalStorage**: For persistent data storage across browser sessions.

### Dependencies
- Installed via `package.json`. Run:
  ```bash
  npm install
