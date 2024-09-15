---
name: User Story
about: This template is for user stories
title: ''
labels: ''
assignees: ''

---

+
-
Play


00:00
02:57
Mute

Settings
Hands-On Lab: Create an Issue Template in GitHub
Estimated time needed: 10 minutes

In this lab, you will create an issue template in GitHub that will help you to write well-formatted user stories in Kanban board.

Note:

If you chose to use GitHub Projects for your Kanban board, continue using it for all the labs. Alternatively, you can use Zenhub to create a Kanban board for your labs.
The process of creating an issue template will be the same whether we use GitHub Kanban or Zenhub Kanban, since the issue template will be created in the GitHub Repository only.
After completing this lab, you will be able to:

Create an issue template in GitHub that contains the information required for writing good user stories.
Exercise 1: Create an issue template in GitHub
In this exercise, you will create an issue template in GitHub. This only needs to be done once for each new repository that you create.

Go to GitHub.com and select the lab-agile-planning repository that you created in Lab 1.
github home.

From the repository page, select Settings.
select settings

Scroll down to the Features section and select Set up templates.
select setup templates

From the dropdown list labeled Add template (1), select Custom template (2).
select custom template

Next to the Custom issue template entry, press the Preview and edit button.
select preview and edit

Select the pencil icon to edit the template.
select pencil

Copy the following markdown for the story template content:

1
2
3
4
5
6
7
8
9
10
11
12
13
14
 **As a** [role]  
 **I need** [function]  
 **So that** [benefit]  
   
 ### Details and Assumptions
 * [document what you know]
   
 ### Acceptance Criteria  
   
 ```gherkin
 Given [some context]
 When [certain action is taken]
 Then [the outcome of action is observed]
 ```
