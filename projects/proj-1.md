---
layout: post
title: 'Indecision App - ToDo in React'
---

This is my first application in React. Yes, it's not very creative - App was created with the [Udemy course](https://www.udemy.com/react-2nd-edition/){:target="_blank"} by Andrew Mead. 

<a href="http://www.google.com" target="_blank"><button name="button" class="btn">Live demo</button></a>
<a href="https://gitlab.com/lapinskap/react-components-1" target="_blank"><button name="button" class="btn">View code</button></a>
<style> 
.btn {
    color: black;
    background-color: #e5e5e5;
    cursor: pointer;
    border: none;
}
</style>

However, I've learned React environment and [ES6 syntax](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Arrow_functions){:target="_blank"} from the beginning. Before I implemented anything, I practiced specific methods on other examples to get deep understanding. That's why I spent a lot of time on this project. The most valuable for me is the playground folder. The app was created completely from scratch. From the beginning, I put a lot of weight on the clear file structure and wise names, so I found the [BEM](https://en.bem.info/methodology/key-concepts/){:target="_blank"} naming convention.

{% include image.html url="http://www.gratisography.com" image="projects/proj-1/dog.jpg" %}

{% include image.html url="http://www.gratisography.com" image="projects/proj-1/wall.jpg" %}



At the beginning I wrote this application in pure JSX (translated by Babel). It works and even application looks the same as it did later. 
> You can see this little monster [here](https://gitlab.com/lapinskap/react-components-1/blob/master/src/playground/jsx-indecision.js){:target="_blank"}.


Later I rewrote it using React Components and Webpack.
I created my own [webpack.config.js](https://gitlab.com/lapinskap/react-components-1/blob/master/webpack.config.js){:target="_blank"} file, which redirected scss files to be loaded by sass-loader. Why do I mention this? Because without this file, scss **will not** work. 

It's such an introduction to node.js.

I spent the most time trying to understand data binding. Afterwards getting to know Props and State was very pleasant.

The added options are saved in the local browser's memory, which means that the options that have not been deleted manually are available again after restarting the application.

I used also Third-Party component called "React Modal" - that's the window that pops up when pressing the main button. This application was my first RWD experience - I used `rem` in css and media queries breakpoints to set up another view for small screens: 

{% include image.html url="http://www.gratisography.com" image="projects/proj-1/mobile.jpg" %}
<br/>
<a href="http://www.google.com" target="_blank"><button name="button" class="btn">Live demo</button></a>
<a href="https://gitlab.com/lapinskap/react-components-1" target="_blank"><button name="button" class="btn">View code</button></a>