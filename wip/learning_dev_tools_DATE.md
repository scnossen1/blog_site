# Learning Dev Tools as an IT Risk and Controls Professional - DATE

Over the last ~5 years as an IT Auditor and Risk and Controls specialist, I have accumulated a functional understanding of the tools and processes in software development. I'm sure this sounds familiar to anyone who has undergone an IT audit or had to work with an IT auditor. The irony is not lost on me that the person assessing a given subject only understands the subject at a surface level. Recently though I have wanted to expand my understanding and writing this blog has given me a great opportunity to learn. I hope software devs can have a laugh at my ignorance and fellow armchair experts can learn something with me.

I was only recently taught I should be using a virtual environment per each Python script/program instead of just raw dogging everything globally. Great shame was brought to me, my family, and department. I must atone.

For my example I will be using GitHub, Visual Studio Code, and Git.

---

## Terminology and Tool Definitions

- Source Code Management Platform: Somewhere code can be stored and changes can be tracked. GitHub, Azure Dev Ops, GitLab, and Bitbucket are popular examples.
- Integrated Development Environment: 
- Distributed Version Control System: 
- Repository (Repo):
- Branch: 

---

## GitHub

I will not be going into depth on GitHub, but I will cover what I did to get this up and running. To start you will need a GitHub account, then create a new repo. Within the settings of that repo, we will need to copy down some credentials, GitHub username and personel access token (PAT), to be used with VSCode later. OAuth is also an option, but I found it useful to understand PATs and how permissions can be managed through them. A PAT functioned very simmilar to API tokens for me, if that helps add context.

---

## Visual Studio Code (VSCode)

Just install VSCode. Git and source control functionality are availible out of the box. Most of what's done in VSCode is during the integration step I go over later on.

---

## Git

Git is a standalone open-source software and must be installed. This was a little confusing to me since it's used synonymously in software development to describe source control. I will be using Git CLI, but a GUI version does exist.

---

## Integrating All 3 Tools

## Funny things I learned about development:

- Git is really the only version control system anyone seriously uses. Some Redditors tried to say otherwise, but were buried in downvotes. [Fun fact](https://www.jonesipl.com/article/genericide-the-case-of-kerosene/) about how Kerosene lost the trademark on its brand name of paraffin oil. (Genericide)
- It feels really silly to create and approve my own pull request after auditing so many change processes that require segregation of duties.
- Devs are bullied by other devs for using Git CLI.
- When you clone a repo, it creates a folder for that repo automatically even though you already created a folder with the same name, and it's very confusing when you didn't realize you were in a nested folder and that's why nothing was working.
- I really don't understand how authentication with VSCode > Git > GitHub works. I just kept running commands until I got an OAuth prompt TBH.
- GitHub PagesTM is nice for static hosting. Use my [referral link](https://www.reddit.com/r/Showerthoughts/comments/p0suzc/when_told_that_gullible_was_written_on_the/) for a 75% discount on your first month.

---

Was this successful? Will my autocratic manager appreciate this post? Will I finally meet the minimum requirements to be considered a mammal capable of higher thought by developers? Yes? Never. Hopefully.