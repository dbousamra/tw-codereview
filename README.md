## Overview:
Some ideas and thoughts around what we can do to improve the ThoughtWorks interview-candidate code review process.

### Affects:

- Recruiters
- Candidates
- Reviewers

### Problems:

- Not a huge amount of visibility around whether there is code needing to be reviewed.
- Handle on the code isn't always great - occasionally wrong code sent out, sometimes problem statement is omitted.
- Data spread across various places (email mainly)

### Ideas:

##### As a Recruiter:

1. I log onto http://codereview.thoughtworks.com using there CAS credentials.
2. I can add a candidate to the system with the following details:
  - Name (may or may not be visible to reviewers).
  - Role and proposed grade.
  - Problem (Trains etc).
  - Extension problem (Yes/No)
  - Extra comments (done in office, done without internet etc).
3. I am then is presented with a link they can send to the candidate. Eg: http://codereview.thoughtworks.com/gJfH27h33
4. I can then email this to the candidate.

![alt text](https://github.com/dbousamra/tw-codereview/raw/master/mockups/CodeReview_AddCandidate.png "Recruiter")

##### As a Candidate:

1. I receive an email with the following link: http://codereview.thoughtworks.com/gJfH27h33
2. This link contains the problem document and an option to submit code (as a ZIP file, a Github/Bitbucket repository etc).
3. Recruiter is then emailed with a notification that the code is submitted.

![alt text](https://github.com/dbousamra/tw-codereview/raw/master/mockups/CodeReview_SolutionSubmission.png "Candidate")

##### As a Reviewer:

1. I am asked to review some code by recruiters, either directly, or a company wide code-review ask.
2. I log onto http://codereview.thoughtworks.com with my CAS credentials.
3. I see all open candidates (localized to my region by default).
4. I can click a candidates open code review and view his code in browser. I can add comments, discuss with other ThoughtWorkers etc.
5. I can vote quantitatively on various criteria (Readability, Design, Ease of extendability etc).

![alt text](https://github.com/dbousamra/tw-codereview/raw/master/mockups/CodeReview_Reviewer.png "Reviewer")

![alt text](https://github.com/dbousamra/tw-codereview/raw/master/mockups/CodeReview_HomePage_Taskboard.png "Reviewer")