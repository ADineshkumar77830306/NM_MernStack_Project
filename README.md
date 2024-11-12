# Online Complaint Registery and Management System - MERN Stack Application

This is a full-stack application built using the MERN stack (MongoDB, Express, React, Node.js) to manage and track user complaints efficiently. Users can register complaints, track their status, and communicate with agents. Agents and administrators have tools to manage complaints and user interactions effectively.
## Table of Contents
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Environment Variables](#environment-variables)
- [Usage](#usage)
- [Features](#features)
  - [User Features](#user-features)
  - [Agent Features](#agent-features)
  - [Admin Features](#admin-features)
- [Tech Stack](#tech-stack)
- [Project Demo](#project-demo)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)
## Project Structure
The project is organized into two main folders:

- **frontend/** - Contains the front-end React code.
  - src/assets/Images - Stores images used in the frontend.
  - src/components/admin - Components for admin functionalities.
  - src/components/agent - Components for agent functionalities.
  - src/components/common - Common components like login, footer, and chat window.
  - src/components/user - Components for user complaint registration and tracking.

- **backend/** - Contains the back-end Node.js and Express code.
  - config/ - Database configuration.
  - controllers/ - Handles complaint, user, and agent operations.
  - middlewares/ - Authentication and error-handling middlewares.
  - routers/ - Defines routes for admin, agent, and user interactions.
  - schemas/ - Mongoose schemas for database models (e.g., complaints, users).

## Installation

### 1. Clone the Repository
```bash
git clone https://github.com/Bhuvaneshsonujiji/Online_learining_platform
cd Online_learining_platform
```

### 2. Install Dependencies

#### Server
```bash
cd backend
npm install
```

#### Client
```bash
cd frontend
npm install
```
## Environment Variables

Create a .env file in the backend folder with the following variables:

plaintext
MONGO_DB=mongodb://localhost:27017/complaint_registry
PORT=5000
JWT_KEY=my_super_secret_key_123456


- **MONGO_DB**: MongoDB connection string.
- **PORT**: Server port (default: 5000).
- **JWT_KEY**: Secret key for JSON Web Token (JWT) authentication.

## Usage

### Running the Server
bash
cd backend
node index.js

### Running the Client
The client will start on port 3000 by default.

bash
cd frontend
npm start


## Features

### User Features
- *Register Complaint*: Users can file a new complaint.
- *Complaint Status*: Track the status of filed complaints.
- *Chat with Agents*: Direct communication with agents assigned to complaints.

### Agent Features
- *Manage Complaints*: Agents can view and update complaint statuses.
- *User Communication*: Chat with users to resolve complaints.

### Admin Features
- *User Management*: View and manage all registered users.
- *Complaint Management*: View and manage all complaints in the system.
- *Agent Management*: Assign agents to specific complaints.
## Tech Stack

- *Frontend*: React, CSS
- *Backend*: Node.js, Express.js
- *Database*: MongoDB
- *Authentication*: JSON Web Token (JWT)

## Project Demo

Here’s a quick demo of the Online Complaint Registry, showcasing the main features, including complaint registration, status tracking, and communication between users and agents.

[Demo Video Link](https://drive.google.com/file/d/1vLnc1tKQ4VHGSNFwmg605xxRYjud0Lq-/view?usp=drive_link)

