# Firebase-Google-Auth-Demo
A simple demonstration of how to implement Google authentication using Firebase in a Node.js backend project.

This project showcases how to set up Firebase, configure Google OAuth, and integrate authentication endpoints for secure user login.

 Firebase Authentication does not require review or manual approval to be used in production. No submission is necessary. Once authorized domains are set and Google sign-in is enabled in Firebase Console, it is fully operational in production.

**Prerequisites**

- Node.js and npm (or yarn) installed on your system. You can download them from the [official Node.js website](https://nodejs.org).

**Installation**

1. Clone this repository using git:

   ```bash
   git clone https://github.com/mjavason/...
   ```

2. Navigate to the project directory:

   ```bash
   cd project-name...
   ```

3. Install the project's dependencies:

   ```bash
   npm install
   ```

**Running the project**

There are four main scripts defined in this project's `package.json` file:

- **npm run dev**

  - This script is used for development purposes. It will start a development server and enable hot reloading.

- **npm run build**

  - This script is used to build the project for production. It will bundle your code, minify files, and store them in a 'build' folder.

- **npm run start**

  - This script starts the application in production mode. It's what you would typically run after building the project for deployment.

- **npm run test**
  - This script runs the project's tests. Make sure you've installed the packages before running this script.

**API Documentation**

After starting the API, you can access the documentation at the `/docs` route. Open your browser and go to [http://localhost:5000/docs](http://localhost:5000/docs) to view the API documentation.

**Additional Notes**

- Refer to the `package.json` file for any additional scripts specific to this project.
- Configuration files (e.g., `.env`) might be required for the project to run properly. Take a look at the `env.sample` file for a guide. Make sure you have them set up according to your environment.