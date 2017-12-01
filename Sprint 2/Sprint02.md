# Sprint 2 (11/20-12/01)

## Forecast

We forecasted that we could get **10 story points** done during this sprint. We forecasted double value than sprint 1 (5 points), even after accounting for the Thanksgiving Holiday plans of team members, using Yesterday's Weather Forecasting Pattern. Based on past sprint we feel that our normalized velocity can be four times of what we accomplished in sprint 1, (i.e. 20 points), but given thanksgiving holidays we factored a 50% capacity for the team and hence arrived at 10 story points (i.e. 50% of 20 points).

The forecast correlated to the next four stories from our [Initial Ordered Product Backlog](https://trello.com/b/qb2G2V5r/product-back-log), with the 'Navigation Enhancements' Page story being introduced based on stakeholder feedback after release 1.

| __Number__ | __Title__ | __Story Points__ | __Summary__
| --- | --- | --- | --- |
| 1. | 'Navigation Enhancements' feature | 2 pts | As a site user, Andy wants tabs to be highlighted to show the current tab and would like a top nav and left nav, instead of dual menus, for easier navigation of the site. |
| 2. | 'User Comments' Blog Feature | 3 pts | As a blogger, Andy can leave comments on blog posts to share thoughts, ask the author questions, or discuss ideas with other users. Further as a user Andy would like username and profile image to appear beside the content of his comment so that other user's can clearly identify his comments from other user's comments. Furthermore, other users should be able to "like", "dislike", or "flag" any comments for offensive or inappropriate language. |
| 3. | 'Neural Net Overview' Content| 3 pts | AAndy wants to share an overview with clients that helps them learn the fundamentals about Machine Learning & AI; what makes a Neural Network different from a Web Application; examples of popular real world applications; and, what AI means for the future of business and the human race as a whole. It should include a detailed explanation of their architecture complete with graphics, what they look like under the hood, and the parameters that are used in practice to develop and tweak them as models. |
| 4. | 'Tagging' Blog Feature | 2 pts | Andy can use tags associated with each blog posts and solution page to search for, filter results based on "Real World Application", "Class of Neural Network", topic, industry, etc., making it easier to find the content he is looking for. |


## Actual

We had few hiccups, but were able to close on the selected user story forecasted within the sprint (reference our [Definition of Done](https://github.com/BrainCradle/CSCIE-71-Project/blob/master/README.md)). 

We deployed the user story in production at following URL:

[Site Nav](https://braincradleai.firebaseapp.com)

### Acceptance Criteria and Sprint Task 

Reference our Sprint Task & Acceptance Criteria:

![Navigation Enhacements](https://trello.com/c/VS9duhzI/30-navigation-enhancements). 

![User Comments](https://trello.com/c/7beM3E70/4-user-comments)

![Neural Net Overview](https://trello.com/c/5un5qPPc/9-neural-net-overview)

![Tagging](https://trello.com/c/xOuJ6IcK/8-tagging)

## Burndown

Our burndown chart, shown below, is based on the completion of each user story [Refer to User Story in Trello](https://trello.com/c/4e62yBqy/10-site-navigation) which were decomposed from the PBIs committed to the sprint. 

![Burndown Data for Sprint 1](https://github.com/BrainCradle/CSCIE-71-Project/blob/master/sprint1_burndown_excel.png)

![Burndown Chart Sprint 1](https://github.com/BrainCradle/CSCIE-71-Project/blob/master/sprint1_burndown.png)

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
| 22 NOV | Standing Team meeting |
| 26 NOV | Daily Scrum |
| 02 Dec | Sprint Review & Retrospective |

1. Example of a peer code review (part of our [Definition of Done](https://github.com/BrainCradle/CSCIE-71-Project/blob/master/README.md))

 ![Code Review](https://github.com/BrainCradle/CSCIE-71-Project/blob/master/Sprint%202/mob-program1.png)

2. Example of a mob programming  (part of our [Definition of Done](https://github.com/BrainCradle/CSCIE-71-Project/blob/master/README.md))

 ![Mob Programming](https://github.com/BrainCradle/CSCIE-71-Project/blob/master/Sprint%202/mob-program2.png)

3. Example of a standing team meeting
 
 ![Standing Team Meeting](https://github.com/BrainCradle/CSCIE-71-Project/blob/master/Sprint%202/CollabPic1.png)
 ![Standing Team Meeting](https://github.com/BrainCradle/CSCIE-71-Project/blob/master/Sprint%202/CollabPic2.png)
 ![Standing Team Meeting](https://github.com/BrainCradle/CSCIE-71-Project/blob/master/Sprint%202/CollabPic3.png)
 

### Behavior-Driven Development & Unit Tests

We continued to use the [cucumber](https://cucumber.io/) framework and  [selenium](http://www.seleniumhq.org/) to run our Behavior-Driven Development (BDD) tests. Specifically we tested navigation enhancements using BDD. See the screenshots below (showing test failed and then passed). 

![BDD Fail Screen](https://github.com/BrainCradle/CSCIE-71-Project/blob/master/BDD_Fail_Case.png)
   
 ![BDD Pass Screen](https://github.com/BrainCradle/CSCIE-71-Project/blob/master/BDD.png)
 
 BDD source code is checked here: https://github.com/BrainCradle/BrainCradle/tree/master/BDD/BrainCradleTest
   
Our TDD and unit tests (we have used tool called Karma) are shown below including a failed one and passed ones.

![TDD fail](https://github.com/BrainCradle/CSCIE-71-Project/blob/master/TDD_Fail.png)

 ![unit cases passed](https://github.com/BrainCradle/CSCIE-71-Project/blob/master/TestCases_Passed.png)
 
 ![refer ot screenshot](https://github.com/BrainCradle/CSCIE-71-Project/blob/master/UnitTests.png)
 
![unit tests](https://github.com/BrainCradle/CSCIE-71-Project/blob/master/UnitTests2.png)
 
![unit tests](https://github.com/BrainCradle/CSCIE-71-Project/blob/master/UnitTests3.png)

The unit test cases are checked here: https://github.com/BrainCradle/BrainCradle/tree/master/braincradleapp/tests

## Sprint Review and Retrospective

We conducted our sprint review with stakeholders and Scrum Team retrospective on NOV 19TH. 

### Sprint Review Stakeholder Feeback

We reviewed the sprint 1 user story in production [Site Nav](https://braincradleai.firebaseapp.com) with our primary stakeholder, Andy.
![Andy Call Log](https://github.com/BrainCradle/CSCIE-71-Project/blob/master/Andy_Review_Call.png)
Andy is pleased with the progress of our efforts. He offered the following feedback, mostly looking towards the next sprint:

- Overall looks clean. Clearly labeled. Font is readable. 
- Loves the responsiveness. Woo Firebase! 
- Tab highlighting should be added as it doesn't show current tab.
- Dual menu is confusing. Maybe have a standard top bar nav and left hand nav
- Selecting the proper categories under the "Examples Tab" is extremely important. Prefer's the label "Examples" over "Solutions".
- Prefers the term "Real-world Applications" to  "Applications".

This feedback will be absorbed into the product backlog (and groomed) ahead of sprint 2 planning.
 
### Scrum Team Retrospective

While the retrospective is a generally closed door event, we chose to share these highlights:

- Angular, Karma & Firebase frameworks had an initial steep learning curve. More pinpointed documentation for features would really help in next sprint. Also framework experts should spend some time walking through the nuances of the code and best practices.
- Despite not being local - the team has managed to leverage tools like slack, google hangouts, conference calls, Trello etc. to collaborate virtually and make progress on the sprint. 
- However there is still no substitute to being able to work face to face in person and it took a while for the team to get comfortable and streamline commmunications. We should look for an opportunity to work together on a future sprint in person if circumstances and calendars permit.

### Continuous Integration / Continuous Deployment
We also solidified our CI/CD process in this sprint (started in sprint1).
![CI process](https://github.com/BrainCradle/CSCIE-71-Project/blob/master/Sprint%202/CI-CD.png)

Travis CI is a continuous integration platform we are using with your Github projects. Using Travis we have Build Pushes and Build Pull Requests turned ON. This means that anytime we push our changes to our Github repository or merge a pull-request, Travis CI will trigger a build and runs  tests every time we push to our branch (or merge a pull request) - see image below. Once the build succeeds we then it triggers a script to deploy the build to Firebase in poduction.

![Travis process](https://github.com/BrainCradle/CSCIE-71-Project/blob/master/Sprint%202/Travis_pic.png)

