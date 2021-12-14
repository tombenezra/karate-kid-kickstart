
## Step 1: 
Your first task will be to write a simple todo app.  For now it will be client only. You can only use html, vanilla js and css (no other lib like react/angular/lodash/jquery are allowed).

The app should support:
* Adding a new todo item
* Editing an existing todo item
* Deleting a todo item
* Showing the list of all todo items
* Mark a todo item as done.

To achieve it you will need to learn:
* Flex layout in css 
  * https://flexboxfroggy.com/
  * http://www.flexboxdefense.com/
  * https://flukeout.github.io/
* what is the dom (document object model)
* js dom manipulation 
* html syntax

You can find a lot of information about each of these items. Remember to always read the manual on the mdn site (Mozilla developer network) and not w3c school.

Videos that I want you to watch in this step:
* [What the heck is the event loop anyway?](https://www.youtube.com/watch?v=8aGhZQkoFbQ)

## Step 2 (Deadline - DD/MM)

To learn:
* Webpack
* [Build your own Webpack](https://www.youtube.com/watch?v=a1HS3-YkJnY)
* Localstorage 
* Cookies
* Localstorage vs cookies
* What are the differences between LS and cookies
    * When should we use LS and when should we use cookies
    * What are the different types of cookies
* Bind
* Hoisting

With the mentor
* [Bind exercise](https://jsbin.com/kenayubile/edit?js,console)
* Hoisting exercise - TBD

Todo:
* Use localstorage to save the todos - refresh should not lose the todos
* Use webpack as your bundler

## Step 3 (Deadline - DD/MM)

To learn:
* Semver - read all about it
* Source map loader vs devtool
* Chrome debugger
* Prototype (read about prototypical inheritance) 

Todo:
* Add source maps to your project
* Change css to be jss (css inside js)

With the mentor:
* [Currying](https://jsbin.com/dumiyakoko/edit?js,console)

## Step 4 (Deadline - DD/MM)

Learn about:
* Http protocol
  * 1 way communication
  * http methods
  * Https
* Learn what is private/public key (RSA)
* Web socket protocol
* Server + express
    * Learn about express library
* Fetch API
  * Read [this blogpost](https://shahata.medium.com/why-i-wont-be-using-fetch-api-in-my-apps-6900e6c6fe78)

Todo:

Write the todo app again, this time with a server. The server should hold the todos in its memory (no need for localstorage). Use webpack, XHR
Use axios, 

## Step 5 (Deadline - DD/MM) - Look mommy I’ve written an actual piece of software you can actually use!

Todo:

* Install "edit this cookie" extension
* Make it a server for “everyone” (cookies and userIds, HTTP cookie)
* Push to heroku
* Use free redis [add-on](https://elements.heroku.com/addons/heroku-redis), Mongo atlas or any other db preference


## Step 6 (Deadline - DD/MM)
To learn:
* Typescript

Todo:
* Typescript everything from scratch

## Step 7 (Deadline - DD/MM)
To learn:
* Signed vs Encrypted
* JWT
* Symmetric vs asymmetric encryption
  * Using asymmetric to exchange symmetric keys
  * Read about pros & cons of symmetric vs asymmetric

Todo:

In this step you can use the app from the previous step.
* replace your cookie with a JWT cookie
* login/logout - design in a sequence diagram (learn about sequence diagram as well if you don’t know what this is)


## Step 8 (Deadline - DD/MM) - Welcome to React!
To learn:
* React - do the [getting started tutorial](https://reactjs.org/tutorial/tutorial.html) (only in case you don't know react)
* Learn about hooks

Todo:
Write the todo app from scratch using typescript and react. You can re-use your server from previous steps.

## Step 9 (Deadline - DD/MM) - Testing!

To learn:
Watch uncle bob TDD episode 6 part 1+2 [link](https://drive.google.com/drive/folders/1wiiQVQ1iEP4w1AzfCOZiOnqj8jL4rrwY?usp=sharing)

Todo:

* Write everything from scratch using TDD
* React tests using jest
* React-testing-library 
* At least 1 e2e test using puppeteer (blackbox)

## Step 10 (Deadline - DD/MM) - The State of affairs

To learn:
Now that you know react a little bit lets learn how it works under the hood:
* Build your own react
* Video - https://www.youtube.com/watch?v=RmAIwZeY0tk
* Blogpost - https://hackernoon.com/build-your-own-react-48edb8ed350d
* [redux](https://egghead.io/courses/getting-started-with-redux)
* Mobx / mobx state tree
* Providers and context using hooks

With the mentor:
Do we providers/contexts them when we have hooks?


## Step 11 (Deadline - DD/MM) - Final Project!! Welcome to Wix!
* npx create-yoshi-app todo
* WSR - The new UI order
* Push your app to wix’s production environment
