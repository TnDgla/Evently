
---

# **Evently: Simplifying Event Planning**

This project involves building an event planning application using the **MERN stack** (MongoDB, Express.js, React, and Node.js). The app includes features such as user authentication, event creation, event management, and real-time notifications. This project provides a comprehensive understanding of full-stack development while enabling participants to create an interactive and efficient event management system.

---

### **Mission and Objectives**

#### **Goal:**
By the end of this project, participants will create a fully functional event management application with real-time features and secure authentication.

#### **Objectives:**
1. Develop a **MERN stack** application for managing events.
2. Implement secure authentication using **JWT**.
3. Create user-friendly interfaces for event creation, management, and notifications.
4. Integrate real-time features for event updates and notifications using **Socket.io**.
5. Deploy the application to hosting platforms for public access.

---

### **Technology Stack**

#### **Frontend**

1. **React.js**
   - **Why?**: Simplifies UI development with reusable components.
   - **Use Cases**: Rendering dynamic event management pages, forms, and user interfaces.
   
2. **Material-UI**
   - **Why?**: Provides pre-designed components for faster development.
   - **Use Cases**: Styling event cards, buttons, and modal windows.

3. **Redux Toolkit**
   - **Why?**: Efficiently manages global state across the application.
   - **Use Cases**: Handling application-wide state like user sessions, event details, and notifications.

4. **Axios**
   - **Why?**: Simplifies HTTP requests to the backend.
   - **Use Cases**: Fetching event data, handling user login, and creating events.

---

#### **Backend**

1. **Node.js**
   - **Why?**: Provides a scalable and efficient backend runtime.
   - **Use Cases**: Server-side logic and API handling.

2. **Express.js**
   - **Why?**: A lightweight framework for building RESTful APIs.
   - **Use Cases**: Defining API routes for event data, user authentication, and notifications.

3. **JWT (JSON Web Tokens)**
   - **Why?**: Secure user authentication and session management.
   - **Use Cases**: Ensuring authenticated routes and user sessions.

4. **Multer**
   - **Why?**: Handles file uploads such as event images and user profile pictures.
   - **Use Cases**: Enabling image uploads for events and profiles.

---

#### **Database**

1. **MongoDB**
   - **Why?**: A flexible, NoSQL database for managing user and event data.
   - **Use Cases**: Storing event information, user data, and relationships.

---

#### **Real-Time Communication**

1. **Socket.io**
   - **Why?**: Enables real-time event updates and chat features.
   - **Use Cases**: Notifications for event status, likes, and real-time communication.

---

#### **Deployment**

1. **Frontend Hosting: Vercel or Netlify**
   - **Why?**: Optimized for React apps with automatic deployment.
   - **Use Cases**: Hosting the frontend with global CDN and fast performance.

2. **Backend Hosting: Heroku or AWS**
   - **Why?**: Provides a reliable environment for backend services with scalability.
   - **Use Cases**: Hosting backend APIs and managing environment variables.

---

### **Workflow Overview**

This section describes the interaction between the frontend (React, Redux Toolkit), backend (Node.js, Express.js), database (MongoDB), and real-time features (Socket.io) for smooth event management and updates.

---

### **System Architecture**

