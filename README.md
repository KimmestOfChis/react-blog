## Instructions
1. Clone the repository
2. Run `npm install` to install the dependencies
3. Run `npm start` to start the application
4. Open [http://localhost:3000](http://localhost:3000) to view it in the browser.
5. Run `npm test` to run the tests (optional)

Project Requirements
Use this fake API to fetch the data: https://jsonplaceholder.typicode.com/posts

Create a front end application that displays a list of posts. The application should have two pages:
- A page that displays a list of posts
- A page that displays a singular post with its details, I should be able to navigate to this page from the list of posts

You can use any (or no) styling or libraries
I recommend keeping your dependencies to a minimum, but you can use whatever you want

Confused? Ask for help! 
No question is a "stupid question" and we're happy to help you get started.
And we might just learn something by asking you questions too!

This project is purposefully open-ended. As you struggle to complete this project, you'll learn a lot!

| Endpoint                     | HTTP Method | Request Parameters | Response                                                                                                                                          |
|------------------------------|-------------|--------------------|---------------------------------------------------------------------------------------------------------------------------------------------------|
| `/posts`                     | GET         | -                  | Array of all post objects. Each object includes `id`, `title`, `body`, and `userId`.                                                               |
| `/posts/{id}`                | GET         | `id`               | Single post object with the given `id`, including `id`, `title`, `body`, and `userId`.                                                             |
| `/posts`                     | POST        | `title`, `body`, `userId` | New post object that was created, including `id`, `title`, `body`, and `userId`.                                                                  |
| `/posts/{id}`                | PUT         | `id`, `title`, `body`, `userId` | Updated post object with the given `id`, including `id`, `title`, `body`, and `userId`.                                                            |
| `/posts/{id}`                | DELETE      | `id`               | Empty object `{}`. The server responds with a 200 status code for a successful delete, even though no actual deletion occurs on the server-side. |
| `/posts/{id}/comments`       | GET         | `id`               | Array of all comment objects for the post with the given `id`. Each object includes `postId`, `id`, `name`, `email`, and `body`.                  |

## Prerequisites

Before you begin, make sure you have the following installed:

- Node.js and npm: You can download these from [here](https://nodejs.org/en/download/).
- A text editor: We recommend Visual Studio Code, which you can download from [here](https://code.visualstudio.com/download).

## Step 1: Set Up the Project

First, let's create a new React application using Create React App:

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

Start with `npm start`

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
