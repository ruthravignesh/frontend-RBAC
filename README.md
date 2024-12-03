# VRV Security’s Frontend Developer Intern Assignment

## **Role-Based Access Control (RBAC) UI**

### **Project Overview**
This project is a frontend implementation for a **Role-Based Access Control (RBAC)** system as part of VRV Security’s Frontend Developer Intern Assignment. It features an admin dashboard where users, roles, and permissions can be managed efficiently. The focus is on providing a user-friendly and secure interface that meets the specified core requirements while showcasing technical and design skills.

---

### **Features**

#### **User Management**
- View a list of all users in a tabular format.
- Add new users with a modal form.
- Edit user details, including assigning roles.
- Delete users securely with a confirmation dialog.
- Toggle user status between Active and Inactive.

#### **Role Management**
- View and manage a list of roles.
- Create new roles and assign permissions.
- Edit existing roles, including modifying associated permissions.
- Delete roles securely with confirmation.

#### **Dynamic Permissions Management**
- Assign, view, and modify permissions for roles dynamically.
- Visual indicators for permission states (e.g., Read, Write, Delete).

#### **Additional Features**
- **Search and Filter:** Quickly find users or roles with search and filter functionality.
- **Sorting:** Sort tables by columns like name, role, or status.
- **Pagination:** Handle large data sets with efficient pagination.
- **Responsive Design:** Fully responsive layout for seamless experience on desktop, tablet, and mobile devices.
- **Mock API Integration:** Simulate server interactions for CRUD operations using mocked API calls.

---

### **Technology Stack**
- **Frontend Framework:** React.js
- **UI Components:** Material-UI (MUI)
- **State Management:** Redux
- **Routing:** React Router
- **Styling:** CSS-in-JS with Emotion
- **API Simulation:** Axios with Mock Adapter
- **Tooling:** Webpack, Babel, ESLint

---

### **Setup Instructions**

#### Prerequisites
Ensure you have the following installed:
- Node.js (>= 16.0.0)
- npm or yarn

#### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/vrv-rbac-ui.git
   ```
2. Navigate to the project directory:
   ```bash
   cd vrv-rbac-ui
   ```
3. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```
4. Start the development server:
   ```bash
   npm start
   # or
   yarn start
   ```
5. Open the application in your browser at:
   ```
   http://localhost:3000
   ```

---

### **Usage Guide**

#### Accessing the Dashboard
- Navigate to the **Users** section to manage users.
- Use the **Roles** section to define and edit roles.
- Modify permissions directly from the **Permissions** tab or inline within the Roles section.

#### Managing Users
- Click **Add User** to open a modal form for creating a new user.
- Use the **Edit** button to modify user details or assign a role.
- Delete a user by clicking the **Delete** button, followed by confirmation.

#### Managing Roles
- Click **Add Role** to create a new role.
- Use the **Edit** button to update the role name or permissions.
- Remove a role by clicking the **Delete** button and confirming.

---

### **Project Structure**
```
vrv-rbac-ui/
├── public/               # Static assets
├── src/
│   ├── components/       # Reusable components (e.g., Modals, Tables)
│   ├── pages/            # Main pages (e.g., Dashboard, Users, Roles)
│   ├── store/            # Redux store and slices
│   ├── utils/            # Utility functions (e.g., API mocks)
│   ├── App.js            # Main application component
│   ├── index.js          # Application entry point
├── package.json          # Project dependencies and scripts
└── README.md             # Project documentation
```

---

### **Security Practices**
- Input validation for forms to prevent XSS and invalid data.
- Role-based conditional rendering to restrict access to sensitive features.
- Error handling for all API interactions.
- Secure deletion with confirmation dialogs to prevent accidental data loss.

---

### **Future Enhancements**
- Integration with a real backend API.
- Implement authentication and session management.
- Role hierarchy for nested permissions.
- Enhanced analytics dashboard for user and role statistics.

---

### **Submission**
To test the project, clone the repository and follow the setup instructions.

For feedback or questions, feel free to reach out.

---

Thank you for the opportunity to showcase my skills through this assignment!
