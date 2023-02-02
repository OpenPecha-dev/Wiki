
# Workflow for developers

This is the workflow for when an OpenPecha developer receives a new RFW from management:

## 1. Create an RFC

Review the RFW and [create an RFC](https://github.com/OpenPecha/Requests/issues/new?assignees=&labels=&template=RFC.md&title=%5BRFC%5D) for it. This involves:

1. Understanding the work
1. Considering several possible solutions
1. Understanding the pros and cons of each solution
1. Choosing the best solution
1. Filling out the RFC
1. Submitting it in the [Requests repo](https://github.com/OpenPecha/Requests/) 

See [How fill out an RFC](#) for specific directions.

> **Note** This process should take no more than two days.

## 2. Get the RFC approved

1. Let the RFW owners and RFC reviewers know that the RFC is ready for review.
1. Meet on-one-one with each member of the management team to go over the RFC.
1. Integrate management's suggestions.
1. Submit the RFC for management to sign off on.

> **Note** This process should take no more than two days.

## 3. Create a repository

If the approved RFC is for a **new** project:

1. Create a new repository for the project using the [OpenPecha project template for Python projects](https://github.com/OpenPecha/openpecha-project-template) or [this template for projects in other languages](https://github.com/OpenPecha/new-repo-template).
1. Update the repo's README file.
1. Transfer the RFC to the new repo.

If the approved RFC is for an **ongoing** project:

1. Update the repo's README file if needed to include information about the new work you are doing.
1. Transfer the RFC to the repo where you will be working.

## Repository

Using as an example a repository that is the "frontend" for "something":

*   If you're creating a production repository, name it `Something-Frontend`
*   If it's not a production repository, nor will it be in the future, name it `something-frontend`
*   Note how context comes first and specifics come second
*   Note how capitalization is handled in both situations
*   Names must not contain more than four words, but should strive to use two

## Creating the Repository

1.  When creating a new **OpenPecha** repository, use [new-repo-template](https://github.com/OpenPecha-dev/new-repo-template) by selecting it in the new repository creation dialogue.
2.  Once the repository is created, start by editing the `README.md` of the repository, carefully following the comments in that file to make sure that there are no devitations from the standard in formatting or any other aspect
3.  Add a short description in the "About" section
4.  If the repository has any docs, add them to `/docs` in the root of the repository
5.  Review your changes in several quick iterations:
    1.  Text clarity. _Can an 8-year-old understand what I just wrote?_
    2.  Message clarity. _Can I use 🔣 code snippets, 🖼️ images or 🙃 emojis to make my message clearer?_
    3.  Spelling mistakes, [capitalization](%5Burl%5D(https://www.grammarly.com/blog/capitalization-rules/)) and punctuation
    4.  Layout and links

## 4. Create a GitHub project in the repository

1. Create a GitHub project in the repo.
1. Update your project's description and README.
1. Add a column after **In Progess** and call it **PRs in Review**.

## 5. Convert workphase items into issues

1. Convert each item in the RFC's workphase section [into an issue](https://docs.github.com/en/issues/tracking-your-work-with-issues/creating-an-issue#creating-an-issue-from-a-task-list-item).

## 6. Assign issues to people and add to project board

1. Assign each issue to yourself or your teammate if you are working as a team.
1. [Add each issue to the project](https://docs.github.com/en/github-ae@latest/issues/organizing-your-work-with-project-boards/tracking-work-with-project-boards/adding-issues-and-pull-requests-to-a-project-board).

## 7. Move the RFC back to the Requests repo

1. [Move the RFC back to the Requests repo](https://docs.github.com/en/issues/tracking-your-work-with-issues/transferring-an-issue-to-another-repository) so management can easily find it.

## 8. Do the work and create pull requests

1. Move the issue/workphase you are working on to the **In Progress** column of your project board.
1. Work on it and add commits.
1. Go to your daily standup meeting. 
1. When you finish the issue issue/workphase, move it to the **PRs in Review** column of your project board
1. Submit a PR for the issue/workphase.
1. Let your assigned reviewers know the PR is ready for them.

## 9. Move to the next issue/workphase

After the PR has been merged:

1. Move the issue to the **Done** column of the project board.
1. Move on to the mext issue and repeat step 8 until the RFC is finished.

## 10. Review the process

After you finish all the workphases of the RFC:

1. Review the process with your scrum master and teammate(s), if any, to see what worked well and what didn't work so well. Use this knowledge to prepare and complete your next RFC.