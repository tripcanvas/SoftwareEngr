# SoftwareEngr
Hello! Thanks so much for showing your interest in joining TripCanvas tech team!

Below is the technical test for you! Please do let us know if you have any questions! You can email us at: tech@tripcanvas.co!
Best of luck!

Technical description
===========

We expect you to be familiar with the following and show the ability in your coding!
-------------

### Frontend technologies:

* ECMA 6
* Frontend framework e.g. ReactJS with Redux
* Webpack
* HTML/CSS as needed

### Backend technologies:

* NodeJS
* MongoDB

### Testing

* Functional testing
* Unit testing

Goals
---------
We would like you to see if you can build a hotel listing application! Sample schema of a hotel 
```
{
  id: 1,
  title: "Aloft Hotel",
  image: "",
  facilities: [
    "breakfast_included" : true,
    "accepts_credit_card" : true,
    "internet" : "1Gbps wifi"
  ],
  average_price : 400,
  currency : "RM",
  star_rating: 5
}
```
Here are the goals:

## Goal 1
Prepare your backend application using NodeJS and Express. This application will serve information of hotels using REST API. Prepare some mock APIs.

Note: This is your opportunity to show your backend skills. Please try over-engineering and showoff your skills!

## Goal 2
Create listing page with pagination using React and Redux. Users can select any hotel as their favourite. Indicator of favourite should not go away with page refresh.

* You should have an application route called /hotels
* On this route, render a page showing the hotels
* You should use Webpack to optimize, pack your assets, and serve to browser!
* Bonus points for isomorphic coding and server side rendering!

Note: This is your opportunity to show your JS skills. Try over-engineering! Use advanced JS features like Async/Await, Generators, Event based operations whenever possible!

## Goal 3

Create sidebar which contains : 

```
Recommended hotel(s).
```
* If user does not select any hotel as favourite, recommended hotels will be empty.
* If user selects any hotel as favourite, recommended hotels would be those hotels that have same features but cheaper.
* Send a push notification to browser if you find any recommended hotel.

Be aware that if you change any input it should change the recommended hotel accordingly 

## Goal 4
Last but not the least, testing! You can follow TDD or FDD!

* There should be a way to test all the functionalities of your app!
* Write functional tests!
* Write unit tests!

### Submit your code
- Please don't forget to write your readme file which should contain what/why your have done things in certain way! Documentation is highly appreciated!
- Your solution should be committed back into this repository like you would do in a normal project.
- You can commit and push as many times as you want.
- We value a clean coding style. It would be nice if you follow something like Airbnb's JavaScript Style Guide!

Best of luck!
