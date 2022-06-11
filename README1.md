# Setting up the ReactJS
npx create-react-app my-react-app or npx create-react-app ./(to add in current directory.)
It generates all files, packages and folders to start the react application and run in the browser. To run this App you need node install in your PC
Node(NodeJS) is JavaScript runtime that allows us to execute JS code on the server. 
npm run start -> To start the server.

# Explore the Files in React App
1. In src folder, you will add your logic and give all your time in building the react App to src folder. package.json file constains all packages that are installed.
2. In Public Folder, you hv index.html file hving div with id = root.
3. In index.js in src Folder,React DOM is used to render the components in our entire application,into the real DOM more specifically in a Div of id root. We injected all the components in this div hving id root.
4. App.js -> We hv discussed Functional components are used nowadays, not the Class based functions. We hv JSX in this Folder not HTML, both are differnt, but incredibly similar changes are we use className instead of class in JSX. You can directly render html data inside your javascript.
Power of React is you can directly put Javascript code inside the HTML code using {} brackets dynamically.
<></> -> to add two lines of code in one () brackets.