# SEcure-Auth
MERN Stack App with Login System

Welcome to MERNSEcureAuthentication
Hello everyone, In this project, we are going to create a MERN Stack App with a Login System. how to create login, registration, profile, reset password routes, and learn how to send Mail from the Node.js backend application.

Working with the Project
Create two configuration files for the project. First in the client and second in the server.

In the Client Folder create a .env file and put this code inside it.

.env

REACT_APP_SERVER_DOMAIN='<server_domain>' # example 'http://localhost:8080'
After that create a file in the Server Folder with the name config.js and put the below code inside it.

config.js

export default {
    JWT_SECRET : "<secret>",
    EMAIL: "steve.franecki@ethereal.email", // testing email & password
    PASSWORD: "sMf46xCzrvdrxvuagc",
    ATLAS_URI: "<MONGODB_ATLAS_URI>"
}
Note: The ATLAS_URI is important to work on this project.

Now, create all these variables in the project and make sure you set the ATLAS_URI variable.
