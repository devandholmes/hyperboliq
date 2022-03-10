This project was bootstrapped with Create React App.

Available Scripts
In the project directory, you can run:

npm start
Runs the app in the development mode.
Open http://localhost:4000 to view it in the browser.

The page will reload if you make edits.
You will also see any lint errors in the console.

Instead of downloading the entire app before users can use it, code splitting allows you to split your code into small chunks which you can then load on demand.

This project setup supports code splitting via dynamic import(). Its proposal is in stage 4. The import() function-like form takes the module name as an argument and returns a Promise which always resolves to the namespace object of the module.

The API is proxyed through the front end allowing you to make API calls very easily


To start the Project do as follow : 

cd api          -- First open a terminal in the API folder
npm start       -- Start the API using the npm start script found in the package.json
cd ../client    -- Then open the Terminal in the Client Folder
npm start       -- and start the front end by using the script found in the package.json

The IMDB API provided no longer works and has since been taken off the site, i tried to make due by using another API that does similar, but i just ran out of time between loadshedding and my current work