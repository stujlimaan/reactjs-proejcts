# Getting Start With Form

## Available Scripts

### `npm start`
start our project using npm start after that [https://localhost:3000](https://localhost:3000)

## Functional Component
- A functional component is just a plain JavaScript function that accepts props as an argument and returns a React element.
- Functional components are functions that takes in props and return JSX. They do not natively have state or lifecycle methods, but this functionality can be added by implementing React Hooks. Functional components are usually used to display information. They are easy to read, debug, and test.
- There is no render method used in functional components.
- Also known as Stateless components as they simply accept data and display them in some form, that they are mainly responsible for rendering UI.
- React lifecycle methods (for example, componentDidMount) cannot be used in functional components.
- Hooks can be easily used in functional components.

### 
    example: const [name,SetName]= React.useState("")
- Constructors are not used .

### 
    function Car() {
    return <h2>Hi, I am a Car!</h2>;
    }


## Class Component
A class component requires you to extend from React. Component and create a render function which returns a React element.

- It must have the render() method returning HTML.
- Also known as Stateful components because they implement logic and state.
- React lifecycle methods can be used inside class components (for example, componentDidMount).
- It requires different syntax inside a class component to implement hooks.
### 
    example: constructor(props) {
    super(props);
    this.state = {name: ""}
    }
- It requires different syntax inside a class component to implement hooks.
### 
    example: constructor(props) {
    super(props);
    this.state = {name: ""}
    }
###
    class Car extends React.Component {
    render() {
    return <h2>Hi, I am a Car!</h2>;
    }
    }


