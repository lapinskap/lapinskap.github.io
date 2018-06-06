---
layout: post
title: 'Expensify - React Router & Redux'
---

The application is not very inventive, for similar reasons as the Indecision-app, but I spent many hours with it learning how to build complex react applications. Thanks to this project I met the React Router and Redux.

<a href="http://www.google.com" target="_blank"><button name="button" class="btn">Live demo</button></a>
<a href="https://gitlab.com/lapinskap/expensify" target="_blank"><button name="button" class="btn">View code</button></a>

<style> 
.btn {
    color: black;
    background-color: #e5e5e5;
    cursor: pointer;
    border: none;
}
</style>

In this example I got to know the concept of application testing and the first time I turned react app on the production mode.

{% include image.html url="http://www.gratisography.com" image="projects/proj-2/thumb.jpg" %}

### Important topics that I explored while writing this application:
* Array Destructuring 
* Reducers, Multiple Reducers
* Filtering Redux Data
* The Higher Order Component
* Controlled Inputs for Filters
* Redux Dev Tools
* Jest
* Enzyme 

I started learning React Router to create an application that will have several subpages, in contrast to "ToDo" app. Afterwards I started to get acquainted with Redux. It took me a long time because I had to understand why we need it. It's about sending props and state between components - Previously application worked if there was a "mother component" that holded the necessary props, for example the "App" component had props "Options" from the "Add Option" component. Here the situation looks different - we don't use any "mother component" and we don't wanna store everything in local store. 

I changed props to Reducers. Then I added few actions to the project with `createStore()` and `combineReducers({})`.

{% include image.html url="http://www.gratisography.com" image="projects/proj-2/stretch.jpg" %}

{% include image.html url="http://www.gratisography.com" image="projects/proj-2/add.jpg" %}
<br/>
<a href="http://www.google.com" target="_blank"><button name="button" class="btn">Live demo</button></a>
<a href="https://gitlab.com/lapinskap/expensify" target="_blank"><button name="button" class="btn">View code</button></a>