# Process Inbox

This app will be for processing the virtual inbox, and setting up the power hour json file

## Plan

* [ ] As a user, I want my virtual inbox file to be used
    * [ ] If there is a environment variable use it
    * [ ] Otherwise use the same directory as the location
    * [ ] Create the file if it doesn't exist
* [ ] As a user, I want my power hour file to be used
    * [ ] If there is a environment variable use it
    * [ ] Otherwise use the same directory as the location
    * [ ] Create the file if it doesn't exist
* [ ] As a user, I want to verify that the task names and descriptions in the inbox are correct
    * [ ] Get json from inbox
    * [ ] For each task in inbox
        * [ ] Display task name
        * [ ] Ask if task name is correct
        * [ ] If not, get new task name
        * [ ] Ask if task description is correct
        * [ ] If not, get new task description
* [ ] As a user, I want to be able to drop tasks that I don't want to keep
* [ ] As a user, I want to add additional information to each task from the virtual inbox
    * [ ] Company or personal
    * [ ] Deadline
    * [ ] Why
    * [ ] In
    * [ ] Available on
    * [ ] Repeats
    * [ ] Category
    * [ ] Importance
    * [ ] Points
* [ ] As a user, I want the tasks from the inbox to be added to my power hour list
* [ ] As a user, I want my power hour list completed items to be removed
    * [ ] Get list of power hour items that have been completed
    * [ ] If item is repeating, create new task and add it to the list
    * [ ] Put the completed item in the completed list
    * [ ] Mark that the item has been completed and when
* [ ] As a user, I want to set how much time to spend on each task category
    * [ ] Get categories from power hour list
    * [ ] If the times don't add up to 100, ask for percentages from user
* [ ] As a user, I want my power hour list to be sorted
    * [ ] Calculate how much effort each category has seen
    * [ ] Sort list by lowest percentage first
* [ ] As a user, I want to have my important items that must be done today in a separate list
* [ ] As a user, I want to have a backup of the last version of my inbox and power hour lists in case something goes horribly wrong
    * [ ] Inbox
    * [ ] Power hour