This section illustrates the high-level architecture of the **Event Management Web App**, showing how users, the application, and its services interact.
![image](https://github.com/user-attachments/assets/6e6ba00e-97e4-4c63-b6e2-3070b7bc16ae)

---

### **Project Structure for Feature Implementation**

This project is structured to ensure a smooth, step-by-step approach to development, from authentication to event management, with each feature building upon the last.

**NOTE:** Customizations and feature improvements are encouraged to enhance user experience.

---

### **Week-by-Week Learning Plan**

#### **Week 1: Project Setup and Basic Authentication**
- **Tasks:**
  1. Install **Node.js**, **npm**, and **VSCode**.
     - **Reading**: [Node.js Installation](https://nodejs.org/en/download/)
     - **Video**: [Setting Up Node.js and npm](https://www.youtube.com/watch?v=TlB_eWDSMt4)
  2. Initialize backend and frontend projects.
     - **Reading**: [Express.js Basics](https://expressjs.com/en/starter/basic-routing.html)
     - **Video**: [Setting Up Express](https://www.youtube.com/watch?v=L72fhGm1tfE)
  3. Set up **JWT-based** authentication.
     - **Reading**: [JWT Authentication Guide](https://jwt.io/introduction/)
     - **Video**: [Secure Authentication with JWT](https://www.youtube.com/watch?v=7Q17ubqLfaM)

- **Deliverables:**
  - Functional login/signup system with JWT authentication.

---

#### **Week 2: Event Creation and Validation**
- **Tasks:**
  1. Create **event creation forms** with validation.
     - **Reading**: [React Forms Documentation](https://reactjs.org/docs/forms.html)
     - **Video**: [Form Handling in React](https://www.youtube.com/watch?v=JmZJkZyC6ts)
  2. Implement backend routes for event data storage.
     - **Reading**: [Express Routing](https://expressjs.com/en/guide/routing.html)
     - **Video**: [API Routing in Express](https://www.youtube.com/watch?v=pgpFFLCk6Lg)

- **Deliverables:**
  - Event creation form with proper validation and error handling.

---

#### **Week 3: Event Management Dashboard**
- **Tasks:**
  1. Create a **dashboard** to manage events.
     - **Reading**: [Managing State in React](https://reactjs.org/docs/state-and-lifecycle.html)
     - **Video**: [State Management in React](https://www.youtube.com/watch?v=35lXWvCuM8o)
  2. Implement **MongoDB integration** to fetch event data.
     - **Reading**: [MongoDB with Node.js](https://mongoosejs.com/docs/index.html)
     - **Video**: [MongoDB and Node.js Tutorial](https://www.youtube.com/watch?v=kWdeVdVZ8Ew)

- **Deliverables:**
  - A dashboard displaying events with CRUD functionality.

---

#### **Week 4: Real-Time Features**
- **Tasks:**
  1. Set up **Socket.io** for event notifications.
     - **Reading**: [Socket.io Documentation](https://socket.io/docs/v4/)
     - **Video**: [Building Real-Time Apps with Socket.io](https://www.youtube.com/watch?v=UUddpbgPEJM)
  2. Implement real-time notifications for event interactions.
  
- **Deliverables:**
  - Real-time notifications for events and chat features.

---

#### **Week 5: Deployment and Testing**
- **Tasks:**
  1. Test backend APIs using **Postman**.
     - **Reading**: [Postman Documentation](https://www.postman.com/docs/)
     - **Video**: [Testing APIs with Postman](https://www.youtube.com/watch?v=VywxIQ2ZXw4)
  2. Deploy the frontend and backend to **Vercel** and **Heroku**.
     - **Reading**: [Deploying on Heroku](https://devcenter.heroku.com/articles/deploying-nodejs)
     - **Video**: [Full-Stack App Deployment](https://www.youtube.com/watch?v=WA4djj2BjDc)

- **Deliverables:**
  - Fully deployed application with public URL.

---

### **Screenshots for Reference**
![Screenshot (229)](https://github.com/user-attachments/assets/cecccf91-f29b-43b7-8c5a-d6b4f182cb37)
![Screenshot (230)](https://github.com/user-attachments/assets/79edd19c-bb1e-40d5-8550-20a99bee12a6)
![Screenshot (231)](https://github.com/user-attachments/assets/51376cf3-6a2e-4c5d-8f45-93888b6d0841)
![Screenshot (226)](https://github.com/user-attachments/assets/2dd9a929-e739-46c4-b1a7-87a99699e007)
![Screenshot (227)](https://github.com/user-attachments/assets/112e7b35-088b-4237-8623-f38ee2069156)
![Screenshot (228)](https://github.com/user-attachments/assets/4b253aae-5bfb-4960-803f-4177e44b13d1)


---

### **References:**
1. [MERN Stack Tutorial](https://www.youtube.com/playlist?list=PLillGF-RfqbbiTGgA77tGO426V3hRF9iE)
2. [React Documentation](https://reactjs.org/docs/getting-started.html)
3. [Material-UI Documentation](https://mui.com/getting-started/installation/)
4. [MongoDB Documentation](https://www.mongodb.com/docs/manual/)
5. [JWT Documentation](https://jwt.io/)
6. [Postman Documentation](https://learning.postman.com/docs/getting-started/introduction/)
7. [Deploying on Heroku](https://devcenter.heroku.com/articles/deploying-nodejs)
8. https://www.youtube.com/watch?v=oUYqpjg-AVA
9. https://github.com/Zeeshu911/MERN_STACK_EVENT_PROJECT

---
