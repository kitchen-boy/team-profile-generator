# team-profile-generator

# Table of Contents:
* [Project Description](#description)
* [Task Completed](#task-completed)
* [User Story](#user-story)
* [Acceptance Criteria](#acceptance-criteria)
* [Installation](#installation-setup)
* [Screenshots and Video Link of application](#screenshots-and-video)
* [Links](#links)
* [Credits](#credits)

# DESCRIPTION:
A Node.js command-line application that takes in information about employees on a software engineering team and generates an HTML webpage that displays summaries for each person.

#TASK COMPLETED: 
Unit tests for each part of the code have also been written and ensured that all code passes all tests, because testing is key to making code maintainable. 

#USER STORY:
```md
AS A manager
I WANT to generate a webpage that displays my team's basic info
SO THAT I have quick access to their emails and GitHub profiles
```
# ACCEPTANCE CRITERIA:
```md
GIVEN a command-line application that accepts user input
WHEN I am prompted for my team members and their information
THEN an HTML file is generated that displays a nicely formatted team roster based on user input
WHEN I click on an email address in the HTML
THEN my default email program opens and populates the TO field of the email with the address
WHEN I click on the GitHub username
THEN that GitHub profile opens in a new tab
WHEN I start the application
THEN I am prompted to enter the team manager’s name, employee ID, email address, and office number
WHEN I enter the team manager’s name, employee ID, email address, and office number
THEN I am presented with a menu with the option to add an engineer or an intern or to finish building my team
WHEN I select the engineer option
THEN I am prompted to enter the engineer’s name, ID, email, and GitHub username, and I am taken back to the menu
WHEN I select the intern option
THEN I am prompted to enter the intern’s name, ID, email, and school, and I am taken back to the menu
WHEN I decide to finish building my team
THEN I exit the application, and the HTML is generated
```

# INSTALLATION SETUP
**MANDATORY REQUIREMENT FOR SUCCESSFUL APPLICATION:**  **NODE.JS MUST BE INSTALLED!**

1. Download all files from the repository.
2. CD into the repository.
3. Run this command to install [inquirer](https://www.npmjs.com/package/inquirer)
```md
npm install inquirer
```
4. Run this command to install [jest](https://www.npmjs.com/package/jest)
```md
npm install jest
```
6. Run this command to run the application
```md
node index.js
```

# SCREENSHOTS AND VIDEO
[Walkthrough Video]()

![Screenshot]()
![Mock-Up]()
The image shows the generated HTML's appearance and functionality.

# LINKS
* Link to the code repository: (https://github.com/kitchen-boy/team-profile-generator) 

# CREDITS
Kaye Chen-Boyce

### References and tutorials utilized
* []()
* BCS Learning Assistant
* [How to use Jest for running the unit tests](https://www.npmjs.com/package/jest)
* [How to use Inquirer](https://www.npmjs.com/package/inquirer)
* [A collection of common interactive command line user interfaces](https://github.com/SBoudrias/Inquirer.js)
* Instructor Scott Burman
* Tutor Alexis San Javier


### Suggested directory structure:
```md
.
├── __tests__/             //jest tests
│   ├── Employee.test.js
│   ├── Engineer.test.js
│   ├── Intern.test.js
│   └── Manager.test.js
├── dist/                  // rendered output (HTML) and CSS style sheet      
├── lib/                   // classes
├── src/                   // template helper code 
├── .gitignore             // indicates which folders and files Git should ignore
├── index.js               // runs the application
└── package.json           
```