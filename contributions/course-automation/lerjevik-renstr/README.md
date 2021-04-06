# Course Automation: Upvote other students’ work
 
## Members

- [Dina Lerjevik](https://github.com/dmariel) (lerjevik@kth.se)
- [Anders Renström](https://github.com/Renstrom) (renstr@kth.se)
 
## This is a repository where the functionality is demonstrated. A PR will be made from this branch `course-automation-2` to `course-automation-1`.

1. In this example, this repository branch corresponds to a student's course-automation project on their fork
2. The student performs a PR from this repository to the other repository branch, which corresponds to `KTH/devops-course` in this example. The student makes sure to include the label `Upvote - Course Automation`. This sets of the following events:
   1. An issue Upvote projects - Course Automation is created, if no such issue already exists. The issue body includes a description of how to use the functionality, directed to the students. Furthermore, a “Top-list” that is going to show the most upvoted projects is incorporated to the issue, in the form of a comment.
   2. Next, a comment is automatically added to the issue thread. The comment includes: the title of the student's PR, a link to the PR and a link to the repository. This information enables other students to read about the project.
   3. The student recieves a comment on their PR, stating that a comment has been added to the issue Upvote projects - Course Automation (including a link to the issue).
3. This enables other students to upvote their classmates projects, by inserting 👍 on the comments in the issue Upvote projects - Course Automation.
4. The upvotes are collected and visualized in the “Top-list”, which is sheduled to be automatically updated every 5 minutes.