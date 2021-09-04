[<img src="assets/images/su-logo.png" alt="Skills Union Logo" height="80px" />](https://www.skillsunion.com/)

# Thinking in React: Study

## Brief

### 1. Overview

In the coming lesson, you will be creating `todo-app` from scratch. Use this time to consider how you might apply the following:

1. Separate container and representational components. Container components focus on managing data. Representational components focus on how it looks.

2. Define what kind of data should exist in this app and decide which ancestral component should manage those data.

3. Unidirectional data flow - state produces view, view triggers actions, actions changes state.

### 2. Use Cases

With the above mindsets, you are to produce the following use cases:

- List owners
- Add owner
- Delete owner
- List todo list based on owner's id
- Archive todo list based on owner's id
- Add new todo task based on owner's id

### 3. Tips

- Start with diagramming the components needed to achieve the above use cases.
- Design your data: craft out the json data needed.
- Decide which component should handle the data (as state) in your diagramming.
- To "switch screen", you need to apply conditional rendering of component based on certain state.
- Consider what kind of effects do you need for each components

### 4. Create a React App

Follow [this](https://reactjs.org/docs/create-a-new-react-app.html) guide to create a react app.

Create your app with this naming convention:

```console
npx create-react-app <your name>-todo-app
```
