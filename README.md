# Burger Menu - Node and Express Servers

<br>

## Description

Eat-Da-Burger is a burger logger that takes in orders from the user and shows an ordered list of orders to be completed. Burgers from the list can be devoured and moved to a seperate list using Object-Relational Mapping (ORM).



<br>

## Overview of App Organization

This is app contains the following files:

  ```
  Burger
    - .gitignore
    - config
      - connection.js
      - db-config.js
      - orm.js
    - controllers
      - burgers_controller.js
    - db
      - schema.sql
      - seeds.sql
    - models
      - burger.js
    - public
      - assets
        - css
          - burger_style.css
        - js
          - burger.js
    - views
      - layouts
        - main.handlebars
      - partials
        - index.handlebars
        - burgers
          - burger-block.handlebars
    - node_modules
    - package.json
    - server.js
  ```
  

<br>

## Run Instructions

The user begins at:

![HomeScreen](assets/images/HomeScreen.png)

Then after the **Find Friend!** form, is filled out the burger name appears on the left side above the form until the **buttono** button is clicked

![InitialSurvey](assets/images/InitialSurvey.png)

This moves the selected burger to the right column on the screen designated for devoured burgers

## This App Utilizes

   * [Node](https://www.npmjs.com/package/path)

   * [Express](https://www.npmjs.com/package/express)

   * [Handlebars](https://www.npmjs.com/package/path)

   * [MySQL](https://www.npmjs.com/package/path)

   * [JawsDB](https://www.npmjs.com/package/path)



<br>

## Role in Development

My name is Alex I am a bootcamp student whose portfolio can be found
[here]( https://alexsamalot19.github.io/Samalot-Alexander-Portfolio/).

I designed this app using existing APIs and packages listed in the **This App Utilizes** section. I used Node and MySQL to query and route data in this app, and Handlebars to generate your HTML. The site is deployed to Heroku [here](https://friendfinder987.herokuapp.com/).