## React Application Basics
∧( 'Θ' )∧
a quick and hands-on assignment to reinforce React.js fundamentals, including setting up a project and managing state with `useState` by building a "Hello World" app and an interactive counter

### hello world
1. initialized a React app using `npx create-react-app my-app`
2. installed dependencies via `npm install` and started the local development server with `npm start`
3. customized the default App component to display a personalized greeting

### counter component
1. implemented `increment` and `decrement` functions within `Counter.js` using `useState`, ensuring the count doesn't drop below zero
2. updated `Name.js` to render a personalized name, then imported and displayed it inside `App.js`

### key takeaways
- **`create-react-app`**: gets a new React project set up with a standard build configuration
- **components**: building blocks that keep the UI code organized and easy to reuse
- **`useState`**: a React hook that lets components track and update their own local data (like the counter value)
