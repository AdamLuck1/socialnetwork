# React Social Network

A photosharing social network powered by ReactJS, Express and Firebase Storage / Authentication / Real-Time Database

### Working:

- Login or Registering with Email
- Uploading photos w/ description
- Commenting
- Liking photos
- Photo Tags
- Following users
- Sharing link
- Searching users
- Profile page displays uploads / liked photos
- Changing profile pic and bio
- Editing photo description
- Deleting photos
- Displaying number of likes for post
- Displaying number of followers and following in profile
- Displaying photos from followed users in main
- Displaying updates from followed users in sidebar
- Front-end routing
- Error page redirection
- Protected routes
- Express backend connected to react
- Authentication with Firebase Auth
- File storage with Firebase Storage
- Database with Firebase Real-Time Database

### TO-DO:

- Image compression
- Search photos by tags

### Roadblocks:

- Its difficult to make simple queries using Firebase.
- Unable to query substrings for searching users and photos.
- Unable to sort photos by time

### Setup:

run express backend in seperate terminal

```
cd react-social-network
set PORT=3001 && node server.js
```

run react development server

```
cd client
npm start
```
