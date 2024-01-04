# SyncDocs

This is a Google Docs clone built using React.js, Quill.js, Socket.io, and MongoDB. It allows users to collaborate on text documents in real-time.

![Screenshot (92)](https://github.com/mishrayash/SyncDocsClient/assets/80852441/ef20cc7b-4836-4150-b028-f8b3765ec4e1)


# Features

Real-Time Collaboration: Multiple users can simultaneously edit and view changes in real-time.

Rich Text Editing: Utilizes Quill.js for a rich text editing experience, including formatting options such as bold, italic, underline, and more.

Dynamic Document Creation: Automatically generates a unique document ID using UUIDv4 when a user accesses the application.

Auto-Save Functionality: Periodically saves document changes to the server, ensuring that the latest content is always available even after a page refresh.

Document History: Keeps track of document changes, allowing users to review and revert to previous versions.

User-Friendly Interface: Simple and intuitive UI design for a seamless writing experience.

# Technologies Used

React.js: Frontend development for building dynamic user interfaces.

Quill.js: Powerful WYSIWYG editor for rich text editing capabilities.

Socket.io: Enables real-time, bidirectional, and event-based communication between clients and the server.

MongoDB: A NoSQL database for storing document data.

# Getting Started

Clone the repository.

Install dependencies using npm install in both the client and server directories.

Get the server repository from https://github.com/mishrayash/_syncdocs/tree/master/server

Start the server using npm start in the server directory.

Run the client using npm start in the client directory.

Access the application in your browser at http://localhost:3000.

Feel free to contribute or report issues by opening a pull request or creating an issue in the repository. Happy collaborating!



# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
