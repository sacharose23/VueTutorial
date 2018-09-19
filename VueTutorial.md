# [Vue Tutorial](https://www.udemy.com/vuejs-2-the-complete-guide/learn/v4/content)

## Benefits of Vue

* Lean and small file sizes (fast loading time)
* Great Runtime Performance
* Feature-Rich

## Starter Exercises

**Reference**: ```firstExercise.html``` & ```secondExercise.html```

**Helpful Links:** [Vue](https://vuejs.org/) & [JSFiddle](https://jsfiddle.net/50wL7mdz/732026/) 

## Course Structure

* Interacting with the DOM (Templates)
* Understanding the VueJS Instance
* Vue CLI 
* Components
* Forms
* Directives, Filters, & Mixins
* Animations & Transitions
* Working with Http
* SPAs (single page applications)
  * Routing
  * State Management
* Deploying a VueJS App (ship our App to a server)

## Projects

1. Basics, Template Interaction
2. Components
3. Animations
4. Final Project (includes Routing, State Management)

## Setup VueJS Locally

I did NPM installation process. Simply go to terminal and to your working directory. Then, type in ```npm install vue```. Then, I did script tags to reference 'vue.js'. 

```html
<!-- Within head tags; however it can be anywhere above the Vue instance. -->
<script src="node_modules/vue/dist/vue.js"></script>
```

## Understanding VueJS Templates

**Reference**: ```thirdExercise.html``` 

* We can see how VueJS Template & Instance works together. 

* We can call methods in our Vue instance using string interpolation (i.e. {{ }} syntax). 
* We can use ```this.title``` in order to call the property 'title' inside the above property object 'data'. 
* We go over the fact that we cannot use string interpolation in any HTML tags (e.g. the 'a' tag for links); so, we need to use a **directive** called *v-bind*. 













