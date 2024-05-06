
## Summary (Summarize the bug encountered concisely)

The text for creating a new blank project contains a typo.

## Steps to reproduce     

Go to the Login URL: https://gitlab.com/users/sign_in
Log In With Username and Password
Go to the New Project URL: https://gitlab.com/projects/new#

## What is the current bug behavior?

The text displayed for creating a new blank project is "Create black project"

## What is the expected correct behavior?

The text for creating a new blank project should be "Create blank project"
     
## Relevant logs and/or screenshots

![alt text](Bug_Screenshot.png)
![alt text](Bug_Project_create_blank.png)

## Possible fixes

Locate the HTML element in the HTML file responsible for displaying the incorrect text. Edit the text within this element to correct the typo from "black" to "blank"

## Whom do you report/ Assign To/ Tags

Report: Test Lead
Assign: Development Team
Tags: UI, Text, Typo

## Priority

Medium Priority
      
