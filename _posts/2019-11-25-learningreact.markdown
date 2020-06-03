---
layout: post
title:  "How I learned React"
date:   2019-11-25 00:15:00 -0500
img: img/portfolio/react.png
modalID: modalLearningReact
category: Technology
---

Life is crazy and React is more crazy. In my meditation classes, many gurus said Please donot react as much as you can. Before learning React, I'd recommend to learn JS. 

Whats new in JS ES6 ?
- Syntax
    - Why let and const keyword were introduced ? (coz of wierd Browser Hoisting)
    - Should we ditch var keyword and why ? (yes due to pollution in global scope)
    - Destructuring values 
    - Template literals
    - Object literal shorthand
    - for.. of loop
    - rest parameter
    - ... spread operator 
    - ... rest parameter
- Functions
    Functions are one of primary data structures in JS. 
    - Arrow functions
        
        const upperizedNames = ['Nirwik', 'Koirala', 'Pokhara'].map(function(name){
            return name.toUpperCase();
        })

    - Default function parameters
            function greet(name = 'Student', greeting = 'Welcome') {
                return `${greeting} ${name}!`;
                }
    - Defaults and destructuring arrays
- Class 
- Built-ins
    - Symbols
    - Iteratin & Iterable Protocols
    - Sets
    - Modifying Sets
    - Working with Sets
    - Sets & Iterators
    - WeakSets
    - Maps
    - WeakMaps
    - Promises
    - Proxies
    - Generators
    - Sending data into/out of a Generator

Code below passes arrow function instead of a regular function as above. 
        const upperizedNames = ['Nirwik', 'Koirala', 'Pokhara'].map(
             name => name.toUpperCase();
                })
    - Arrow functions are always expressions

Lists of Gotchas in JS
- this keyword
- Nan
- 



Learning about developing with React is so fun. Below are the resources that I used to learn the Front end development. 

- CSS and Bootstrap (Coursera)
- FreecodeCamp
- Javascript  (Javabrains)
- Typescript (Javabrains)
- React (Coursera)
<!-- https://www.coursera.org/learn/front-end-react/home/welcome -->





