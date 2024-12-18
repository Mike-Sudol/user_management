# The User Management System Final Project: Your Epic Coding Adventure Awaits! 🎉✨🔥
## Tests

## Paper
Submit a 1-2 page Word document reflecting on your learnings throughout the course and your experience working on this epic project.

## Features
[Choose a feature](features.md) from the provided list of additional improvements that sparks your interest and aligns with your goals like a laser beam. ✨⭐🎯 This is your chance to shine!

## Issues

1. **User Deletion Validation**: [Link](https://github.com/Mike-Sudol/user_management/issues/2)
   
Currently we are not checking if the user is an admin before they delete a user, lets fix this this by checking in the function first.


2. **Database Issues**: [Link](https://github.com/Mike-Sudol/user_management/issues/8)
   
The way we are allocating database instances to our services is heavily suboptimal

3. **Race Condition**[Link](https://github.com/Mike-Sudol/user_management/issues/6):
   
We have a potential infinite loop in an await that really slows down our execution or can stop the program all together, lets add a limit to how many times we check in the while before exiting.
   

4. **Email validation**: [Link](https://github.com/Mike-Sudol/user_management/issues/4)
   
When we verify emails, we aren't checking if they exist before we pass them on, lets fix this by checking first.

5. **CVEs and Conflicting Dependencies**: [Link](https://github.com/Mike-Sudol/user_management/issues/1)
    
Currently we have CVEs in our software as well as dependencies that are conflicting with each other, we need to change our requirements.txt to fix this

## Dockerhub
Make sure your project successfully deploys to DockerHub and include a link to your Docker repository in the document

[Link to project image deployed to Dockerhub](https://hub.docker.com/r/ms2649/user_management/tags)
![Docker](Docker.png)