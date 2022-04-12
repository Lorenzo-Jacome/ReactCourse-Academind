# React Course - Academind
## Description
Repository for the code written for the Udemy course by Maximilian Shwarzmüller [
React - The Complete Guide (incl Hooks, React Router, Redux)
](https://www.udemy.com/course/react-the-complete-guide-incl-redux/)
## Folder description and annotations
### 3 - React basics & working with components
#### Commands used and descriptions
* Create a default / demo react project with - `npx create-react-app [project name]`
* Start the server with - `npm start`
* Reads into package.json file and installs all necessary dependencies. Used when cloning / copying a previously created project. - `npm install`
### 4 - React State & Working with Events
#### Annotations
* On event listeners, when passing a function, you just reference the functio, don't call it. Meaning don't do: function() | Do: function.
* Hooks (like useState), always start with "use". They can only be called inside react components.
* You can pass information to children components with props, but you can also pass it from children to parents when creating a function from the parent and passing a reference to the children, where it can be called. 