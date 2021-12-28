# GPU manager

## Description
This software will be responsible for managing the GPU's activities and tasks, providing users with control over certain settings to improve quality, maintain stability,
and offer updates/downgrades when needed, offer information over the current installed software, offer support, and make sure everything is running smoothly.

## Stakeholders
GPU manufacturers, GPU piece owners, Game devs.

## Near vision for the first two sprints
We should have the bare minimum of the software running and testable by this point, which includes a system to verify your GPU drivers version, and a system to allow you to update your drivers if they're outdated.

## Convention for story points
Using powers of 2 convention
For our easiest story we are giving it 1 story point (Driver verification)
For our hardest story we are giving it 16 story points (Special Capture)

## Product backlog order
Items are ordered by their necessity.
From items that provide critical information to make sure the system is running correctly, 
to more quality of life items that help ease the access and provide more features that could be considered luxury.

## Estimated story points per sprint
Minimum 6, Maximum 16

## Workflow
### Rules
Issues can be dragged from (IN-PROGRESS) to (TESTING) by those who are assigned to them only.
Then from (TESTING) to any other state by the assigned scrum member, and so on.
### Rationale
This workflow was designed to accomodate the test-dependent programming style where software is designed to be easily tested to check for faults,
if the software passes the set tests, it is accepted as a finished software, if not then it is re-assessed to see what needs to be changed
and whether or not it can be done in the same sprint.
