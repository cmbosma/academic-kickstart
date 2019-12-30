---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "My Academic Workflow"
subtitle: ""
summary: ""
authors: ["Colin Bosma"]
tags: ["productivity", "workflow", "academia"]
categories: []
date: 2019-12-30T00:44:10-05:00
lastmod: 2019-12-30T00:44:10-05:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Photo by Jane Palash on Unsplash"
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

## My Academic Workflow

When I began working on my dissertation proposal, I realized I needed to tighten up my workflow. I found the internet is lacking in examples of streamlined academic workflows. The examples I have come across are either complicated by mentioning too many applications or they feature outdated applications. Below is my current academic workflow. I put this together to help me think through it myself and to provide a reference for others to use.

### Task Management

**Email: Gmail**

Gmail finally adopted many of the features I love about Inbox by Google. Now that these features have been added to Gmail, Inbox is going away. This is unfortunate as Inbox by Google did an amazing job of making your inbox into a to-do list. Although Gmail has some shortcomings, it gets the job done.

*Email tip*: I created a backup Gmail account for my personal and university email addresses. Every email I receive is forwarded to these backup accounts. That way if I accidentally delete and email, I can retrieve it. This will also be helpful for when my university email is deleted.

**Task manager: To-Do by Microsoft**

I used to use Wunderlist. However, it was purchased by Microsoft and the Wunderlist team is now developing MS To-Do. It's free and it has a great feature where you can review your tasks and add them to a "My Day" list. With every other task management program, you have to manually create a "My Day" list. The application works across devices and can be accessed online. MS To-Do does not currently have all of the features of Wunderlist, such as calendar syncing, but the development team updates the app with new features every few weeks.

[To-Do Website](http://todo.microsoft.com)

**Meetings: nvALT**

nvALT is a note-taking program that is shortcut-driven. You can quickly open the program, name the file, write text, and easily locate it later. Although the program could use a UI makeover, the developer makes sure the program is stable. The way I use this program for meetings is by using a file naming convention, such as mtgx-name-date. I sync my notes to one folder on Dropbox. Since I began using this program, I never spend more than a few seconds finding my meeting notes. Since it is in plain text, I can create, view, and edit my meeting notes using any mobile app that connects to Dropbox and edits plain text (there are tons of options). I currently use 1Writer on iOS and JotterPad on my Android phone. In addition, you can organize your notes using tags. Lastly, nvALT supports markdown (multimarkdown and github flavors). Taking notes in markdown makes for quickly formatting your notes as you write them for sharing. They are also more portable as they are written in plain text.

[nvALT](http://brettterpstra.com/projects/nvalt/)

### Research and Writing

**Capturing and processing existing knowledge: Mendeley, plain text**

I use Mendeley to manage my library of research articles and references. I used Mendeley because it is the most robust and flexible reference manager I have used.

My workflow in Mendeley involves syncing my library with folders on my computer. I organize the folders on my computer by broad topic areas (e.g., emotion theory, mindfulness, etc.) I also set up Mendeley to create a backup library of all of my articles sorted by author, date, and title. The in-text citation plug-in for Microsoft Word is decent enough. A little buggy with the newest version of MS Word for Mac, but it still makes for a more efficient workflow than writing reference lists manually.

Although Readcube is doing some cool stuff with their new Papers app, I don't like the idea of paying a subscription fee. F1000 Workspace is the only manager with a Google Docs in-text citation plug-in and might be worth trying for that reason alone. I do not use Zotero because the free space cap before paying for a subscription is pretty limited.

For annotating when I review literature, I use plain text notes. I do this to avoid needing to be dependent on a proprietary program. For example, if I save all of my notes in Mendeley, they will likely be lost if the company were to ever go under.

I am currently experimenting with saving my annotations in a spreadsheet, as I want them to be centralized and searchable.

I use a combination of plain text and Google Keep to take notes and save useful resources. Plain text notes allow me to think critically about what I am actually writing for my notes and give me the flexibility of editing my notes in pretty much any word-processing program. Google Keep is a nice application for organizing helpful online resources and general notes. It's organized using a labeling system, which is nice for items that fall under more than on category.

**Project Organization: Trello, Github**

I use Trello to organize research projects. The Kanban board design is useful for keeping track what needs to be done, what is in progress, and what has been done. I find that traditional to-do lists become too unwieldy for large projects. Using Trello breaks down each aspect of a project into smaller parts and can host to-do lists within each aspect or higher-order task. Although this can be accomplished in a robust to-do list application, Trello's platform already facilitates this kind of work flow and will save you time for that reason.

I use Github to host R and Python scripts that are useful for different types of projects and scripts that I have found to be helpful for my lab. For example, I have a repository with scripts my friend, Dr. Silas Tittes, helped me write to wrangle psychophysiology data into a tidy data set. In fact, I host my website on Github. I will not get into all of the merits of using Github in this post; however, I do highly recommend using Github as a platform for organizing and showcasing your code. If you plan on working in the industry completing data analyses, most jobs request a link to your Github account.


**Creating New Knowledge: Microsoft Word, Google Docs**

I, unfortunately, write my manuscripts in Microsoft Word and Google Docs (depending on the co-authors). Writing manuscripts using Markdown with pandoc or an application like Overleaf would be preferable for facilitating reproducibility and to prevent formatting headaches. However, manuscripts are rarely written alone and few journals have caught on to value of plain text. It is too bad, as researchers waste hours of time fiddling with APA formatting.

**Disseminating Knowledge: Powerpoint, RMarkdown, OSF**

I stick with Microsoft Powerpoint for creating slides and posters for presentations. Since Powerpoint is the most popular, I stick with it for sharing and collaboration.

Whenever possible, I use [R Markdown](https://rmarkdown.rstudio.com/) to document and display my analysis. R Markdown documents are part an extension of R Studio that integrate Markdown Syntax and R code (Python and SQL are supported). R Markdown is incredibly flexible as it can generate outputs in just about any format, such as PDFs, static web pages, MS Word, articles, slides, and even whole books.

Through my graduate career, I have developed an interest in open science and intend to write more on this topic in the future. The [Open Science Forum (OSF))](https://osf.io/), if you are not already familiar, is an organization that provides a platform for hosting research projects publicly, as well as pre-registrations. The OSF platform is great for hosting a project online for collaboration and to put a time stamp on your intellectual property. I am currently using OSF for my dissertation project [OSF URL](https://osf.io/wdsvj/). My dissertation is very methods heavy, so I intend to post protocols and R/Python scripts on OSF to share with others who are doing similar research.
