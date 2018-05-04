# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Requirements

In order to get a satisfactory score, by the time you present your project, you **must** meet the following requirements:

### Deployment
* Be deployed online, where the rest of the world can access it on [Heroku](https://www.heroku.com/).
* Deploy on your public Github page, not Github Enterprise.

### Version Control
Demonstrate using version control by:
* Sharing your work through a git repository hosted on Github.
* Making frequent, cohesive commits dating back to the **first day**
of the project week. A **minimum** of 30 commits is required!

### Documentation
* A `README.md` file containing:
  - A Project description
  - A Link to the Deployed App
  - A Link to the Trello Board
  - A Link to any Wirefames or Mockups (or inline photos / screenshots will work too!)
  - A link to the ERD
  - A list of technologies, libraries, and/or frameworks used in the project, such as `Express.js`, `React.js`, or `Semantic-UI`
  - What you would like to add in version 2.0
* Wireframes or Mockups -- what does the app look like?
  - Simple: take a picture of a whiteboard drawing
  - Advanced: use a tool such as [Balsamiq](https://balsamiq.com/) or [Mockingbird](https://gomockingbird.com/home)
* User Stories in a PUBLIC [Trello](https://trello.com/) board
  - You should have a Trello board tracking your User Stories
  - Board lists should include:
    * Backlog
    * Todo
    * In Progress
    * Under Review
    * Done
    * Icebox

### Sample Project `README.md` files:
* [Tic-Tac-Toe](https://github.com/iamsydsmith/tic-tac-toe)
* [FootUp](https://github.com/wschaeferiii/footup)

### Technical Requirements

Your app must:

* **Have at _least_ 3 models** (more if they make sense) – one representing someone using your application (a user), and two that represent the main functional ideas for your app
  * **Devise/Passport is not a requirement**
  * If you don't feel 100% confident that you understand how to work with auth and sessions, build out your user model without Devise.
  * The creator of `devise_token_auth` has provided this template for integrating the library into an existing model.  Check it out in the link [here](https://github.com/lynndylanhurley/devise_token_auth/wiki/Setup-migrations-for-an-existing-User-table)
* **Have validations on any applicable fields on your models**
* **Have complete RESTful routes** for at least one of your resources with GET, POST, PUT, and DELETE
* **Use MongoDB or Postgres SQL for your database**
* **Include wireframes** that you designed during the planning process
* **Include User Stories**
* **Include ERDs**
* Have **semantically clean HTML and CSS**
* Polished and professional looking front-end, either using custom CSS (via styled-components) or a library. Or Both!!
* **Be deployed online** and accessible to the public via Heroku

Stretch Goals: 
 * Auth using Devise
 * Redux
 * Automated Tests Using Jest / Rails
 * Use a third-party API e.g. Google Maps for geolocation, or anything you want

### Necessary Deliverables

* A **working full-stack application**, hosted on Heroku
* A **link to your hosted working app** in the URL section of your Github repo
* A **git repository hosted on Github**, with a link to your hosted project, and frequent commits dating back to the **very beginning** of the project. Commit early, commit often.
* **A ``readme.md`` file** with explanations of the technologies used, the approach was taken, unsolved problems, and notes to yourself so you can come back to your project later in the course and be able to pick up your train of thought, etc.
* **Wireframes of your app**, hosted somewhere & linked in your readme
* A link in your ``readme.md`` to the publicly-accessible **user stories you created**

Most importantly a **technical demonstration** of your app which:

* Is 5-10 minutes in length
* Shows off all features of the app
* Explains the technical details
* Explains the technical challenges
* Explain the pros / cons of the development stack you chose for this application.
* Explains which improvements you might make

### To Submit

* Submit the completed project, wireframes, images, and deployed link to Schoology.

### Before you start creating your repo or coding.

Read [Git Collaboration Workflow](https://git.generalassemb.ly/atl-wdi/project-vagabond/blob/master/git-collaboration-workflow.md)

### DO NOT!!
Your app **must not**:
* Delete your repository at any time or start over.
* Rely on refreshing the page for any functionality.
* Have any user-facing bugs.
* Display non-functional buttons, nor buttons that do not successfully complete a task.
* Show actions at inappropriate times (example: sign out button when not signed in).
* Forms not clearing at appropriate times (example: sign up form not clearing after success).
* Display errors or warnings in the console.
* Display debugging messages in the console.
* Be presented on your local port instead of Heroku.