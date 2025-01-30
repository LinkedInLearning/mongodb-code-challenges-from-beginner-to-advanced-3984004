# MongoDB Code Challenges: From Beginner to Advanced

This is the repository for the LinkedIn Learning course `MongoDB Code Challenges: From Beginner to Advanced`. The full course is available from [LinkedIn Learning][lil-course-url].

_See the readme file in the main branch for updated instructions and information._

## Instructions

This repository has branches for each of the videos in the course. You can use the branch pop up menu in github to switch to a specific branch and take a look at the course at that stage, or you can add `/tree/BRANCH_NAME` to the URL to go to the branch you want to access.

## Branches

The branches are structured to correspond to the videos in the course. The naming convention is `CHAPTER#_MOVIE#`. As an example, the branch named `02_03` corresponds to the second chapter and the third video in that chapter. 
Some branches will have a beginning and an end state. These are marked with the letters `b` for "beginning" and `e` for "end". The `b` branch contains the code as it is at the beginning of the movie. The `e` branch contains the code as it is at the end of the movie. The `main` branch holds the final state of the code when in the course.

When switching from one exercise files branch to the next after making changes to the files, you may get a message like this:

    error: Your local changes to the following files would be overwritten by checkout:        [files]
    Please commit your changes or stash them before you switch branches.
    Aborting

To resolve this issue:

- Add changes to git using this command: git add .
- Commit changes using this command: git commit -m "some message"

## Installing

1. To use these exercise files, you must have the following installed:
   - MongoDB [Community Edition](https://www.mongodb.com/products/self-managed/community-edition) installed on your machine or a MongoDB [Atlas](https://www.mongodb.com/atlas) account with a cloud database provisioned
   - MongoDB [Compass](https://www.mongodb.com/products/tools/compass)
   - MongoDB [Shell](https://www.mongodb.com/docs/mongodb-shell/) (mongosh)
   - An active [Microsoft CoPilot](https://copilot.microsoft.com) or [ChatGPT](https://chatgpt.com/) account
2. Clone this repository into your local machine using the terminal (Mac), CMD (Windows), or a GUI tool like SourceTree.
3. [Course-specific instructions]

## Instructor

John Cokos

John is Director of Curriculum and Principal Instructor at Code Fellows, a technical skills training academy based in Seattle, where his areas of expertise include Node.js, MongoDB, Express Servers, RESTful APIs, and full stack application building with ReactJS. In addition to his role guiding budding engineers through their careers, he's also owned a software company, a gym, and was program director of a youth baseball team and operates 2 YouTube channels in his spare time.

Check out my other courses on [LinkedIn Learning](https://www.linkedin.com/learning/instructors/john-cokos).

- [Data Modeling in MongoDB](https://www.linkedin.com/learning/data-modeling-in-mongodb)
