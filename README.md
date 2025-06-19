# Task 3: Design the Login Page Using NetBeans IDE (Design Window) 

A simple login page design using NetBeans IDE and Java Swing.

---

*COMPANY*: Main Flow Services and Technologies Pvt. Ltd. 

*NAME* : shiva kasula

*INTERN ID* : 17203

*DOMAIN* : Full Stack Web Development

*DURATION* : 8WEEKS



---

## Overview
This project demonstrates the design of a simple login page using NetBeans IDE and Java Swing. It focuses on GUI design without implementing backend functionalities.

---

## Features
- JFrame-based Login Form.
- Username and Password fields with tooltips.
- Centered window with aligned components.

---


## Prerequisites
To run or modify this project, you need:
- **Java Development Kit (JDK)**: Version 8 or higher.
- **NetBeans IDE**: Preferably version 12 or later.

---

## Installation Guide

### Step 1: Install JDK
1. Download the JDK:
   - Go to the [Oracle JDK Downloads](https://www.oracle.com/java/technologies/javase-jdk-downloads.html) or [OpenJDK](https://openjdk.java.net/).
2. Install the JDK by following the instructions for your operating system.
3. Set the `JAVA_HOME` environment variable:
   - **Windows**:
     - Go to System Properties > Advanced > Environment Variables.
     - Under "System variables," click `New` and add:
       - Variable Name: `JAVA_HOME`
       - Variable Value: Path to your JDK installation (e.g., `C:\Program Files\Java\jdk-17`).
     - Add `%JAVA_HOME%\bin` to the `Path` variable.
   - **Mac/Linux**: Add `export JAVA_HOME=/path/to/jdk` in your `.bashrc` or `.zshrc`.

### Step 2: Install NetBeans IDE
1. Download NetBeans:
   - Visit the [NetBeans Downloads page](https://netbeans.apache.org/download/).
   - Choose the appropriate version for your operating system.
2. Install NetBeans:
   - Run the installer and follow the on-screen instructions.
   - Ensure the JDK is correctly detected during installation.
3. Launch NetBeans:
   - Open the application and set up a new project workspace if prompted.

---

## Getting Started

### Step 1: Create a New JFrame Form
1. **Open NetBeans IDE**:
   - Launch the IDE on your computer.
2. **Create a New Project**:
   - Go to `File > New Project`.
   - In the "New Project" wizard:
     - Select `Java` under "Categories."
     - Select `Java Application` under "Projects."
     - Click `Next`.
   - Name the project (e.g., `LoginApp`) and click `Finish`.

---



## Design Steps
1. **Create a JFrame Form**:
   - Project Name: `LoginApp`
   - JFrame Name: `LoginForm`

2. **Design Components**:
   - Title: `Login Page`
   - Labels: `Username:` and `Password:`
   - Fields: `JTextField` for username and `JPasswordField` for password.
   - Button: `Login`

3. **Customize Layout**:
   - Used `GroupLayout` for alignment.
   - Set window size to `400x300` and centered it.

4. **Test the Design**:
   - Verified component alignment and functionality in design view.

## How to Run
1. Open the project in NetBeans IDE.
2. Press `Shift + F6` to run the application.
3. The login page should display correctly with all components aligned.

## Next Steps (Optional)
- Implement backend validation for login credentials.
- Connect the form to a database for dynamic validation.

---

