# Namste_React

# Parcel
-Dev Build
-local server
-HMR = Hot Module Replacement (auto refreshing dom)
-File watching Algoritham -written in c++
-Cashing Faster BUild
-Image optimisation
-Bundling
-Compressing
-Code splitting
-Differencial Bundling : support old browser
-Diagnostrics 
-Error Handling
-Host into https
-Tree shaking : remove unsed code

Two types of Export/Import
1.export/import default
> export default Component; 
> import Component from "path"

2.name export/import
> export cosnt Component; 
> import {Component} from "path"

#React HOOKS
(normal js functions)
-useState = state variable in react
-useEffect

# Types of Routing
- Client side Routing (you redirect anither page just coponent changes)
- Server side Routing (you made a call and about us page comes with data)

# class component vs functional component
- function end of js function 
- class component end of js class (it inherit from react component) and it has render method which return jsx

# Redux Toolkit
- Install @reduxjs/toolkit, react-redux
- Build our store 
- Connect our store to app
- create card slice
- dispatch(action)
- Selector

# Types of Testing
- Unit Testing (Testing a component in isolation app)
- Integrating Testing
- End to End Testing - e2e testing

# Setting up Testing in our app
- Install react testing library
- install jest
- install babel dependancy
- configure babel
- configure parcelrc to disable the default babel transpilation.
- jest configuration : npx jest --init.
- install jsdom : npx i --save-dev jest-environment-jsdom.
- install @babel/preset-babel : to make JSX work in test cases.
- include @babel/preset-babel inside babel config file.
