# IT115 Group 3 Class Project @ NSC

## Project Overview
[![GitHub Super-Linter](https://github.com/twopercentjazz/It115-Group-3-Project/workflows/Lint%20Code%20Base/badge.svg)](https://github.com/marketplace/actions/super-linter)

We will use a fork of [websitedemo](https://github.com/rbunge-nsc/websitedemo) as
the seed code for our project.

Our project is a site that pulls together resources for anyone who wants to learn
git and use GitHub. We used HTML, CSS, PlantUML, Visual Studio Code, gitk, GitHub,
SuperLinter and AWS. All of these technologies are free to use, except for AWS,
where we had access to a free student account through our school.

We wanted to share our journey as we learned different techniques and software
in order to become proficient in git and shared our work through GitHub. Our
site includes key items that we learned and tips for starting your own journey.

One challenge we faced was using a SuperLinter status badge at the top of the
README file to catch coding errors during pull requests. We had introduced known
errors but the linter was not catching them. We realized that super-linter.yml
had been added after the bugs were introduced. We did a fix involving the setting:
VALIDATE_ALL_CODEBASE. It had defaulted to false, meaning it would only check the
code after it was installed. We needed it to check all of the code, so we changed
it to be true.

## License
>Please see our license included in GitHub.

## Table of Contents 

- [x] **LICENSE**
- [x] **README.md**
- [x] **CONTRIBUTING.md**
- [x] **Project Page** (GitHub Pages site)
- [x] **Bug Reports Project Board**
- [x] **Super-linter Workflow**
- [ ] **All Project Pages and Assets** (Our Production Site)
- [x] **Launch Our Site** (Deploy code to server)
- [ ] **Group Project Presentation**

## How to install and run the project
[Coming Soon]

## Credits
Group members names and main role
>Amna [Testing]
>Chris [Deployment]
>Joshua [GitHub Repo Owner]
>Julyah [Project Management]

## Project Requirements Questions

>* How did you change Web Site Demo?
>* How did your group collaborate and manage the project?
>* What roles did each team member play?
>* Describe your process for testing.
>* Describe your process for bug tracking.
>* How did you update and fix code?
>* What web server are you using to host your project?
>* Describe the process for configuring your web server.
>* How did you deploy code to your server?
>* Provide a URL so others in the class can playtest your project.

## **Individual Project Report**

>* Your group's Web Site Demo version name
>* Link to your group's repository
>* Link to your group's production site
>* Group members — list names
>* What was your main role in the development of your group's version of the Web Site Demo site?
>* If you have a similar team project in the future (like a capstone project),
>  what would you do similarly to what you did on this project?
>* What things would you do differently for future group projects?
>* List three main things you learned by doing this project.

### Learn More about this project at our GitHub Pages site
[Live Site](http://it115-group3.s3-website-us-west-2.amazonaws.com/docs/index.html)

## Bug Reports
Report bugs here: [Bug Board](https://github.com/users/firejewels/projects/7/views/1)
