# Working with Data and APIs in JavaScript

This is a working document outlining future plans for a new Coding Train playlist: "Working with Data and APIs in JavaScript."


## Description

This course is for aspiring developers who want to learn how to work with data in web applications. How do you find, collect, clean, analyze, and visualize data? I’ll start with the basics of data formats: CSV, XML, and JSON. I’ll then cover how to use Promises and the JavaScript fetch() function to load data asynchronously on a webpage. I’ll do case studies of several APIs and explain how to sign up and authenticate, make a request, and load the data. I’ll look at how this works for both client-side and server-side code. I’ll demonstrate how to visualize the data using HTML5 Canvas and p5.js. The course will end with a demonstration for how to analyze data using modern machine learning techniques such as classification, regression, and clustering.

## Outline

## Introduction
1. Course Trailer (~1 minute overview)
2. Full introduction -- overview of topics, goals for the course

### JSON
1. Example data: [Corpora](https://github.com/dariusk/corpora)
2. Loading into the browser: `fetch()`
    * working with promises, async/await
3. Rendering DOM elements
4. Loading data server-side:
    * `fs` package
    * `es6-promise` and `isomorphic-fetch`;

### Tabular Data
1. Example data: (TBD? need super simple spreadsheet!)
2. Using split() and regex
    * dealing with header row
3. Sorting data
4. Parsing libraries for working with CSV
    * What would be good to show?
    * Google sheet integration?
    * p5.js `loadTable()`
    
### Databases
1. [NedB](https://github.com/louischatriot/nedb)
2. Saving, updating, retrieving
3. Talking to the client

### Loading Data from an API
1. CORS! Help!
2. API demonstration: https://wheretheiss.at? 
3. API pagination
4. Querying an API over and over
5. API keys and environment variables
6. Deployment (Glitch?)

### Geo Data
* Mapping data (global climate temperatures?)

### Time Series Data
* Graphing data in real-time
