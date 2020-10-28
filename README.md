# Kottans Front-End Course
My participating in the *[course](https://github.com/kottans/frontend/blob/master/contents.md#stage-0-self-study)*  
#### General   
- [x] 0 - Git Basics  
- [x] 1 - Linux CLI and Networking  
- [x] 2 - VCS (hello gitty), Github and Collaboration
#### Front-End Basics  
- [x] 3 - Intro to HTML & CSS
- [x] 4 - Responsive Web Design
- [ ] 5 - HTML & CSS Practice
- [ ] 6 - JavaScript Basics
- [ ] 7 - Document Object Model - practice
## 0. Git Basics 
 Completing the task, I've learned basics of Git. Since this tool is new for me, I was really surprised by incredible important possibilities of version control.   
 Now, using command line, I can initialize repositories, add files on staging index, make commits, point tags; create branches, developing safely and isolated, merge branches together; undo or modify changes that have been saved to the repo.
***
![completed version control course](https://github.com/eve5ince/kottans-frontend/blob/main/task_git_basics/udacity_vc.png)
![finished learn git branching main](https://github.com/eve5ince/kottans-frontend/blob/main/task_git_basics/learn_git_branching1.png)
![finished learn git branching remote](https://github.com/eve5ince/kottans-frontend/blob/main/task_git_basics/learn_git_branching2.png)
## 1. Linux CLI and Networking
#### Linux CLI   
  As I am newbie to Linux, finishing this chapter was actually valuable. The command line seems very powerful tool, especially with git, and I am glad to know how to perform basic tasks with it.
![completed linux survival proof](https://github.com/eve5ince/kottans-frontend/blob/main/task_linux_cli/linux_survival.png)  
  Some commands to remember:
* cp -r, rm -r - copy/remove files on trees 
* chmod(ugo-rwx) - change file permission 
* finger - show user info
* ~ - home directory
* df - show free disk space
* ps - show system processes
* kill, kill -9
* grep - find words in text
* man - manual  
#### Networking
  Reading articles about Networking, I got known some of HTTP's basics: request verbs, status codes, request/response headers, using HTTP in web frameworks; also HTTP connections, connection handling, authentication, HTTPS, and cache processing.   
## 2. Git Collaboration   
In this task I've learned how to work with remote repositories: how to push or get changes from remote repos; forking a repository; looking in CONTRIBUTING.md file and project issues, before start doing any work; working on "topic" branches; creating pull requests; squashing commits with rebase command, and the importance of communicating clearly and frequently with other stakeholders in the project.
***
![completed git collaboration course](https://github.com/eve5ince/kottans-frontend/blob/main/task_git_collaboration/git_collaboration.png)
![completed learn git branching](https://github.com/eve5ince/kottans-frontend/blob/main/task_git_collaboration/learn_git_branching1.png)
![completed learn git branching](https://github.com/eve5ince/kottans-frontend/blob/main/task_git_collaboration/learn_git_branching2.png)  
## 3. Intro to HTML and CSS
Mostly I have refreshed HTML/CSS knowledges; some were new for me, such as ```!important``` flag, which overrides any style; CSS Grid properties: ```grid-area```(a shorthand which specifies an item's location and size), ```grid-template-areas```(allows the naming of sections of a webpage), ```grid-auto-flow```(specifies whether implicity-added elements should be added as rows or columns within a grid), ```grid-auto-rows```(implicitly-added rows or columns occur when there are more grid items than cells available); also I find CSS ```transition``` pretty cool tool, which allows you to provide visual feedback to users.
***
![completed intro to HTML and CSS](https://github.com/eve5ince/kottans-frontend/blob/main/task_html_css_intro/completed_learnHTML.png)
![finished HTML course](https://github.com/eve5ince/kottans-frontend/blob/main/task_html_css_intro/finished_learnHTML.png)
![finished CSS course](https://github.com/eve5ince/kottans-frontend/blob/main/task_html_css_intro/finished_learnCSS.png)
## 4. Responsive Web Design 
By finishing this task, I've learned some basic concepts of repsonsive design , such as:
* always set ``` <meta name="viewport" content="width=device-width, initial-scale=1.0"> ```
* use **responsive design mode** in dev tools
* set **relative** units in specifying widths for elements(preventing from overflow) 
* set tap targets size for **48x48** px
* start responsive design for *smaller* viewport, *prioritizing* content for users
* use *media queries* to control styles for different viewports
* use flexbox/grid for creating responsive layouts
* use the ``` picture ``` element for responsive images (provides multiple versions of an image based on different characteristics, like device size, device resolution, orientation etc)
* ideal measure for the lenght of a line is **65 cpl** > use *measures* as a factor for picking **breakpoints**
* add minor breakpoints too   
***
There are 4 evolving patterns for responsive design: 
1. **Column Drop** - the simplest one, at narrowest viewport, each element simply stacks vertically, one on top of the other  
2. **Mostly Fluid** - very similiar to Column Drop, but with more columns fitting in different ways; at narrowest is the same, at its widest margins are added on the left and right, instead of expanding  
3. **Layout Shifter** - the most responsive layout, using flex ``` order ``` attribute to move content, instead of reflowing or dropping columns  
4. **Off Canvas** - at smaller viewport places less frequetly using content off screen, showing it when user taps on burger icon(for eg); on wider viewport the content is shown by default  
***
Creating responsive *tables*, there are 3 techniques to decide: 
1. *Hidden Columns* - using ``` display:none; ```, hides columns based on their importance, as the viewports size gets smaller  
2. *No more tables* - positioning table's content way off screen  
3. *Contained tables* - wrapped in a div table with *scroll*; set ``` width:100%;``` and ``` overflow-x: auto; ``` 
***
![Finished course of responsive web design ss](https://github.com/eve5ince/kottans-frontend/blob/main/task_responsive_web_design/finished_responsive_design.png)
![Finished flexbox Froggy ss](https://github.com/eve5ince/kottans-frontend/blob/main/task_responsive_web_design/flexbox_froggy.png)
