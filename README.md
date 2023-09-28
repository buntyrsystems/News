# News 

This project consists of .Net Core 6 Web API as backend and Angular 16 for frontend. Backend project with 6 layers clean architecture i.e
 -  News.API
 -  News.Data
 -  News.Domain
 -  News.Data.Inegration.Test
 -  News.UnitTests
 -  News.Web

## Overview

News.sln is a web application that provides a platform for users to fetch the top news from hackernews and stay up-to-date with the latest trends in various topics.

## Features

- News.API is responsible for opening port and can be accible from postman/frontend. Cors are already enabled for application
- News.Data is responisble for logic and data access from hackernews api
- News.Domain consists of model/viewmodel
- News.Data.Inegration.Test having the test case for data layer by mocking the HttpClient
- News.UnitTests having the test case to verify the module in controller/API level.
- News.Web having the angular project with component, module and templates

## Prerequisites

These are prerequisites that are required to run project

- .NET Core 6 SDK
- Node.js and npm
- Angular CLI
- Visual Studio

## Getting Started

### Backend (ASP.NET Core Web API)

1. Clone this repository/rarfile. Extract in your working directory.
2. Navigate to the `backend` directory and open News.sln file
3. Build project so that all dependencies and nuget should be restore
4. Run the application
5. Note down the port number with localhost (https://localhost:7248/)

### Frontend (Angular)

1. Clone this repository/rarfile. Extract in your working directory.
2. Navigate to the `frontend` directory and reach location 'News\News.Web\newshacker\src' in command line
3. run npm install, that will install all npm modules and package
4. run ng serve --open
5. it will open http://localhost:4200/
6. You can see the number of records by paging

### Usings

Api which are using to get data

1. https://hacker-news.firebaseio.com/v0/newstories/.json?print=pretty
2. https://hacker-news.firebaseio.com/v0/item/{itemId}.json      (https://hacker-news.firebaseio.com/v0/item/2921983.json)


