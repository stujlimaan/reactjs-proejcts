# Getting Start With Form

## Available Scripts

### `npm start`
start our project using npm start after that [https://localhost:3000](https://localhost:3000)

## JSX
- JSX stands for JavaScript XML. JSX allows us to write HTML in React. JSX makes it easier to write and add HTML in React.
- JSX (JavaScript Syntax Extension and occasionally referred as JavaScript XML) is a React extension to the JavaScript language syntax which provides a way to structure component rendering using syntax familiar to many developers. It is similar in appearance to HTML.
- JS is simply a scripting language, adding functionality into your website. JSX is an addition to the JavaScript syntax which is a mixture of both HTML and JavaScript. Both JS and JSX are interchangeable but JSX makes the code easier to understand for users.

### with jsx
    const myelement = <h1>I Love JSX!</h1>;
    ReactDOM.render(myelement, document.getElementById('root'));

### without jsx
    const myelement = React.createElement('h1', {}, 'I do not use JSX!');
    ReactDOM.render(myelement, document.getElementById('root'));
