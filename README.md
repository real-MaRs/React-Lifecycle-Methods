# React-Lifecycle-Methods

MOUNTING LIFECYCLE METHODS:

getInitialState/constructor: set initial state of component

componentWillMount: last minute prep before component mounts

Render: return html to the DOM

componentDidMount: fires after component mounts to DOM, good place to load external data


UPDATING LIFECYCLE METHODS:

componentWillReceiveProps: called before a component receives any new props, can compare current and new props and change state

shouldComponentUpdate: can return false if no update wanted

componentWillUpdate

render

componentDidUpdate: Operate on the DOM or perform network requests
