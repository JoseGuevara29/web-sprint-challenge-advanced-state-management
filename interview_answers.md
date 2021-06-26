# Interview Answers
Be prepared to demonstrate your understanding of this week's concepts by answering questions on the following topics. These will not be counted as a part of your sprint score but will be helpful for preparing you for your endorsement interview, and enhancing overall understanding.

1. What problem does the context API help solve?
   -It prevents prop drilling.

2. In your own words, describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?
   -Actions: Give instructions and data to the reducer
   -Reducers: Reduce the previous state and the new state into one new state.
   -Store: the store stores the states and provides the states to the app

3. What does `redux-thunk` allow us to do? How does it change our `action-creators`?
   -thunk gives us more functionality and it lets action-creators make api calls

4. What is your favorite state management system you've learned and this sprint? Please explain why!
   -Context API