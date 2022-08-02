Props :
Step 1 - Pass in props as an argument. We did that in the first line of the code above: function Tool(props){} . ...
Step 2 - Declare props variable(s) const name = props. ...
Step 3 - Use variable(s) in JSX template. ...
Step 4 - Pass data to props in the App component.

State :
Local state is most often managed in React using the useState hook. For example, local state would be needed to show or hide a modal component or to track values for a form component, such as form submission, when the form is disabled and the values of a form's inputs.
There are four main types of state we need to properly manage in our React apps:
Local state
Global state
Server state
URL state

Local (UI) state – Local state is data we manage in one or another component.

Global (UI) state – Global state is data we manage across multiple components.

Server state – Data that comes from an external server that must be integrated with our UI state.

URL state – Data that exists on our URLs, including the pathname and query parameters.