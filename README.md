# Task Management Boards

## Tech stack 
- React for the front-end (only hooks, no classes).
- For front-end part state manager for data (redux, redux-toolkit or any other which you prefer).
- Back-end framework which is suitable for you (Nest.js or Express.js).
- Typescript is a must for both front-end and back-end (frameworks, which doesn't support Typescript are not allowed).
- Use MongoDB or PostgreSQL for data storage.
- Code quality checkers are required (at least ESLint and Prettier)
> Stack requirements mentioned above are obligatory to follow. Other technologies and patterns are free of your choice.  

## Extra points - optional
- Add github actions to run code quality checks for frontend and backend
- Provide a Dockerfile for frontend and backend

## Requirements
1. Each visitor is allowed to create/update/delete boards (implement UX/UI on your own).
2. Each board (unique hashed ID, name) should contain 3 columns - ToDo, In Progress, Done.
3. Each visitor can enter a board ID and load relevant columns with cards (if exist) related to this board.
4. Each visitor should be able to add/update/delete cards (title and description).
5. Visitors should be able to drag and drop cards into other columns, or change order.
> User authentication is not needed. Boards management is considered to be implemented anonymously.

## Assessment

What will we assess:
- workability: how your application works;
- project structure: how you structure your files;
- code quality: how you write clean, readable code;
- knowledge of technologies and their ecosystem: how you compose and use libraries together;
- testing: how you can test your code;

## Mockups

![image](https://res.cloudinary.com/dgw6mlivg/image/upload/v1704446575/Title_1_yecgix.png)


## How to complete the task
- create a new public repo on GitHub;
- develop the application according to the requirements;
- send us the link to your repo;
- deploy your application to any service;
- if you don't see something in the design, you can implement this functionality in UI just with your vision and understanding.
