# Student Form Management System

A dynamic web application that collects student information and displays it in a tabular format.

## Features

- Student form with various input fields
- Data submission and redirection to display page
- Tabular display of submitted data
- Navigation buttons for seamless user experience

## Pages

### 1. Student Form Page (`student_form.html`)

The main form page where users enter student information.

**Form Fields:**
- First Name (required)
- Last Name (required)
- Student ID (required)
- Date of Birth (required)
- Gender (radio buttons, required)
- Hobbies (checkboxes)
- Email (required)
- Password
- Self-description (textarea)
- Skills (dropdown)

### 2. Data Display Page (`student_db.html`)

Displays submitted data in a tabular format with two buttons:

>
<button onclick="window.location.href='student_form.html'">Back to Form</button>
<button onclick="window.location.href='student_javascript_info.html'">View Code Explanation</button>

### 3. Data Display Page (`student_javascript_info.html`)

This page provides detailed explanations of the JavaScript code used in the project.

### Features

- Line-by-line breakdown of the JavaScript implementation
- Clear explanations of key functions and methods  
- Important notes about security and implementation details
- Navigation button to return to the main form

### Navigation Button

```html
<button onclick="window.location.href='student_form.html'">Back to Home</button>
