## What is an RFW?
* RFW stands for **request for work**. 
* It is a detailed product specification that the product department submits following a standard template. 
* It should be filled by all the stakeholders in a meeting. 
* It should focus on what the developers should make and why they should make it.

## What is an RFC?
* RFC stands for **request for comments**. 
* It is a detailed engineering specification that R&D department submits following a standard template, based on an RFW. 
* It should focus on how specifications will be satisfied and when.
* It should be approved within three days after seeking aprroval from NT, Mikko, and Elie.
* Once an RFC is approved, it can't be changed as this is like playing on a football ground with shifting goal posts.
* During the RFC review period, developers can reach out to their fellow developers to get opinions.
* An RFC should contain no more than two weeks worth of work
* Each RFC work phase should:
   * Create value
   * Take less than a day
   * Be testable
   * Be converted to issue and linked to a PR so that peer developers can review it and merge the code to main code.
   * Be placed in a project board to track the workphases

## How to start developing

Once an RFC is ready:

- Create new repo using the [openpecha-project-template](https://github.com/OpenPecha/openpecha-project-template/generate).
- Make a kanban board in the project repo (its name should be same as repo name)
- Transfer the RFC (the issue in the Requests repo) to the new project repo
- Convert all the work items into issues
- Add all the issues to the kanban board
- Clone the repo to local
- Make a feature branch
- Checkout to that branch
- Start working on it
- Once tested send PR to main
- Make a next feature branch for the next work item and continue until you have completed all the items

**Daily standup meetings**
* Daily standup meetings are from 4-5 p.m. IST
* During daily standup meeting, developers answer these three questions:
   * What have you done today?
   * What are you going to do tomorrow?
   * What kind of unexpected issues are you facing that is stopping you from complete you work items?
* Meetings will take up to 10 minutes and each developer will get five minutes.
* The sprint master will joining the meeting to make sure that the meetings happen every day and are on time.