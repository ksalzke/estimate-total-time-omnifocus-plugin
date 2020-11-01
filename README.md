# About

This is an Omni Automation solitary plug-in for OmniFocus that calculates the total estimated duration of the selected tasks. Further details are provided below.

_Please note that all scripts on my GitHub account (or shared elsewhere) are works in progress. If you encounter any issues or have any suggestions please let me know--and do please make sure you backup your database before running scripts from a random amateur on the internet!_

## Known issues

None so far! 🤞

# Installation & Set-Up

(For instructions on getting started with Omni Automation, see [here](https://kaitlinsalzke.com/how-to/how-to-add-a-omnijs-plug-in-to-omnifocus-and-assign-a-keyboard-shortcut/).)

1. Click on the green `Clone or download` button above to download a `.zip` file of the file in this GitHub repository.
2. Unzip the downloaded file.
3. Move the `.omnijs` file to your OmniFocus plug-in library folder.

# Actions

## Estimate Total Time

This action totals the estimated duration of the selected items, and displays this information to the user. The user is given a warning if any of the items in the selection do not have an estimated duration, but is still provided with the estimate.

The total includes any of the following that are selected:

| Selection  | Amounts included in total                                                           |
| ---------- | :---------------------------------------------------------------------------------- |
| Task(s)    | The selected task(s)                                                                |
| Project(s) | Any remaining tasks belonging to the project (that do not have children themselves) |
| Tag(s)     | Any remaining tasks which have the selected tag(s)                                  |