# Task Scheduler

Authors: [Adil Mohiuddin](https://github.com/advilm), [Jian Darugar](https://github.com/jiandarugar), [Leyna Diep](https://github.com/lxyna), [Saul Mendoza](https://github.com/smendoza07)

## Phase I

As students, time management is crucial to succeeding in our classes so a task scheduler is something that we can all make use of. It is also a way to keep track of all assignment due dates in a central location instead of having to check each class syllabus every day. It is also important to dedicate time to rest and relaxation so having a reminder on a scheduler that it is time to step away from the desk will help to keep students balanced. This project is interesting to us of how busy daily life can be. Time management is crucial for productivity throughout the day, so this project will be able to greatly benefit the user.

The programming languages we plan to use are JavaScript for the frontend and Python for the backend.

Technologies:
* Frontend
    * [React](https://reactjs.org/) - Declarative, efficient, and flexible JavaScript library for building user interfaces
    * [Next.js](https://nextjs.org/) - Framework that allows for server-side rendering and static site generation
    * [Mantine](https://mantine.dev/) - Library with pre-made UI components
* Backend
    * [Flask](https://flask.palletsprojects.com/) - Can be used to make a basic API easily
    * [SQLAlchemy](https://www.sqlalchemy.org/) - Gives application developers the full power and flexibility of SQL.
    * [SQLite](https://www.sqlite.org/index.html) - C-language library that implements a small, fast, self-contained, high-reliability, full-featured, SQL database engine.

The project JASL is proposing is to create a task scheduler that allows the reader to tell when they should complete a task. The scheduler will remember the user's tasks that the user sets and order them by priority. Users should be able to create tasks in this program with corresponding subtasks. If the user felt the task was completed they can check off that they completed it on their task list. The input for the project would be people uploading tasks with a title, description, and priority, and the output would be tasks added to the scheduler.

## Class Diagram
![Class Diagram](./classdiagram.svg)

## Phase II
* Met with TA. 

## Final deliverable

 ### Screenshots
 ![Input](./Input.png)
 ![Outpu](./Output.png)
 
 ### Installation/Usage
 * Backend:
   * When running the program, you must run it in a virtual environemnt.
   * Once in the virtual environment, you can install all the dependencies by using: $ pip install -r requirements.txt
   * Using the command $ python app.py will run the program and show a link for the local server.
 * Frontend:
   * Install dependencies by running yarn
   * Run yarn build && yarn start to build & run the production build

 ### Testing
 * The program was tested using Postman for the most part. Postman allows us to test each function by passing in JSON data and showing us the output of the function.
 * We also created a unit test and have a code coverage report.
