# fb-react-demo
an intro to react 
![](https://reactjs.org/logo-og.png)

### What is React?
- An open source front end library 
- Created at FB by Jordan Walke at Facebook in 2011
- Went open source in 2013

### Advantages of React
- Reusable Components
- Virtual DOM for faster load times
- Change data without refreshing the page
- SEO friendly
- Fun to learn and easier to develop in

### Components
- Key building block for React site development
- 2 main types, class and functional
- Traditionally only class components could hold state. Today, with React hooks we can use functional components to hold state.
- Can hold state
- Unidirectional work flow

### State and Props
- State lives inside a component only
- Props are properties that can be passed down to child components

### Lifecycle Methods
- There are many lifecycle methods in React. The most frequently used on is Render, which of course is needed to get something on the page. Another commonly used one is Component Did Mount, a great place to make a network call.
- The constructor in a class base component is the first lifecycle method that is called

### React Router
- Allows for different components to be rendered depending on what route is hit. 

### Component Heirarchy
               App
                |
               Home
         /    /   \    \
     Header PLP   PDP  Cart
       /     
     Nav
    
