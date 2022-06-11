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
<></> -> to add two lines of code in one () brackets known as React Fragment.
-> Components division in React

# Props in React
-> Props is important part of the react.It allows you to pass the naming data through react components. Props are arguments that you pass in the react components. They are pass by the attribute. Every component i.e every function has props as default argument

# Components in React
-> Component is a piece of code that returns or renders some JSX, and we can call person component in any other component.
-> By using props we can write the diffent data in the function.
-> We can have Many more things like Hobbies, College Name etc. and if we not use custom components then it would becomes messy, and we hv to write the JSX every single time.But if we another component then we need to simply call it every time in a single line and pass the dynamic properties based on the person.   

# State in React
State is a plane JS object used in react to represent piece of information about the components. We hv to import state to use it in our webpage.
Purpose Of using State is -> We made counter and if I increase or decrease the number, it doesn't works out.
But now we use state include by using function of useState(), whenever you call the function and it starts with use in react we called it as **hooks**
We use the syntax and named like (counter, setCounter) setCounter is function to set the counter and also put initial value in the function as 0.
When you give the counter, it's initial state is 0, We hv to write the events like onClick event.
And write the Call back Function in that event. Calback function is the function with it's name and comment.
And We made counter as Dynamic as Application on react.
Without Reloading the page we worked on the features on the webpage.
When we talking about states we hv to about hooks,without hooks state is not possible.
Go through the documentation of React once. 