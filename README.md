# ColdMailProject

`ColdMailProject` is a `MERN Stack` web application that allows users to create and manage automated email sequences using a flowchart interface. This application uses `React Flow` for visualizing the flowchart, `Agenda` for email scheduling, and `Nodemailer` for sending emails.

## Features

- **Flowchart Interface**: Intuitive interface for creating email sequences.
- **Node Types**:
  - **Lead-Source**: Defines the recipient of the email sequence.
  - **Cold-Email**: Represents an email to be sent with a subject and content.
  - **Wait/Delay**: Adds a delay between emails.
- **Scheduling**: Automatically schedules and sends emails based on the flowchart.
- **Modal Forms**: Easy-to-use forms for adding and editing nodes.
- **Backend Integration**: Node and edge data are sent to the backend to start the email sequence process.

## Technologies Used

- **Frontend**:
  - React
  - React Flow
  - Axios
  - Modal from react-modal
- **Backend**:
  - Node.js
  - Express
  - Agenda
  - Nodemailer
  - MongoDB (via Mongoose)

## Installation

### Create .env

Create .env files for both frontend and backend
```
# Backend .env
PORT = 5000
ORIGIN = http://localhost:5173
MONGODB_URI = 
MAILTRAP_HOST = smtp.gmail.com
MAILTRAP_PORT = 587
MAILTRAP_USER = 
MAILTRAP_PASSWORD = 


# Frontend .env
VITE_BASE_URL = http://localhost:5000
```

### Install dependencies

```bash
# Backend

cd backend
npm install

# Frontend

cd frontend
npm install
```

### Start the Backend & Frontend

```bash
# Backend

cd backend
npm run dev

# Frontend

cd frontend
npm run dev
```

### Open the application

Open your browser and navigate to http://localhost:5173 to view the application.


## Screenshots
Enter E-mail Address
![EnterEmailAdd](./Screenshots%20&%20Video/EmailAddress.png)

Enter wait / Delay Time
![Wait / Delay Time](./Screenshots%20&%20Video/WaitDelayTime.png)

Enter Cold Mail Subject / Body
![SubBody](./Screenshots%20&%20Video/coldMailDetail.png)

Demo Video: https://youtu.be/bbHYAVLJPok




