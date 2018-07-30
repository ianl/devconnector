# DevConnector

### A social network for developers. Project from ['MERN Stack Front To Back: Full Stack React, Redux & Node.js'](https://www.udemy.com/mern-stack-front-to-back/) Udemy course.

#### See it live [HERE](https://dcnetwork.herokuapp.com)

## Quick Start

```bash
# Install dependencies for server
npm install

# Install dependencies for client
npm run client-install

# Run the client & server with concurrently
# (Server runs on http://localhost:5000 and client on http://localhost:3000)
npm run dev
```

You will need to create a keys_dev.js in the server config folder with:

```
module.exports = {
  mongoURI: 'YOUR_OWN_MONGO_URI',
  secretOrKey: 'YOUR_OWN_SECRET'
};
```

## Technology

Built with the MERN stack (MongoDB, Express, React + Redux and Node.js). Utilizes GitHub API to display latest GitHub repositories of users in their profiles.
