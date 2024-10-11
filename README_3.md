# React
### React and JSX Essentials

1. **React**: is a popular library used to create user interfaces. React components use Pascal case (or upper camel case) variable names
2. **JSX**: Stands for JavaScript XML. It allows you to write HTML-like syntax in your JavaScript.

4. **Props**: Short for properties, props are how data is passed from a parent component to a child component.

5. **State**: Used to store and manage data within a component. It allows components to respond to user inputs or updates.

6. **Virtual DOM**: A key feature that optimizes rendering performance by minimizing direct updates to the actual DOM.

7. **Passing Data**: You can send data from a parent to a child component using props.

8. **React Hooks**: Special functions that let you use state and other React features in functional components.

9. **useEffect Hook**: This hook is used for handling side effects in functional components, like fetching data or directly manipulating the DOM.

10. **JSX Syntax**: Similar to XML or HTML, making it intuitive for those familiar with web markup.

11. **ReactDOM Library**: Responsible for rendering React components into the DOM, essentially connecting React with the browser.

12. **Event Handling**: In React, you define event handlers directly in JSX, making it straightforward to manage user interactions.

13. **useState Hook**: This hook is specifically for managing state in functional components.

14. **Component Benefits**: React components promote reusable and modular code, making it easier to maintain and scale applications.

15. **render() Function**: Responsible for rendering the component's output (HTML) to the DOM.

16. **Key Prop**: Essential for lists, it provides a unique identifier for each item, helping React efficiently update the UI.

17. **Conditional Rendering**: Achieved using ternary operators or logical operators (like `&&`) within JSX.

18. **forwardRef Function**: Allows refs to be passed to child components, enabling direct DOM manipulations when needed.

19. **Key Prop in Lists**: Again, it's about specifying unique identifiers to optimize rendering of list items.

20. **memo Function**: Used to memoize component rendering, which can improve performance by preventing unnecessary re-renders.

21. **Updating State in Class Components**: You do this using the `setState()` method, which schedules updates to the component's state.

22. **Context API**: A powerful tool for sharing data between components without having to pass props through every level of the component tree.

23. **createContext Function**: This function creates a context object, which is part of the Context API.

24. **Asynchronous Operations**: Handled in React using `async` and `await` within functional components for cleaner, more manageable code.

25. **Router Component**: In React Router, this component manages rendering different components based on the current URL.

26. **Defining Routes**: You define routes by importing the `Route` component from the `react-router-dom` library.

27. **NavLink Component**: Used for navigation links, it comes with built-in styling for the active route.

28. **withRouter HOC**: A higher-order component that provides routing props (like match, location, and history) to any wrapped component.

29. **Link Component**: Similar to `<a>` tags in HTML, but it allows navigation between routes without a full page refresh.

30. **Accessing URL Parameters**: You can access parameters in the URL via the `params` object found in the `match` prop.

31. **Switch Component**: Renders the first child route that matches the current URL, useful for exclusive routing.

32. **Exact Prop**: Ensures that the route matches the exact URL path, preventing partial matches.

<p>Component: is an independent, reusable code block which divides the UI into smaller pieces.</p>
<ul>
    <li>Functional component - is basically a JavaScript/ES6 function that returns a React element (JSX)</br>
    
```html
    <script>
        function Welcome(props) {
              return <h1>Hello, {props.name}</h1>;
        }
    </script>
```
</li>
    <li>Class-based component - are ES6 classes that return JSX, must have an additional render( ) method for returning JSX.<br>

```html
    <script>
    class Welcome extends React.Component {
      render() {
        return <h1>Hello, {this.props.name}</h1>;
      }
    }
    </script>
```
</li>
    
    <li>Presentational component - </li>
    <li>Container components - </li>
</ul>
