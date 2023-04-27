
## Summary (Summarize the bug encountered concisely)
When attempting to create a new project in Gitlab, an error message is displayed, preventing the user from creating a new project.


## Steps to reproduce

 Log in to Gitlab.
Click on the "New Project" button.
Fill out the required fields such as "Project Name" and "Description".
Click on the "Create Project" button.

## Example Project

    The new project should be created successfully, and the user should be redirected to the project page.

## What is the current bug behavior?

     An error message is displayed, stating "Something went wrong while creating your project. Please try again later."

## What is the expected correct behavior?

The user is not able to access a non-existent project and an error message is displayed.
     
## Relevant logs and/or screenshots

      The issue is reproducible on different browsers.
The issue is not related to the network connectivity as other pages and functionalities of Gitlab are working fine.
This issue is affecting all users in our organization, and it's not limited to my account.
Attached below are the screenshots of the error message displayed while creating a new project.

[Insert attached screenshots]

## Possible fixes

It is recommended that the Gitlab development team investigate and fix this issue as soon as possible to prevent users from being unable to create new projects.

## Whom do you report/ Assign To/ Tags

 Gitlab, project page, bug, branch name, display
 
## Priority

    Minor
