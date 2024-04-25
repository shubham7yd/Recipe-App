# Recipe Sharing Full Stack App (MERN Stack)


1. Open the folder and open terminal:


2. Navigate to the project directory:

       cd Mern-Recipe-App   

3. Navigate to the client directory:
     
       cd client 
       cd my-app 

4. Install client dependencies:

       npm install 

5. Return to the project root:

       cd ..
       cd ..

6. Navigate to server folder:

       cd server

7. Create a `.env` file in the project root and configure your environment variables:
   
       PORT=2000
       MONGODB_URI=mongodb://localhost/recipe-app
       SECRET=your-secret-key

Replace `your-secret-key` with a secure secret for JWT token generation.

8. Start the development server

       node index.js


## Folder Structure
The project follows a standard MERN stack folder structure:

- client: Contains the React frontend application.
- server: Contains the Express.js backend application.
- Schema: Define the MongoDB schemas and models.
- routes: Define the API routes.
- controllers: Handle route logic and interact with the database.
- middlewares: Custom middleware functions.
- db: Configuration files (e.g., database connection).
