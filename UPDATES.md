# UPDATE LOG
## NOTES:
* In order to stay active in the job search most of my work will be done late afternoon or evening time.
* Next up, starting to tackle the preliminary front end/Angular.

## 06.12.17 - Began Preliminary Research
* identified 4 main requirements
* researched 10 production projects as case studies
* identified 20+ functionality ideas for potential use in projects
* Created git Repository (https://github.com/devcix/ngScrumDogg.git)

## 06.13.17 - Began Laying Groundwork
* created git repository
* captured general project goals in README.md file
* captured research findings in RESEARCH.md file
* created UPDATELOG.md file

## 06.13.17 - Built RESTful Server - And MongoDB Schema
* developed the server side (express)
  * installed several modules
* added preliminary database schemas (Users, Tasks, and Reports)
* added Report, User and Task Controllers
* added routing solution

## 06.14.17 - Mocked Up Front End views
* Created Mockups for
  * Standup Page
  * User disciplines Page
  * User Profile Page
  * User Tasks Page

## 06.14.17 - Began Dev of Client Side Structure
* Started off utilizing Yomen, and Grunt serve to set up for mockup but windows doesn't seem to play well with these technologies
* Abandoned Yomen and Grunt solutions in lieu of a more straight forward approach to such a small application.

## 06.15.17 - Continuing development of Client side
* Moved Client side into Server Directories
* Added User List functionality (Parses user Json object into user list in side bar)
* Added User List => Hotseat functionality (Clicking on a user in user list brings up Hotseat Form dialog in main content area)
* Added User List Randomizer function (Clicking Randomize button randomizes the list of users)
* Added preliminary UX work on User list (Clicking Users now highlights them and fills the star Icon. Users also have hover state.)

## Todo:
* Create StandupRecords array on scope object (capture date, user, yesterday, today, blockers as a single object for each day).
* Develop interaction between Hotseat and StandupRcords (2way bind form fields so that Adding/Changing information saves it to the StandupRecords Array, and upon forms loss of focus, the data is saved)
* Develop final UX for user link clicks
* Create clever 404 messages from dead links.
* Final pass for revision
