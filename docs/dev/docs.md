
# Filling out the docs in a new repository

Configure the site and update the content


## 1. Configuring the site

### 1. Update `docs/index.html`

Update these four lines with the name and URL of the project

Line 5: Update `Tool name` to the name of the tool.
Line 19: Update `Tool name` to the name of the tool.
Line 20: Update the URL to the new project's URL.
Line 36: Update `tool-name` in the URL to the name of the repository: `plugins: [EditOnGithubPlugin.create('https://github.com/openpecha/Toolname/blob/main/docs/`

### 2. Update the GitHub Pages path

On your projects GitHub page, navigate to **Settings** > **Pages**.

1. Under **Build and deployment**, set **Source* to **Deploy from a branch**.
2. Set **Branch** to **main**, select the **/docs** folder and save.

[insert image]

Update the Repo README

In the Repo README, update the following:

The repo name
The repo owners
Integrations
The URL for the docs (get from the github pages path. It should be https://openpecha.github.io/new-repo-name)


Update the Docsify site content

## 2. Updating the content

There are three essential pages and two optional pages to make a minimum viable documentation MVD


Pages:
- Overview
- Getting started
- Reference

and two optional pages

- Examples
- Background





### Overview

# Project name

(This is the project's homepage)

## Short conceptual overview

This page should tell users:

- What the project is/what it does
- What problem it solves
- How it works
- Any other high-level info that users might want to know before using it

## Good overview examples:

- [1](https://www.atlassian.com/software/jira/guides/more/jira-family#about-the-jira-platform)

- [2]()

- [3]()

> **Note**: For longer or more in-depth information, us the **conceptual overview** page and add it to the sidebar.


### Getting started

A getting started page should show users the shortest path to completing a common task with this tool. By following the steps on this pag, users can see how it works and appreciate its benefits.  

Good examples of quickstarts:

- [1](https://developer.chrome.com/docs/native-client/devguide/tutorial/tutorial-part1/)
- [2](https://www.electronjs.org/docs/latest/tutorial/quick-start)
- [3](https://getbootstrap.com/docs/5.3/getting-started/introduction/)

Sections:

Intro: Describe what you will do

Prerequisites

- Python version

-

Step 1: Installation

Describe how to install the software

Teach something basic that


### Configure

1. _Write the step here._
2. _Write the step here._

### Run

1. _Write the step here._
2. _Write the step here._

### Troubleshoot

1. _Write the step here._
2. _Write the step here._

<table>

<tr>

<td>

Issue

</td>

<td>

Solution

</td>

</tr>

<tr>

<td>

_Describe the issue here_

</td>

<td>

_Write solution here_

</td>

</tr>

<tr>

<td>

_Describe the issue here_

</td>

<td>

_Write solution here_

</td>

</tr>

<tr>

<td>

_Describe the issue here_

</td>

<td>

_Write solution here_

</td>

</tr>

</table>

Other troubleshooting supports:

- _Link to FAQs_
- _Link to runbooks_
- _Link to other relevant support information_
### Reference

A reference page gives detailed descriptions of specific parts or features of the project. Users will look at this page while they are using the software, so the page should:

It should:

- Be organized into entries, like in a dictionary.
- Have a consistent structure, vocabulary, and tone.
- Give clear, concise information that fits the description in the overview.

It shouldn't:

- Give detailed instructions on how to use the software (put in the quick start).
- Describe the project as a whole (put in overview or conceptual guide).
- Describe the concepts or background behind the project (put in the conceptual guide).

#### Examples of good reference pages:

- []()
- []()
- []()

#### Sections:

##### Overview

_Summarize what this reference article is about._

##### The main section (change title)

_The way a reference article is put together depends on what kind of information you are writing about. The best formats are tables, lists, interactive object-schemas, etc. They allow entries to be shown in a structured way. Most of the time, a table is the best way to show reference information._

##### Code-generated documentation (change title )

_Add code-generated documentation here._

##### Reference articles

_Add links to reference articles here:_

- [Reference article 1](link)
- [Reference article 2](link)

#### APIs and libraries

_If the project is an API or a library, include these sections:_  

#### Overview

_See above._

#### Endpoints/library functions

For each endpoint plus method or library function include the following:

##### Resource description

Describe what the API call or library function is used for.

##### Endpoints and methods

Write the endpoint and method such as GET, POST, or DELETE. Or for a library, write the function and method.

##### Parameters

Describe the parameters that users can pass for the endpoint or method to influence the response.

##### Request examples

Include a sample request, showing some parameters configured.

##### Response examples and schema

Show a sample response from the request example above. Also provide a response schema that defines all possible elements in the response.

#### Reference articles

_Add links to reference articles here:_

- [Reference article 1](link)
- [Reference article 2](link)

### Examples

The examples page is for providing code samples for various common use cases.


This page is optional and shouldn't be added until you've completed these pages:

- the overview in the README,
- the "getting started" guide,
- and the reference page,

> **Note**: If you add this page, add it to `_sidebar.md` so users can find it.
### Background

This page is optional.

After completing these pages:

- the overview in the README,
- the "getting started" guide,
- and the reference page,

add a background page if needed.

The background page can include:

- Conceptual overviews that are too long for the overview page in the README,
- The bigger picture and perspective on the tool
- History of similar tools and how this tool is different
- Information about choices, alternatives, and possibilities
- Reasoning and justifications for why the tool is the way it is

> **Note**: If you add this page, add it to `_sidebar.md` so users can find it.

### Help and license

No need to update.

