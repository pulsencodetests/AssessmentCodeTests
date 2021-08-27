# WebApiCodeTest
# Task
This task is about implementing a common scenario in most enterprise projects, namely receiving api requests and calling external apis.
You should preferably use **dotnet core 3.1 or dotnet 5** but other languages are acceptable. 

## Requirements
Your api will receive certain parameters and use them to call an external api, namely the OMDB API which is open source movie database. The response back to the caller should include the response from OMDB. 

Your application should receive an api request with the following parameters:
* movieTitle, this is a string and contains the title of the movie to search for
* movieYear, this is the year the movie was released
* moviePlot, this is an enum with values full or short indicating to return the full movie plot or the short version
 
The moviePlot parameter is mandatory but the others are optional. The API should return the response back to the client as both json and xml.
The omdb api can be found at [OMDB](https://www.omdbapi.com/) . There you will find further instructions for their api and how to call it.

## Bonus tasks

* Include unit and integration tests (for example mock the omdb api and test different scenarios)
* Basic error handling (network failure, authentication errors)
* Logging (able to log different steps of the process)
* Not hardcoding the apikey for omdb api

Although the task itself is relatively straightforward, what we are looking for is to see how well you grasp the basics and how you have developed the project according to established best practises.

Once you believe you have completed the task and wish to submit, then clone this repo and simply submit a pull request with your name.
