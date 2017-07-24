# Class 1: Introduction to the Tools and Fundamentals of Development

<a id="top"></a>
# Today's Plan: Week 1, Monday Lecture

**Agenda**

This first day of class is an all-day session with the students that is mostly lecture.

- [Kickoff!](#kickoff)
- [Academic Overview](#academic)
- [Tools: Terminal, Git, VS Code](#ug)
  - [Verify Student Toolbelts](#toolbelt)
- [Go over the assigned readings](#readings)

*Lunch Break*

- [Continuing going over the assigned readings](#readings)
- [Code demo to prep for lab](#code)
- [LAB](#lab)
  - Write code as outlined in the lab assignment

**Learning Objectives**

- Create a web page using organized, hierarchical HTML.
- Capture user input using the browser's `prompt` and `confirm` methods.
- Create an interactive web page by including JavaScript in a `<script>` tag.
- Create an interactive experience for a user using the browser's `alert` method.
- Create folders and files for a project using the command line.
- Navigate through folders, view and create files, and open folders and files in VS Code using the command line.
- Customize VS Code to check our JavaScript by installing ESLint.

## Readings

- HTML Chapter 1: "Structure"
- HTML Chapter 8: "Extra Markup"
- HTML Chapter 17: "HTML5 Layout"
- HTML Chapter 18: "Process & Design"
- JS Chatper 1: "The ABC of Programming"

<a id="kickoff"></a>
## Kickoff!

[Slides: 1-first-day-orientation.pdf](slides/1-first-day-orientation.pdf)

This is the welcome and introduction to Code Fellows. Students will meet the campus manager and learn about campus operations and policies.

[-top-](#top)

<a id="academic"></a>
## Academic Overview

[Slides: 2-academic-overview.pdf](slides/2-academic-overview.pdf)

The instructor will give an overview of the topics to be covered in this course and how those topics fit into the overall academic program at Code Fellows.

[-top-](#top)

<a id="toolbelt"></a>
## Verify Student Toolbelts

By doing a few quick tests and exercises, as detailed below, ensure that students have functionality of all of the core pieces of their development environment:
- VS Code: type `code` in the command line to verify that it opens properly. Command line tools may need to be installed.
- Chrome: how to open the console
- Git: enter `which git` in the command line to verify installation
- Directory structure: Have students set up a directory at ~/codefellows/201/ in which they will store their classwork. Go over directory structure in general; compare to GUI.

[-top-](#top)

<a id="ug"></a>
## Unix & Git

[Slides: 3-unix.pdf](slides/3-unix.pdf)
[Slides: 4-git-intro.pdf](slides/4-git-intro.pdf)

Slides to introduce students to core concepts of file management from the command line and the fundamentals of Git and GitHub.

[-top-](#top)
<!--
<a id="linter"></a>
## Set up a JavaScript linter
Have students go to the command line and `apm install linter-eslint`. Have them open a new tab in their terminal ( which also shows them that this is something they can do!) and cd to their home directory. Then `atom .eslintrc` in their home directory and copypasta the contents of the .eslintrc file (send it through the class Slack channel, which is a nice verification of that functionality). Then go into the package settings in Atom and make sure that it is looking for that .eslintrc

[-top-](#top)-->

<a id="readings"></a>
## Go over the assigned readings

**HTML Chapter 1: "Structure"**

- p.15: How pages use structure
- p.20: HTML describes the structure of pages
- pp.21-22: Tags as containers (great graphic page)
- p.24: Tags
- p.26: Attributes
- p.33: Code in a CMS

**HTML Chapter 8: "Extra Markup"**

- p.179: Evolution of HTML
- p.181: Doctypes
- p.182: Comments
- p.183: Class & id attributes
- p.185: Block vs. inline
- p.191: Meta tags
- p.193: Escape characters
- p.194: Special characters

**HTML Chapter 17: "HTML5 Layout"**

- Semantic HTML
- Traditional layout vs. HTML5
- Header, footer, nav, aside, section, figure, div

**HTML Chapter 18: "Process & Design"**

- Things to think about when starting a project
  - Who is the site for?
  - User stories
  - Sitemaps
  - Wireframes
- Visual hierarchy, grouping, navigation

**JS Chatper 1: "The ABC of Programming"**

- p.16 	Designing a script
- p.28 	Objects & properties
- p.30 	Events
- p.36 	Browsers & document object
- p.40 	How a browser sees a web page
- p.44 	How HTML, CSS, JS work together			
- p.45 	Progressive enhancement
- p.51 	JavaScript runs where it is found in the HTML

**We also need to discuss the role of *pseudocode*, which is something the Duckett text does not cover very well.

[-top-](#top)

<a id="code"></a>
## Live code

This code demo is to help students be ready to complete the first assignment and also to show off some functionality of the REPL and Chrome Developer Tools. This demo should also reveal any lingering issues with student computer setups.

[-top-](#top)