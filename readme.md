This project is a simple notes app that is built using React as front end and Node/Express as backend.

Steps to start the project locally:
    
    1. Clone the project to a local folder using git clone "repo link"
    2. Project has two folders, backend and frontend, we need to start server for both.
    3. cd into the frontend folder, run: {npm install} this will install all the dependencies required for the frontend
    4. Check the scripts in the package.json to run the server, run: {npm start} in the directory where package.json is present
    5. Frontend should be up and running.
    6. Now cd into the backend folder on another terminal.
    7. Run: {npm install}, to install all the dependencies.
    8. Run: {node index.js} in the backend folder (index.js file should be present here).
    9. Now your backend and frontend are both running locally.


Common Errors:

    error:0308010C:digital envelope routines::unsupported at new Hash (node:internal/crypto/hash:69:19)
    You may encounter this error while running 'npm start' in frontend.
    To resolve: 
        1. go to package.json of frontend and replace start script with "react-scripts --openssl-legacy-provider start"

