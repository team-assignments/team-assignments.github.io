## Summary

Team Assignments provides a visual representation of assignments that need to be completed by a group and allows members to claim them. Ideally, we implement a tracker/leaderboard allowing users to see who contributes the most. Not only does this allow the team leader to manage the busy itinerary, but provides incentive for members to be as productive as possible. 

## Intended users

> As a project manager who is managing multiple employees in multiple groups, I want to use the Team Assignments App so that I can ensure all our daily tasks are complete every day.

> As a single parent who isn't always home to enforce chores, I want to use the Team Assignments Apps leaderboard so that I can ensure my kids are equally sharing the work amongst one another.

## Client component

### Functionality

After downloading the application you are prompted to sign in using your google id, this will be used to identify the users moving forward. After signing in the application will load up the home screen. At the home screen the user can attempt to join a group id or build their own group. Assuming our user wants to build their own group, they will be automatically identified as the group leader (in our Intended User Examples the project manager or single parent would be the group leader). Once inside the group they will have three options: Add / Remove Tasks (visible only to the leader), View / Claim My Tasks, or View Team Overview. From there each option will perform as described above. 

### Persistent data

The option to save whatever tasks you have claimed while connected to the network will be useful. This way in the case that you become disconnected, you can still see them. 
    
### Device/external services

Access to google sign in will be important as that will create a uniform profile for each user in the application. 
    
## Server component

### Functionality

The server will perform the following functional aspects: 
* Registered Users
* Maintain the group
    * Verify the group. 
    * Verify who is registered in each group.
    * Verify what assignments are currently available for pickup. 
    * Confirm what assignments have already been picked up by individual member. 
    * Provide data on how much each member contributes. 
* Current Time (to identify when each cycle should end / reset)

### Persistent data

The server will keep a record of everything listed:
* Registered Users
* Group Data
    * Users registered to group.
    * Assignments the leader has assigned to group.
    * Specific assignments members have claimed.
    * Data involved with tracking how often each member contributes.
* Current Time (to identify when each cycle should end / reset)

### External services

N/A
    
## Stretch goals/possible enhancements 

TBD - None at this time, however open to suggestion from the build team. 
