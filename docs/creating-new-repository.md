# Creating new repositories

## Convention for Naming Repositories

Using as an example a repository which is the "frontend" for "something":

- If it's a production repository, the name will be `Something-Frontend`
- If it's not a production repository, nor will it be in the future, the name will be `something-frontend`
- Note how context comes first and the specifics come second
- Note how capitalization is handled in each case
- Names must not contain more than four words, but should thrive to use two words only

## Creating the Repository

1) When creating a new repository under **OpenPecha** make sure to always do it using the [new-repo-template](https://github.com/OpenPecha-dev/new-repo-template) by selecting it in the new repository creation dialogue.

2) Once the repository is created, always start by editing the `README.md` of the repository, carefully following the comments in that file to make sure that there is no devitation from the standard in terms of formatting or any other aspect

3) Add a short description in the About section

4) If the repository has any docs, add them to `/docs` in the root of the repository

5) Review your changes in several loops:
- Text clarity. _Can a 8 years old understand what you wrote?_
- Message clarity. _Can I use code snippets, images or emojis to make my message clearer?_
- Spelling mistakes, [capitalisation]([url](https://www.grammarly.com/blog/capitalization-rules/)) and punctuation
- Layout and links
