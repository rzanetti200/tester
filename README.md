
This Job Portal is a comprehensive web-based Job Portal application utilizing the MERN Stack (MongoDB, Express.js, React.js, Node.js). The platform facilitates seamless user registration as either applicants or recruiters, and features persistent login sessions safeguarded by JWT token verification. Recruiters can post, edit, or delete job listings, and manage applications by viewing resumes and altering application statuses. Applicants are equipped to browse job postings through an intelligent fuzzy search, apply with a Statement of Purpose, upload resumes, and modify profiles. 


## Guidelines for Job Portal Web App Initialization:

1. Install Node.js and MongoDB on your system.
2. Initiate the MongoDB server by running `sudo service mongod start`.
3. Navigate to the backend directory by entering `cd backend`.
4. Install the necessary dependencies within the backend directory by executing `npm install`.
5. Start the Express server with the command `npm start`.
6. The backend server will initiate on port 4444.
7. Then, navigate to the frontend directory by executing `cd ../frontend`.
8. Install the necessary dependencies within the frontend directory by executing `npm install`.
9. Kickstart the web app's frontend server by entering `npm start`.
10. The frontend server will begin operating on port 3000.
11. Finally, access `http://localhost:3000/` in your web browser and commence creating job listings and applications by registering under the appropriate categories.

## Dependencies:

- Frontend:
  - @material-ui/core
  - @material-ui/icons
  - @material-ui/lab
  - axios
  - material-ui-chip-input
  - react-phone-input-2
- Backend:
  - bcrypt
  - body-parser
  - connect-flash
  - connect-mongo
  - cors
  - crypto
  - express
  - express-session
  - jsonwebtoken
  - mongoose
  - mongoose-type-email
  - multer
  - passport
  - passport-jwt
  - passport-local
  - uuid





