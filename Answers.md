1. What problem does the context API help solve?

    The handling of data from parent to child gets cumbersome with scale especially for certain types of props that are required by many
    different components within an application. Context API solves this problem by providing a way to share data values between components without having to pass props. 

2. In your own words, describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?
    
    actions: packets of information that contain an action type and some data that we want associated with that action type.
    reducers: pure functions that never produce any side-effects, and are only place we can update state.
    store: contains our state for our entire application.

3. What is the difference between Application state and Component state? When would be a good time to use one over the other?
    
    Application state is pretty much what it sounds like, the state of the application as a whole (i.e. the store).

    Component state, conversely, is stored locally within a component and is not accessible from other components unless 
    it’s explicitly passed as props to it’s sub components.

4. Describe `redux-thunk`, what does it allow us to do? How does it change our `action-creators`?

    Redux Thunk is a middleware created by Dan Abramov, that provides the ability to handle asynchronous operations inside our Action Creators.

5. What is your favorite state management system you've learned and this sprint? Please explain why!
    
    I definitely enjoy REDUX the most because it comes with dev tools!
