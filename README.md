# todolist
Users can store their tasks in a database, see their tasks, and mark them complete.

## Context

One of the main skills we seek to learn here at Learners Guild is the creation of full-stack web applications. This project is an excellent opportunity to see how all your various foundational skills will come together into a complete, functioning website.

When working on this goal, you'll encounter questions like:

- How could the application logic be structured satisfy this user story?
- How should the code be broken up and organized, and where should the different parts live?
- When and where will users run into errors, and how should the app respond to them?
- What should be tested and how?
- What is the UI needed to satisfy this user story?

## Specifications

#### General
- [ ] Code uses a linter and there are no linting errors.
- [ ] Repository includes a README file with basic installation and setup.
- [ ] All dependencies are properly declared in `package.json`.
- [ ] All major features are added via pull requests with a clear description and concise commit messages.
- [ ] Every pull request has been reviewed by at least one other person.
- [ ] The artifact produced is properly licensed, preferably with the [MIT license][mit-license].

#### Functionality
- [ ] Users can create to do list items.
- [ ] Users can delete unwanted to do list items.
- [ ] Users can check items off as completed.
- [ ] Users can edit the text on existing to do list items.
- [ ] UI renders to do items differently when they are completed (using a checkbox or some other indicator).
- [ ] When an error occurs, the user is notified with modal message.\*
- [ ] Backend uses Node.js and Express.
- [ ] App persists to do list items in a database.

#### Testing
There are thorough tests for all functionality involved in interacting with the database.
- [ ] There are tests for creating to do list items.
- [ ] There are tests for deleting to do list items.
- [ ] There are tests for completing to do list items.
- [ ] There are tests for editing to do list items.
- [ ] All tests are passing.

\* A quick and easy way to do this is to use the `alert()` function.

### Stretch

- [ ] App is deployed on Heroku.
- [ ] Users can rearrange to do list items.
- [ ] Users can create multiple to-do lists.
- [ ] Users have their own account and can sign up and log in/out.
- [ ] App is written with ES6 and compiled using [babel][npm-babel].

[npm-express]: https://www.npmjs.com/package/express
[npm-babel]: https://www.npmjs.com/package/babel
[npm-pg-promise]: https://www.npmjs.com/package/pg-promise
[postgres]: https://www.postgresql.org/
[material-design]: https://material.io/
[mit-license]: https://opensource.org/licenses/MIT
