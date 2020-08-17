# Laravel & PHP Software/Web Developer

The purpose of this development task is to demonstrate your abilities and knowlege of the Laravel Framework whilst also gaining insight into how you write and structure your code.

## The Task

Our software projects are heavily dependant on APIs, either by self consuption on the front-end through VueJS or exposing a RESTful API to be used and consumed in iOS and Android mobile apps.

We would like you to create a RESTful API that can be consumed through Postman.

You should update this README.md file with instructions on how to get this project started (seeding the database with model factories where appropriate) and also include documentation on what endpoints are available and how we can interact with them.

### Context

You are the well known buying and selling marketplace AutoTrader and are developing a new feature that will allow the user to select a vehicle make, model and fuel type before then returning the vehicles that are available for sale with the matching criteria.

### Endpoints

#### GET /api/v1/makes

**Returns** all vehicle makes in alphabetical sort order.

#### GET /api/v1/makes/{make}/models

**Returns** all associated models in alphabetical sort order.

#### GET /api/v1/search?make=Audi&model=TT&fuelType=Petrol

The search API endpoint has 3 parameters **make**, **model** and **fuelType**. The **make** parameter is required and should be validated.  
**Returns** all vehicles matching the endpoint parameters

## What we'd like to see

• [SOLID Principles](https://laracasts.com/series/solid-principles-in-php)  
• [API Resources](https://laravel.com/docs/6.x/eloquent-resources)  
• [Repository Design Pattern](https://itnext.io/repository-design-pattern-done-right-in-laravel-d177b5fa75d4)  
• [API Tests](https://laravel.com/docs/6.x/http-tests)   
• [Database seeding with model factories](https://laravel.com/docs/7.x/seeding#using-model-factories)  
• The API endpoints will be publically accessible though they should be protected using an API Bearer token   
• A basic front-end using Vue components that consumes the API and allows you to interact with the functionality     
• We use [TailwindCSS](https://tailwindcss.com/docs/installation/#laravel-mix) extensively so you should install this package and use it's utility classes to position your Vue component elements   
• It would be preferable if you were able to use Docker for the development environment   
• Update the readme below to provide instructions on how to get the project setup locally and how to use the API   
• Please treat this is if it were a real world project as we are also looking at your file naming conventions and directory structure   

# Documentation  

...
