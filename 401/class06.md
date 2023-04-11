# Ten Thousand Game 1

## Reading
### [How to use Random Module](https://www.pythonforbeginners.com/random/how-to-use-the-random-module-in-python)
### [What is Risk Analysis](https://www.edureka.co/blog/risk-analysis-in-software-testing/)
### [Test Coverage](https://martinfowler.com/bliki/TestCoverage.html)

## Videos
### [Big O Notation](https://www.youtube.com/watch?v=v4cd1O4zkGw)

## Bookmark and Review
### [Python Random](https://docs.python.org/3/library/random.html)

## Further Reading
### [What is Dependency Injection](https://www.freecodecamp.org/news/a-quick-intro-to-dependency-injection-what-it-is-and-when-to-use-it-7578c84fa88f/)

## Reading Questions
1. How can the random module be utilized in Python to generate random numbers or make selections from a list, and what are some common functions available within the module?
   - You can use `random` to generate random numbers or choose a random selection from a list.
   - `.random()` can be used to get a random floating point number between 0.0 and 1.0 not including 1.0. To get a random integer, just multiply the result by the largest possible number you want. Also encase it in `int()`. 
     - `int(random.random()*10)` gives a random number from 0 to 9.
     - `int(random.random()*100)` returns a random number between 0 and 99. 
     - `int(random.random()*25)` returns a random number between 0 and 24.
   - `.choice(list)` returns a random selection from a list
2. In the context of software development, what is risk analysis, and what are the key steps involved in conducting a risk analysis for a software project?
    - Risk analyisis is analyzing an application for areas where it is likely that something will go wrong
      1. Searching the Risk
      2. Analyzing the impact of each individual risk
      3. Measures for the risk identified
3. What is test coverage and why is it an important (or potentially misleading) metric in software testing?
    - Test coverage is how thoroughly you code is tested. Test coverage is an important metric because it is helpful to understand how vigorously your code has been tested so you can either make more/better tests or not.
4. What is Big O notation, and how is it used to describe the performance of an algorithm? Give an example of an everyday task (not software related) that demonstrates O(n) time complexity.
    - Big O notation is used to describe the performance of a task by relating it to a math equation involving N where N is the input. An example of this is sending out thank you notes to people who came to your birthday party. N would be the number of people you invited/came to the party. the time it would take you to write thank you notes would be O(N).