# About

This is an Omni Automation solitary plug-in for OmniFocus that calculates the total estimated duration of the selected tasks. Further details are provided below.

_Please note that all scripts on my GitHub account (or shared elsewhere) are works in progress. If you encounter any issues or have any suggestions please let me know--and do please make sure you backup your database before running scripts from a random amateur on the internet!_

## Known issues

Refer to ['issues'](https://github.com/ksalzke/estimate-total-time-omnifocus-plugin/issues) for known issues and planned changes/enhancements.

None so far! 🤞

# Installation & Set-Up

1. Download the [latest release](https://github.com/ksalzke/estimate-total-time-omnifocus-plugin/releases/latest).
2. Unzip the downloaded file.
3. Move the `.omnifocusjs` file to your OmniFocus plug-in library folder (or open it to install).

# Actions

## Estimate Total Time

This action totals the estimated duration of the selected items, and displays this information to the user. The user is given a warning if any of the items in the selection do not have an estimated duration, but is still provided with the estimate.

The total includes any of the following that are selected:

| Selection  | Amounts included in total                                                           |
| ---------- | :---------------------------------------------------------------------------------- |
| Task(s)    | The selected task(s)                                                                |
| Project(s) | Any remaining tasks belonging to the project (that do not have children themselves) |
| Tag(s)     | Any remaining tasks which have the selected tag(s)                                  |