# Creating new repositories

## Convention for Naming Repositories

Using as an example a repository which is the "frontend" for "something":

*   If you're creating a production repository, name it `Something-Frontend`
*   If it's not a production repository, nor will it be in the future, name it `something-frontend`
*   Note how context comes first and specifics come second
*   Note how capitalization is handled in both situations
*   Names must not contain more than four words, but should strive to use two

## Creating the Repository

1.  When creating a new repository under **OpenPecha**, do it using the [new-repo-template](https://github.com/OpenPecha-dev/new-repo-template) by selecting it in the new repository creation dialogue.
2.  Once the repository is created, start by editing the `README.md` of the repository, carefully following the comments in that file to make sure that there are no devitations from the standard in formatting or any other aspect
3.  Add a short description in the "About" section
4.  If the repository has any docs, add them to `/docs` in the root of the repository
5.  Review your changes in several quick iterations:
    1.  Text clarity. _Can an 8-year-old understand what I just wrote?_
    2.  Message clarity. _Can I use 🔣 code snippets, 🖼️ images or 🙃 emojis to make my message clearer?_
    3.  Spelling mistakes, [capitalization](%5Burl%5D(https://www.grammarly.com/blog/capitalization-rules/)) and punctuation
    4.  Layout and links
