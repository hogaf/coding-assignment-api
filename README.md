# Api Coding Assignment

## Case: Questionnaire Api

For this coding assignment, we want you to create an _http based API_.
The API should support:
- Getting one or more questions and answer options, preferably paged 
- Posting one or more answers for the questions. This includes a mock userid and one of four possible departments (marketing, sales, development, reception)
- Returning a results calculation of min, max, average for each answer, calculated across the departments

We also want you to create a test-suite for the API to check its correctness. For this you can use any approach or tool you like.

## The JSON

As data source for the API you should use the JSON provided called `questionnaire.json`. This JSON contains a datastructure that represents your sample questionnaire. It contains `subjects`, `questions` and `answers`.

We leave it to you to further interpret this data in the way you want. Please write down what questions you had about the data and what assumptions you made.

## Expectations

The goal of the assignment is to get an idea of your experience, creativity, and ability to learn, analyse and reason. 

`Please keep in mind that this assignment is the starting point of discussion, not the destination. Readability and clearly explaining your solution and reason about it are more important than implementing many different concepts, libraries, or tools without explaining why one would use them in the case. We expect you to don't spend more than 4 hours to complete this assignment. Please think carefully before you start about what you are able to accomplish in this timeframe.`

Your back-end application does not have to be production ready but it should be able build and run  without errors

Depending on your degree of experience, we may want to add some creative ideas to your application. This is entirely up to you, and you can choose anything you want to enrich your application. Some examples include:
- Deploy and run the API to a cloud environment.
- Set up a Docker compose file to run and/or deploy your application
- Using event-based messaging to publish the answers of the questionnaire

## Tech stack
For the application(s), you can use any language or framework of your choosing. However in order for us to better understand your fit with our current tech stack, we recommend you stay close to it. Our stack is made of Angular/Typescript, .Net Core/C#, Azure.

You can read more about what else our Tech Stack contains [here](https://tech.effectory.com/#what-are-we-working-on).
