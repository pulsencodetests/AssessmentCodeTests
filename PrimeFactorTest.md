Prime Factors
============
Source: [https://github.com/ardalis/kata-catalog](https://github.com/ardalis/kata-catalog)

# Instructions #

Your project should be written in dotnet core 3.1 or dotnet 5 (other languages are acceptable).

Write a class named "PrimeFactors" that has one static method: Generate(). Generate accepts one integer argument and returns a collection of integers. This collection contains the prime factors  of the input argument in numeric sequence.

Your main task is complete teh generate method above and write parameterised tests to verify this functionality. 
Your tests should verify that the following numbers result in a valid output:
* 0 => []
* -1 => []
* 3 => []
* 9 => [3,3]
* 12 => [2,2,3]
* 44 => [2,2,11]
* 156 => [2,2,3,13]
* 67892 => [2,2,11,1543]
* 1023405 => [3,5,68227]

**Hint:** Your first test might confirm that, given an input of one, Generate() returns an empty collection.

Once you have completed the project, clone this repo and submit a pull request. 

# Resources #
- [Walkthrough by Uncle Bob Martin](http://butunclebob.com/ArticleS.UncleBob.ThePrimeFactorsKata)
