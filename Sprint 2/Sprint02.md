# Sprint 2 (11/20-12/01)

## Forecast

We forecasted that we could get **13 story points** done during this sprint. We forecasted much higher value than sprint 1 (15 points), even after accounting for the Thanksgiving Holiday plans of team members, using Yesterday's Weather Forecasting Pattern. Based on past sprint we feel that our normalized velocity can be three times of what we accomplished in sprint 1, (i.e. 15 points), but given thanksgiving holidays we factored a 80-90% capacity for the team and hence arrived at 13 story points.

The forecast correlated to the next six stories from our [Initial Ordered Product Backlog](https://trello.com/b/qb2G2V5r/product-back-log), with the 'Navigation Experience' Page story being introduced based on stakeholder feedback after release 1.



| __Number__ | __Title__ | __Story Points__ | __Summary__
| --- | --- | --- | --- |
| 1. | 'What is AI' page| 3 pts | As a site owner, Andy wants to share an overview with clients that helps them learn the fundamentals about Machine Learning & AI; what makes a Neural Network different from a Web Application; examples of popular real world applications; and, what AI means for the future of business and the human race as a whole. |
| 2. | 'User Comments' Blog Feature | 1 pts | As a blogger, Andy can leave comments on blog posts to share thoughts, ask the author questions, or discuss ideas with other users. Further as a user Andy would like username and profile image to appear beside the content of his comment so that other user's can clearly identify his comments from other user's comments. Furthermore, other users should be able to "like", "dislike", or "flag" any comments for offensive or inappropriate language.  |
| 3. | 'User Authentication for Blogs' Blog Feature | 2 pts | As a blogger, Andy wants that other users can clearly identify him from other bloggers. Also, he would like to edit his blogs. For his convenience, Andy wants to be able to log in with his Facebook/Google/Email address. |
| 4. | 'Navigation Experience' site feature | 2 pts | As a site user, Andy wants tabs to be highlighted to show the current tab and would like a top nav and left nav, instead of dual menus, for easier navigation of the site. |
| 5. | 'Static Tagging for Category Assignment' Blog Feature | 2 pts | As a site administrator, Andy can use tags and associate it with each blog post so users can eventually filter results based on tags. Here is an initial tag list  "Real World Application", "Class of Neural Network", "Chat Bots", Speech Recognition", "Machine Learning", "Class of Artificial Intelligence". |
| 6. | 'Upvoting/Downvoting for blogs' Blog Feature | 3 pts | As a site user, Andy wants users to be able up-vote and down-vote blog posts so that the community can filter the best content to the top. |

## Kanban Board

We are continuing to use [Trello](https://trello.com/b/qb2G2V5r/product-back-log) as our Kanban Board and screenshot provided below:

![Kanban Board](https://github.com/BrainCradle/CSCIE-71-Project/blob/master/Sprint%202/kanban-board.png).

## Actual

We had few hiccups because of unavailability of product owenr during Thanksgiving holidays for clarification on stories, so were able to close only on **4 user stories / 8 story points as against 6 user stories / 15 story points forecasted within the sprint**

We deployed the 4 user stories (What is AI, User Comments on Blogs, User Authentication for Blogs & Navigation Experience) in production at following URL:

[Prod Site](https://braincradleai.firebaseapp.com)

### Prod Screens, Acceptance Criteria and Sprint Task 

Reference our Sprint Tasks & Acceptance Criteria:

1. what is AI

![What is AI Prod Screen](https://github.com/BrainCradle/CSCIE-71-Project/blob/master/Sprint%202/AI-Home.png).

![What is AI](https://github.com/BrainCradle/CSCIE-71-Project/blob/master/Sprint%202/What-is-AI.png). 

2. User Comments

![User Comments Screen](https://github.com/BrainCradle/CSCIE-71-Project/blob/master/Sprint%202/User-Comments_screen.png).

![User Comments](https://github.com/BrainCradle/CSCIE-71-Project/blob/master/Sprint%202/User-Comments.png).

3. User Authentication

![User Auth Screen](https://github.com/BrainCradle/CSCIE-71-Project/blob/master/Sprint%202/User-Auth-Screen.png).

![User Auth](https://github.com/BrainCradle/CSCIE-71-Project/blob/master/Sprint%202/User-Auth.png).

4. Navigation Experience

![Navigation Experience Screen](https://github.com/BrainCradle/CSCIE-71-Project/blob/master/Sprint%202/Nav-Screen.png).

![Navigation Experience](https://github.com/BrainCradle/CSCIE-71-Project/blob/master/Sprint%202/NavExperience2.png).

## Burndown

Our burndown chart, shown below, is based on the completion of each user story [Refer to Trello for Stories "Done in Sprint 2"](https://trello.com/b/qb2G2V5r/product-back-log) which were decomposed from the PBIs committed to the sprint. 

![Burndown Data for Sprint 1](https://github.com/BrainCradle/CSCIE-71-Project/blob/master/Sprint%202/sprint2-burndown-excel2.png)

![Burndown Chart Sprint 1](https://github.com/BrainCradle/CSCIE-71-Project/blob/master/Sprint%202/sprint2-burndown-chart.png)

## Daily Scrums (2-day sample)

### Monday, November 20th
#### Digant
_What did you accomplish yesterday?_
> Decomposed stories into tasks

_What will you do today?_
> Research on content for blogs

_What obstacles are impeding your progress?_
> none

#### Shivas
_What did you accomplish yesterday?_
> Worked on navigation enhancements.

_What will you do today?_
> Continue working on navigation enhancements.

_What obstacles are impeding your progress?_
> none

#### Ailing
_What did you accomplish yesterday?_
> Worked on blog features

_What will you do today?_
> Continue working on blog features

_What obstacles are impeding your progress?_
> None

### Sunday, November 25th

#### Digant
_What did you accomplish yesterday?_
> Content for Blogs 

_What will you do today?_
> Content for Neural Net pages

_What obstacles are impeding your progress?_
> none

#### Shivas
_What did you accomplish yesterday?_
>  Reasearch on CI/CD.

_What will you do today?_
> Continue working on CI/CD

_What obstacles are impeding your progress?_
> Limited experience on CI/CD tools

#### Ailing
_What did you accomplish yesterday?_
> Neural Net Overview Page

_What will you do today?_
> Update BDD test suite

_What obstacles are impeding your progress?_
> None.


### Impediments

_IRP = Impediment Removal Plan_

#### Shivas - Nov 22nd, 06:45 pm
> Not sure how to setup CI/CD framework?

IRP: Links provided on slack (https://medium.com/@ved.pandey/setting-up-jenkins-on-mac-osx-50d8fe16df9f) and (https://houssein.me/continuous-integration-angular-firebase-travisci)

## Collaboration
Our Team met as a group at least 2x per week to synchronize and elevate obstacles along our critical path; additionally, individuals teamed up to pair program in order to solve various engineering tasks.  

| __Date__ | __Meeting Type__ |
| --- | --- |
| 20 NOV | Daily Scrum |
| 22 NOV | Mob Programming |
| 26 NOV | Daily Scrum |
| 01 DEC |Standing Team Meeting |
| 03 Dec | Sprint Review & Retrospective |

1. Example of a peer code review (part of our [Definition of Done](https://github.com/BrainCradle/CSCIE-71-Project/blob/master/README.md))

 ![Code Review](https://github.com/BrainCradle/CSCIE-71-Project/blob/master/Sprint%202/mob-program1.png)

2. Example of a mob programming  (part of our [Definition of Done](https://github.com/BrainCradle/CSCIE-71-Project/blob/master/README.md))

 ![Mob Programming](https://github.com/BrainCradle/CSCIE-71-Project/blob/master/Sprint%202/mob-program3.png)

3. Example of a standing team meeting
 
 ![Standing Team Meeting](https://github.com/BrainCradle/CSCIE-71-Project/blob/master/Sprint%202/CollabPic1.png)
 ![Standing Team Meeting](https://github.com/BrainCradle/CSCIE-71-Project/blob/master/Sprint%202/CollabPic2.png)
 ![Standing Team Meeting](https://github.com/BrainCradle/CSCIE-71-Project/blob/master/Sprint%202/CollabPic3.png)
 

### Behavior-Driven Development & Unit Tests

We continued to use the [cucumber](https://cucumber.io/) framework and  [selenium](http://www.seleniumhq.org/) to run our Behavior-Driven Development (BDD) tests. Specifically we tested user login for blog view using BDD. See the screenshots below (showing test failed and then passed). 

![BDD Fail Screen](https://github.com/BrainCradle/CSCIE-71-Project/blob/master/Sprint%202/BDD-fail.png)
   
 ![BDD Pass Screen](https://github.com/BrainCradle/CSCIE-71-Project/blob/master/Sprint%202/BDD-pass.png)
 
 BDD source code is checked here: https://github.com/BrainCradle/BrainCradle/tree/master/BDD
   
Our TDD and unit tests (we have used tool called Karma) are shown below including a failed one and passed ones.

![TDD fail](https://github.com/BrainCradle/CSCIE-71-Project/blob/master/Sprint%202/TDD-fail.png)


![TDD fail2](https://github.com/BrainCradle/CSCIE-71-Project/blob/master/Sprint%202/TDD-pass.png)


![Unit cases passed](https://github.com/BrainCradle/CSCIE-71-Project/blob/master/Sprint%202/TestCases-Passed.png)
 
  
![Refer to console](https://github.com/BrainCradle/CSCIE-71-Project/blob/master/Sprint%202/TDD-success.png)
 

The unit test cases are checked here: https://github.com/BrainCradle/BrainCradle/tree/master/braincradleapp/tests

## Sprint Review and Retrospective

We conducted our sprint review with stakeholders and Scrum Team retrospective on NOV 19TH. 

### Sprint Review Stakeholder Feeback

We reviewed the sprint 2 user story in production [User Comments for Blogs](https://braincradleai.firebaseapp.com/#/blogs) with an AI student stakeholder, Hazem Salama, who is a software engineer with Verizon Communications and a student at Harvard Extension School. Hazem is pleased with the progress of our efforts. He offered the following feedback on the blog functionality, mostly looking towards the next sprint:

- I like the simple design of the blog and it looks very pleasing
- The navigation is easy and not complicated
- I cannot vote up blog entries
- When I try to enter a comment but decide to cancel, the cancel button does not function as expected
- Tab order is not working as expected
- When I expand a blog entry to read the full blog and press the back button then it takes me back to previous page. Its slightly confusing

This feedback will be absorbed into the product backlog (and groomed) ahead of sprint 3 planning.
 
### Scrum Team Retrospective

While the retrospective is a generally closed door event, we chose to share these highlights:

- Finalzing right CI/CD framework took time as there were many choices. Narrowing focus to couple of frameworks and quick PoCs helped finalize the right tool.
- There was confusion on Sprint 1 feedback/grades from Richard. Clarifying it on slack channel helped provide feedback on how to improve in Sprint 2
- Not having product owner available during holidays hampered our ability to complete couple of stories as we needed clarification on the story. We then came to an agreement with product owner that we would deliver only 4 stories since the sprint window was too short post clarification. To mitigate this we have now obtained emergency contact details of the entire team in case we need to reach anybody on emergency basis.

### Continuous Integration / Continuous Deployment
We also solidified our CI/CD process in this sprint (started in sprint1).
![CI process](https://github.com/BrainCradle/CSCIE-71-Project/blob/master/Sprint%202/CI-CD.png)

Travis CI is a continuous integration platform we are using with your Github projects. Using Travis we have Build Pushes and Build Pull Requests turned ON. This means that anytime we push our changes to our Github repository or merge a pull-request, Travis CI will trigger a build and runs  tests every time we push to our branch (or merge a pull request) - see image below. Once the build succeeds it triggers a script to deploy the build to Firebase in production.

 ![Travis Process](https://github.com/BrainCradle/CSCIE-71-Project/blob/master/Sprint%202/mob-program2.png)

![Travis process](https://github.com/BrainCradle/CSCIE-71-Project/blob/master/Sprint%202/Travis_pic.png)


