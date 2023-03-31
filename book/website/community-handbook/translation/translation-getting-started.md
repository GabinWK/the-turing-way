(ch-translation-getting-started)=

# Getting Started in Translating _The Turing Way_

Our current Translation Management System is Crowdin.
Crowdin is integrated to a GitHub fork of The Turing Way in [a temporary GitHub organisation](https://github.com/TWTranslation).
Every time the repository is updated, Crowdin starts an automatic translation.
These translations need to be reviewed and accepted before being considered final.

```{figure} ../../figures/workflow-crowdin.png
---
name: create-account-crowdin
width: 80%
alt: The workflow used in Crowdin.
---
The Translation workflow, which relies on a fork of the Turing Way repository inside the [TWTranslation](https://github.com/TWTranslation) GitHub Organisation account.
```

All translations are stored in a fork for the Turing Way repository inside [TWTranslation](https://github.com/TWTranslation) GitHub Organisation account.
This fork is updated automatically and any new content is added to Crowdin automatically.
New translated and approved files will generate a PR and be added to the repository as shown in the figure above.

## Join the Translation Team in Crowdin

- **Create an account in Crowdin** through [this link](https://accounts.crowdin.com/register?domain=turingway&continue=%2Fturing-way).

```{figure} ../../figures/Create-accunt-Crowdin.gif
---
name: create-account-crowdin_
width: 90%
alt: Sign up in crowdin or log in before you start the translation. You can also log in using your GitHub or Google account.
---
```

You can either create an account in Crowdin by filling the requested details or through sign up using your GitHub, Facebook, Twitter, GitLab or Google account.

```{warning}
_The Turing Way_ is using [Crowdin Enterprise](https://crowdin.com/enterprise), which is not connected to [crowdin.com](https://crowdin.com/) and needs a separate account.
If you have an account in [crowdin.com](https://crowdin.com/), you will still need to sign up again in [Crowdin Enterprise](https://crowdin.com/enterprise) using [this link](https://accounts.crowdin.com/register?domain=turingway&continue=%2Fturing-way).  
```


- **Read the landing page of _The Turing Way_** and README to understand the vision and mission of _The Turing Way_ Book.

```{figure} ../../figures/README.gif
---
name: explore-readme-crowdin
width: 90%
alt: Crowdsourcing page in Crowdin which has three tabs, one showing the languages, the 2nd one showing the names of the managers and the third one showing the README file.
---
```

- **Review the Translation Guidelines.**
  - What should *not* be translated for consistency and structural integrity.
  - It is essential to harmonise and standardise translations.
  Make sure you read them before you start translating for the first time.
  - Each language has the Translation Priorities list, which you can find in the README file. 
  Choose one of the high priority files.

- **Choose the language you want to contribute to.** We have currently 4 languages with active contributors, which are Spanish, Arabic, Portuguese and Chinese.   

```{admonition} Add New Language
:class: tip
If your language is not in the list, please feel free to contact one of the managers and ask for new language through Crowdin or Slack.
```

```{figure} ../../figures/add-language-crowdin.gif
---
name: add-language
width: 90%
alt: You can add a new language by contacting one of the managers.
---
```

- **Start Translating chapters from the translation priorities list.**
  - You can view the translation priorities list in the task tab in Crowdin, they are also marked with a red arrow. The same list is copied below:
    - **Urgent** (Welcome, afterword)
    - **Priority +++** (Overview of the guide of reproducible research, open research)
    - **Priority ++** (Research data Management, Research Compendia, Licensing)
    - **Priority +** (Version Control, Overview of Project Design, Creating Project Repositories)
    - **Intermediate** (Overview of the Guide for Communication, Making Research Objects Citable, Communications in Open Source Projects, Getting Started With GitHub, Research Infrastructure Roles, Introduction to Research Ethics)

    - In order to navigate to the tasks tab inside crowdin, you need to click in "Go to the Console" at the top right and navigate back to _The Turing Way_ project which will direct you to a similar interface but with additional tabs on the left, one of the these is the task tab.
    In the Tasks, we assign tasks to get files translated or proofread by the community or set the due dates and receive notifications about the changes and updates in tasks.

```{figure} ../../figures/tasks-crowdin.gif
---
name: tasks-crowdin
width: 90%
alt: You can add a new task to Crowdin by clicking on the console at the top and then navigating to the task tab at the side.
---
```

- Once you decide which file you will work on, you can type its name in the search bar and click on it. 
  This will direct you to Crowdin Editor, you will learn more about it in the next chapter.

```{admonition} Top Tip
:class: tip
The arrow icon next to the high priority files are always pointing up and coloured red!  
```

```{figure} ../../figures/choose-file-crowdin.gif
---
name: choose-file-crowdin
width: 90%
alt: Use the search box to look into the file that you would like to start translating.
---
```  

You are now all set-up to start translating the Turing Way. 
In the next chapter, you will learn how to take advantage of the Crowdin editor to translate strings, proofread or add comments.