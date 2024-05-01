## Backend technology

### Framework/Library and modules

1. For handling HTTP requests and building RESTful APIs, I have used `Express.js` web framework.
2. To work with MongoDB, I have used `Mongoose` as the ODM (Object Data Modeling) library.
3. For user authentication and authorization, I have incorporated `JWT` (JSON Web Tokens).
4. To securely hash passwords, I have used `bcrypt` library.
5. For file storage and retrieval, I have integrated `Amazon S3` service.
6. To manage access control for AWS resources, I have utilized `IAM` (Identity and Access Management) service.

## Project setup

1. Clone the repository from GitHub.
2. Install the required dependencies using the command `npm install`.
3. Create a `.env` file in the root directory and configure the following environment variables:
   - `MONGODB_URI`: MongoDB connection string
   - `JWT_SECRET`: Secret key for JWT token generation
   - `AWS_ACCESS_KEY_ID`: AWS access key ID for S3 integration
   - `AWS_SECRET_ACCESS_KEY`: AWS secret access key for S3 integration
   - `AWS_BUCKET_NAME`: Name of the S3 bucket for file storage

## Running the server

Use the following command to start the server:

You may use npm or yarn. Like `yarn` and `yarn start` <br />

`npm install` <br />
`npm start` <br />
<br />
<br />

# Documentation

Here I have discussed about which technology I have used, and why used. <br />

## Server side technology

### Framework/Library and modules

1. I have used `node.js` runtime environment for server side
2. `Express.js` web framework
3. To validate request, I have used `express-validator`

## Decision

1. `Why nodejs/Express?: ` Node. js uses non-blocking, event-driven I/O to remain lightweight and efficient in the face of data-intensive real-time applications that run across distributed devices.
2. I have used pagination instead of loading all data at a time. Initially, it loads 10 items
3. Authentication, authorization, user verify, recover password are added to this app
