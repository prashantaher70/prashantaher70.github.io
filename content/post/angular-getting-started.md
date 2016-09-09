+++
date = "2016-09-10T16:00:49+05:30"
draft = false
title = "Angular: Getting started (Part 1)"
subtitle= "Short introduction to angular.js"
ogimage= "images/angular-getting-started.png"
bigimg = "/images/angular-getting-started.png"

+++

#### What is Angular JS?

According to Angular JS <a href="" target=_blank>official website </a>
 
> AngularJS is a structural framework for dynamic web apps. It lets you use HTML as your template language and lets you extend HTML's syntax to express your application's components clearly and succinctly.
>
> Angular's data binding and dependency injection eliminate much of the code you would otherwise have to write. And it all happens within the browser, making it an ideal partner with any server technology.

Angular JS is a Javascript framework for writing HTML based web applications. It's a `MVC` framework where you have HTML templates as views, Javascript controllers to manage those views, and services for code reuse.


#### Why Angular JS?

Here are some reasons why you should consider using Angular JS:   

##### 1. DOM manipulations where they belong

Angular sees the view as just another HTML page with placeholders for data. So you do not mix your HTML rendering logic with your business logic. Because of it's two way binding, controllers and views are tightly coupled. Just bind a placeholder to a variable and Angular will take care of rendering it.

##### 2. Dependency injection

Dependency Injection (DI) is a software design pattern that deals with how components get hold of their dependencies.
The Angular injector subsystem is in charge of creating components, resolving their dependencies, and providing them to other components as requested.

##### 3. Two way data binding

Angular has two way data binding, where a model variable is bound to a HTML element that can both change and display the value of the variable. You can have more than one HTML element bound to the same variable.

##### 4. Directive

Directives are nothing but html tags on steroids. With directives you never have to manipulate DOM again. While using a widget (for example accordian, carousel), imagine if you could just write single HTML tag and a bind a variable to it. No DOM manipulations, no user event handling (for example closing, hiding). I know that would be just amazing. With directives you can do all those stuff.  
_You can define your own directives too!_

##### 5. Other features

* Routing (Write single page web applications)
* Scope inheritance
* Clean, modular, reusable architecture

These reasons should give you an idea of why Angular is powerful. In the next part we will implement a small Geocoding application with Angular JS.  

So stay tuned!
