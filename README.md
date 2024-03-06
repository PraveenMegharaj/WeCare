# CH_2023_Java_Team3
# We Care

## Overview
"WeCare is a user-friendly website designed to empower citizens by providing a platform to voice their complaints and concerns regarding city streets. The primary focus is on facilitating a seamless process for users to raise issues related to roads, track the progress of their complaints, and, when necessary, escalate matters. External users, representing the common citizens, are encouraged to register on the platform to actively participate in improving their local infrastructure. Meanwhile, internal users, comprising city officers responsible for addressing these concerns, can be created and managed through the Officers Admin page. The website ensures a smooth user experience with a prominently placed logout button at the top right corner, allowing individuals to effortlessly navigate back to the landing page and login screen when needed."

## Table of Contents
- [Features](#features)
- [Technology Stack](#technology-stack)
- [Installation](#installation)
- [Usage](#usage)
  - [User Authentication](#user-authentication)
  - [User Signup](#user-signup)
  - [Admin Dashboard](#admin-dashboard)
  - [Officer Dashboard](#officer-dashboard)
  - [User Dashboard](#user-dashboard)
- [Additional](#additional)

## Features
- User-friendly interface for both users and admins.
- Secure login and authentication mechanisms.
- Ability to raise complaint and get solution for the complaint.
- Personalized snapshots and visualizations.
- Complaint history and tracking based on status of complaint.
- User profile management and password change capabilities.
- Admin profile management and password change capabilities.
- Officer profile management and password change capabilities.
- Admin controls for managing Jurisdiction and Officers.

## Technology Stack
- Database: MySQL
- Frontend: HTML+Thymeleaf, CSS, JavaScript
- Backend: Hibernate, Spring Boot

## Installation
1. Clone the repository: git clone https://github.com/IN-Valtech/CH_2023_Java_Team3.git
2. Set up the MySQL database and configure the connection in the application.
3. Navigate to the project directory and run the application: mvn clean spring-boot:run
4. Access the application at [http://localhost:9006](http://localhost:9006)

## Usage
### User Authentication
- Use your email and password to log in.
- Based on the role mapped in the database, you will be directed to the buyer or seller dashboard.

### User Signup
- Provide your name, email, password, and select whether you are a admin,user and officer.
- Optionally, enter the code sent to mail for email verification.

### Admin Dashboard
- View all complaint details.
- Navigate to the Jurisdiction and Officer mangement page.

### Officer Dashboard
- View all complaint details which is assigned to respective officer
- Add can respond to complaint.

### Officer Dashboard
- View all complaint details which are created by respective user.
- Add can create complaint.

## Additional
- User/Officer/Admin can change password.
- User/Officer can edit their profile.

Note: This documentation serves as a guide for the We Care platform. For any inquiries or issues, please refer to the [GitHub repository](https://github.com/IN-Valtech/CH_2023_Java_Team3) or contact the project team.