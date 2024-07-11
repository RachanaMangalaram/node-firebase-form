# Node Firebase Form

## Overview

This project is a simple form submission application built with Node.js, Express and Firebase.The application allows users to fill out a form, and upon submission, store the data in Firestore.


## Setup and Run Locally

### Prerequisites

- Node.js (v14 or higher)
- npm (v6 or higher)
- Firebase Account

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/node-firebase-form.git
   cd node-firebase-form
2. Install dependencies:
     ```bash
   npm install
3. Set up Firebase:
   - Go to the Firebase Console.
   -  Create a new project or use an existing one.
   -  Navigate to the project settings and generate a new private key for your Firebase Admin SDK.
   -  Download the serviceAccountKey.json file and save it in the root directory of your project.
   -  Rename the file to firebase-service-account.json.
     
4. Start the application:
   ```bash
   npm start
The application should now be running on http://localhost:3000.
