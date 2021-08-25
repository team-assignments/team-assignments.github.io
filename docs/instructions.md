---
title: Instructions
subtitle: "Instruction to build the Application"
menu: Instructions
order: 70
---

## Build Instructions

In order to use the App follow these instructions
* Follow this [link](https://github.com/team-assignments/team-assignments-android) to the github project page.
* Click the CODE button and with your preferred method of authorization (SSH recommended) selected click the clipboard icon to copy the link.
* From the welcome menu of IntelliJ click the "get from vcs" button and paste the link you copied from github into the URL field.
* You MUST create a properties file on your local machine with the following fields
    * base_url = http://10.0.2.2:8099/team-assignments/
    * client_id =
        * A client Id must be provided from the Google Cloud Platform.
    * You must then navigate to the default config section of the build.gradle app file and edit the following fields to point at your local properties file.
        * buildConfigField "String", "CLIENT_ID",
        * buildConfigField "String", "BASE_URL",
    * You can now run the app in your preferred emulator.

## App Instructions

### Logging in and Home Screen

When you start the app you will be met with a Google sign in button which is used to create your user profile, Sign in with your Google account.

You will then be presented with a home screen which displays any groups you are associated with.

You can click any groups populated in the home screen and see a list of tasks that have been posted for that group.

### Management Screen

If you swipe towards the left on your screen or simply click the management tab at the top of the screen you will navigate to the management screen of the app.

From this screen you can create a new group by clicking the ADD GROUP button. Any groups created here will be displayed on the home screen in a scrolling list.

There is a spinner at the top of the screen that will display any groups you have created. You may perform administrative operations on the selected group via the buttons on this screen.

Clicking the ADD TASK button will present a editing tool which allows you to set a title, due date, and task description for your task. Once created it will be visible by clicking on the group it was assigned to in the home screen of the app.