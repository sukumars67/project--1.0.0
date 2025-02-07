# **Navigation Flow - To-Do List App**  

## **App Navigation Structure**  

### **1. Authentication Flow**  
- **Splash Screen** → Displays app logo & loading animation  
- **Login Page** → User authentication (Email/Google Login)  
- **Signup Page** → New user registration  

### **2. Main App Navigation**  
- **Dashboard (Home Page)** → Displays all tasks in categories (Pending, Completed, Important)  
- **Task Management Page** → Create, edit, delete, and set reminders for tasks  
- **Profile Page** → User profile & settings  
- **Settings Page** → Theme selection, notification preferences  
- **Logout** → Option to sign out  

### **3. Web Navigation (React Router)**  
- `/login` → Login Page  
- `/signup` → Signup Page  
- `/dashboard` → Main task list  
- `/task/:id` → Task details & edit  
- `/profile` → User profile  
- `/settings` → App settings  

### **4. Mobile Navigation (React Navigation)**  
- **Stack Navigator**  
  - Home → Displays task list  
  - Task Details → Edit/Delete tasks  
  - Profile → Update user info  
  - Settings → Manage preferences  

### **User Journey Example**  
1. **New user opens the app → Signs up → Lands on the dashboard.**  
2. **Creates a new task → Adds a due date & reminder.**  
3. **Completes a task → Marks it as "Done".**  
4. **Navigates to Profile Page → Updates settings.**  
5. **Logs out when done.**  
