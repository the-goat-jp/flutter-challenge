## Flutter Coding Challenge


### Challenge Overview

Implement sample App on the assumption you are in a specific situation.

#### Assumptions

- Select A or B as a situation you are in. See situations below.
- Write the selected situation in [README.md](http://readme.md/), indicating your decision making revolving around your selected situation. You can write this however you like.
- The selection of A or B itself has no impact to your evaluation.

**A. Coach a junior engineer**

A junior Flutter engineer joined to your team. To coach the engineer, you are going to demonstrate implementation of a sample app. The structure of the app should be as simple as possible.

**B. Design and implement an app as a long term project**

You are a tech-lead of a Flutter team with 5 members. The team is going to develop a new Flutter app. It is supposed to be a long term project to develop and maintain the app within the team. Before starting the development with the team members, you are going to design the app and implement fundamental functionalities as the tech lead.

---

### Challenge Specifications

Create an application that fetches data from the Gutenberg Library API to display books from their library. 

Gutenberg API: http://gutendex.com/

**Required functionality
- Create an initial screen with a list/grid of books from Gutenberg Library's collection
  - Implement a search functionality
  - Implement an infinite scroll pagination
- A screen with details of a certain book of the collection.
  - This screen is opened when you tap an item in the initial screen. 
  - What to display (title, cover, author, etc.) is up to you
- A third screen containing a list/grid of books that share the same characteristics.
  - This screen is accessed when you tap one of the details in the detail screen
  - e.g. Tapping on author name "Jane Austen" would show a list of other books by "Jane Austen"
  
  
  
**Optional
- Improve UI/UX
- Anything else you would like to add


  <img src="list.png" width="200"> <img src="detail.png" width="200">

---

### Challenge Requirements
- Flutter: Latest STABLE release


---


### Items to Submit
- Configure your project to run the app just by building the project
- Archive and submit the directory containing the project and [README.md](http://readme.md/) file.
- *Nice to have*:
  - Create the challenge in a public repository. Display the README on landing page.
  - Have an intact commit history for the whole development.
  
---

### Evaluation Criteria

This challenge will be evaluated based on the following. Each item will be evaluated on a scale of 1-5, 5 being the highest.
- Following project requirements
  - Does the submitted project run? Should have no code level related errors.
  - Is the project set up based on the requirements?
  
- App functionality and user experience
  - Does the app work based on the specs? Are the specs correctly implemented?
  - Does the app crash or lag on normal usage i.e. scrolling, tapping buttons, etc.? 
  - Does the app run on both mobile platforms (Android and iOS)?
  
- Code and development
  - Did the candidate use recommended design patterns?
  - Did the candidate use good naming conventions and comments?
  
- Others
  - Does the candidate write unit tests? Is the app testable?
  - Does the candidate handle errors with proper ways?

- *OPTIONAL. Only if project repository is submitted.*
  - Are the commit messages clear and concise?
  - Does the commit message correctly relate to the change made?
  - Does the candidate commit reasonable amount of changes?

