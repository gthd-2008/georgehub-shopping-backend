A back-end for the "georgehub-shopping" project. The project was never finished as I decided to learn C instead of continuing to do front-end. 

## What I learned by working on the project:
- how to work with Flask
- REST API (improved my understanding of it)

## Improvements compared to previous back-end projects
- the codebase is no longer monolithic, there's a clear separation between front-end and back-end.
- much smaller framework (Flask) had been used that still fulfills all of the needs
- commit messages had matured, they sound more confident. Some of the commits are even atomic.
- although the project was vibe-coded as the previous ones, code is much easier to read and it works as expected because I actually spent time reviewing the it
 
## What are the flaws:
- still no tests, no meaningful logging, no metrics -> painful debugging
- nested code, most of the route handlers handle all of the logic, instead of calling smaller functions for each sub-task
- some edge cases were not accounted for, because I focused more on front-end part than on the back-end one
- I still didn't Dockerize the application
    
## What could have been done differently:
- phase 1 of the project could have been dedicated to architecture design
- tests would be nice to have
- metrics, logs and traces could have been added for better debugging
- Docker could have been used to containerize the application
- more edge cases could have been accounted for


## Verdict?
Much better compared to previous two back-end projects. Code is easier to read, app structure is easier to follow (thanks to using a lightweight framework), more edge cases accounted for but not all of them, commits are smaller on average and commit messages are more meaningful. This is an showcase of my progress in the journey of becoming a Software Developer.
