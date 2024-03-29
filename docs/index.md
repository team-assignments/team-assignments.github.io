---
title: Summary
subtitle: "Lists assignments that need to be completed by a group, and allows members to claim them"
menu: Home
icon: home
order: 10
---

## Summary

Team assignments provides a convenient tracking system for tasks that need to be completed within a group. Team leaders are able to assign tasks to group members and approve task completion reports. This app allows for time optimization when a team has multiple simultaneous tasks in need of completion.

Once a user has created a group they are designated as the owner of that group. Group Owners are able to add other users to their groups. Group owners can also create tasks within their groups allowing all group members to see and work towards completion of those tasks.

The creation of the Team Assignments app allowed for the exploration of various interactions between client and service applications. There were complex relationships between the entities in the project that were interesting puzzles to investigate. As a team we felt that this app would have value in a wide range of applications, from Parents assigning chores for their children all the way up to multi-team corporations looking for a wy to optimize workflow.

## Intended Users
 Managers of teams responsible for completing several tasks each day.
> As a project manager who is managing multiple employees in multiple groups, I want to use the Team Assignments App so that I can ensure all our daily tasks are complete every day.

 Single parents who want to remove the headache in balancing chores between their children. 
> As a single parent who isn't always home to enforce chores, I want to use the Team Assignments Apps leaderboard so that I can ensure my kids are equally sharing the work amongst one another.

## Client Component

### Functionality


* User prompted to sign in using their Google ID.
  * Google ID will be used to distinguish users in the server. 
  * Google ID provides personality to the application. 
* Home screen allows users to build their own group. 
  * This user will be automatically identified as group leader. 
    * Group leader may exclusively Add / Remove Tasks.
    * Group leader otherwise shares the same capabilities as a group member. 
* Home screen also allows users to join an already established group. 
  * This user will be automatically identified as a group member. 
    * Group members may claim new tasks. 
    * Group members may view their already claimed tasks. 
* Inside a selected group, all users may view the Team Overview. 
  * List of all tasks and whom it was claimed by with timestamps. 
  * A leaderboard showcasing which member contributes the most or least.

### Persistent Data

The option to save whatever tasks you have claimed while connected to the network will be useful. This way in the case that you become disconnected, you can still see them. 
    
### Device/External Services

* Access to google sign in will be important as that will create a uniform profile for each user in the application.
  * Google Id will be used as authentication by the app.
  * In the even there is a short term service interruption with Google, access to the app could be interrupted for up to an hour.  
  * [Google Id API](https://developers.google.com/identity/sign-in/web/sign-in)
    
## Server Component

### Functionality

The server will perform the following functional aspects: 
* Registered Users
* Maintain the group
    * Verify the group. 
    * Verify who is registered in each group.
    * Verify what assignments are currently available for pickup. 
    * Confirm what assignments have already been picked up by individual member. 
    * Provide data on how much each member contributes.

### Persistent Data

The server will keep a record of everything listed:
* Registered Users
* Group Data
    * Users registered to group.
    * Assignments the leader has assigned to group.
    * Specific assignments members have claimed.
    * Data involved with tracking how often each member contributes.


### External Services
* Google Sign in Services

## [Overview](pdf/PDFOverview.pdf)


## Current State of Project

### Current State
* The Team Assignments application can name a Group and add it to the database.
* A Task can be added to the database.
* A Group and Task can be edited.
* A group and Task can be deleted.
* Dialogue popup to confirm delete.

### Unimplemented
* Created Tasks cannot be assigned to a User.
* Members cannot be assigned to a Group.
* Mark tasks as complete.
* Priority buttons (high, medium, low).

### Bugs
* When Group screen is fully populated, add button covers the bottom group delete icon.
* When editing a Task, pop keyboard covers description text box.  It requires re-opening to access.

### Aesthetic Plans
* UI design themes for color.

### Stretch Goals
* Fix bugs.
* Notifications when task is loaded.
* Comments on tasks.
* Volunteer to accept open Tasks.
* Adding custom Group icons.

## Team Roster

### Jonathan Rodrigues
jonrodrigues24@gmail.com
[GitHub](https://jonrodrigues24.github.io/)

### Dagoberto Garcia
[GitHub](https://github.com/wyldus)

### Marshall Eldridge
l2marshall@gmail.com
[GitHub](https://github.com/marshalleldridge)

### Lee Scroggins
lee_scroggins@yahoo.com
[GitHub](https://github.com/lee-scroggins) 