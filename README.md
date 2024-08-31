# User Management Web Application

## Overview

This project is a simple web application that allows users to view, add, edit, and delete user details. It uses JSONPlaceholder as a mock backend API for demonstration purposes.

## Features

- **View Users**: Display a list of users with details such as ID, First Name, Last Name, Email, and Department.
- **Add User**: Add a new user with validation for user input.
- **Edit User**: Edit details of an existing user.
- **Delete User**: Remove a user from the list.
- **Pagination**: Navigate through pages of users.
- **Notifications**: Display notifications for user actions (add, edit, delete).

## Tech Stack

- **Frontend**: React.js, Redux, Tailwind CSS
- **Backend**: JSONPlaceholder (mock API)
- **State Management**: Redux Toolkit
- **Routing**: React Router
- **Notifications**: React-Toastify

## Usage

### Home Page

- Displays a list of users with pagination controls.
- You can navigate to the Add User page or use the Edit and Delete buttons for each user.

### Add User Page

- Fill in the form with user details (First Name, Last Name, Email, Department) and submit to add a new user.
- Validation errors are displayed for invalid inputs.
- The Cancel button redirects to the home page without saving changes.

### Edit User Page

- Edit details of an existing user.
- The form is pre-filled with the current user's information.
- After editing, the changes are saved, and the user is redirected to the home page.
- The Cancel button redirects to the home page without saving changes.

### Error Handling

- Network Errors: Notifications are displayed if API requests fail.
- Validation Errors: Form validation errors are shown on the Add and Edit User pages.

### Bonus Features

- Pagination: Allows users to navigate through pages of users.
- Responsive Design: The interface adapts to various screen sizes.
- Client-Side Validation: Ensures user input is valid before submission.

### Assumptions

- The JSONPlaceholder API is used as a mock service and does not persist data.
- The application is designed to work in modern browsers.
