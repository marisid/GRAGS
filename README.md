# Status

![[Build Status]https://travis-ci.org/NodeGroup2/GRAGS.svg?branch=master](https://travis-ci.org/NodeGroup2/GRAGS.svg?branch=master)

# GRAGS

A Hapi app for searching recipes and requesting Tesco shopping lists.

## Installation instructions

- Clone this repo and `cd` into it
- Run `npm install` to install all dependencies
- Ask us for the Tesco API key
- Create an `.env` file in the root directory, and add line `export TESCO_API_KEY=the-key-here` to it
- Run `npm start` to start the server
- Navigate to `http://localhost:4000/` in your browser
- To run the tests, run `npm test`

## General objectives

- Build a simple hapi app
- Use test driven development
- Query at least two APIs on the backend
- Use data to populate a handlebars template
- Display server-rended page on the front-end
- Aim for high test-coverage on front-end and back-end
- Host the project on heroku
- Use basic ES6 syntax

## Specific objectives

- Implement a recipe search API ([Recipe puppy](http://www.recipepuppy.com/))
- Implement a grocery search API ([Tesco](https://devportal.tescolabs.com/))
- Provide ingredients checklist
- Provide total cost calculation for selected ingredients

## User story

As a... **beginner cook with a busy lifestyle and a Tesco Clubcard**,  
I want to... **find a recipe and a shopping list of ingredients**  
so that... **I know what I need to get from Tesco and how much it will cost.**  

## Project plan

### Monday
- develop ideas
- user story
- research APIs
- wireframes
- implement Travis

### Tuesday
- set up a simple Hapi server using TDD
- define endpoints from front-end to back-end
- add API keys as environment variables using ENV2
- add templates for server rendering of webpages
- add front-end interactivity
- ...

### Wednesday

## Front-end design

![Front-end design](wireframes.jpg)

## Folder structure
- public
  - templates
    - index.html
  - helpers
  - styles.css
  - index.js
- src
  - router.js
  - handler.js
  - other modules
- tests
  - tape-tests.js
  - qunit-tests.js
- server.js
- package.json
- qunit.html
- .gitignore

### Testing

- Unit testing
- Front-end using qUnit
- Back-end using Tape
- Code coverage using Istanbul
- Continuous integration using Travis
