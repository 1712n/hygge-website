---
title: 'Project Boards'
date: 2022-03-21T12:00:00Z
menu:
  sidebar:
    parent: github
weight: -131
tags:
  - collaboration
  - tools
  - GitHub
  - leading
---

![Project Boards](/img/github/project-boards.png)

Project boards is a managing tool to improve visibility of the work progress. All GitHub projects are located on the organisational level. Use spreadsheets view (Beta Boards) for Team Projects and kanban view for Personal Projects.

# Project Team Boards 

The new Github Projects connect your planning directly to the work your teams are doing, and flexibly adapt to whatever your team needs at any point. Built like a spreadsheet, project tables give you a live canvas to filter, sort, and group issues and pull requests. You can use it, or the accompanying project board, along with custom fields to track team work across multiple repos, build and visualize content creation workflow, or even as a powerful sales CRM.

## Building the board

The project board can be assembled in multiple ways: 

* Adding existing issues and pull requests from a selected repository
* Adding new fields, showing, and hiding them on different views
    * Potential fields: due dates, text notes, issue types to enable better filtering
* Adding new views (don’t forget to save your changes, there is no autosave)
* Filter, group, and sort issues by using labels, repos, assignees, custom fields, and/or keywords

Project boards can also have extra information added in either the project board description and README file. You can,

* Describe the purpose of the project
* Include relevant external information and contact details for specific people
* Describe format of the board and different views 
* Use markdown to format README, include images and advanced formatting

### Project Migration

Classic project boards are able to be migrated to the beta format, however automation, activity, archive, and triage will not transfer over. Everything else such as issues, pull requests, and notes will transfer over along with the board’s title and description. In addition, there’s the option to keep or delete the original classic board..

### <span style="text-decoration:underline;">Tips:</span>

* Board views can be built from any custom field
* Manage board visibility and access in case there is sensitive information present
* Maintain a single source of truth 
    * Prevent information and issues from getting out of sync by keeping info in one location when possible (e.g. issue due dates) 
* Add project to quick access for convenience

## Working with the board

* The beta project board will automatically add any issues or pull requests in a selected repo. Views with multiple repositories will also automate depending on filters. 
* Side panel allows you to open issues within the board without leaving the page
* Issues can be created from within the board by creating issue drafts or converting from within the side panel
* The insights tab (top right corner), can visualize any fields within the board (e.g. issue status, assignee, labels, etc.)
* If automation is not an option, Issues can be added manually from within the repo or from another repo

### Filtering

You can filter by keyword or by any field by using the filter bar within the view. Much of this will autofill for you and you will be able to select any values within a field if it is present in the board. Find the filter button right under the view tabs and select it to start applying filters.

[Filtering](/img/github/project-filtering.webm)

* Filtering by keyword can be done in plain text 
* To exclude a query, add a “-” before the query 
* Separate issues from pull requests, drafts, or other states by using “is:”
    * Ex. “is: issue”, “is: merged”
* To filter by issue status, use “status:“ 
* Use “label:” to query specific labels
* Select either one or multiple repositories using “repo:”
* You can filter on the absence of something using “no:”
    * Ex. filter any issues without assignees by using “no:assignee”
* Multiple fields can be used at the same time when they’re separated by a space
    * Ex. To find open issues labeled stale that don’t have an assignee, use “label:stale status:open no:assignee”

### Insights

You can find the insights tab near the top right. Here, you can create new charts that visualize different fields that are in the project board. Different graph designs are provided, and you can optionally group by labels, repository, or status. A burn up/CFD chart will be provided automatically, which can also be edited to reflect different information.

[Charting](/img/github/project-charting.webm)

### Managing Access & Permissions

Under settings, there is a section to “Manage access” for the board. This presents the option of having a public or private board while also being able to set the base role. The base role will determine whether or not other Inca employees will be able to view the contents of the board, regardless of Public or Private visibility. Boards should be kept private since public boards can be viewed by anyone on the internet. 

<table>
  <tr>
   <td colspan="2" ><strong>Base Roles</strong>
   </td>
  </tr>
  <tr>
   <td>Admin
   </td>
   <td>Anyone can see, make changes to, and add new collaborators for the project
   </td>
  </tr>
  <tr>
   <td>Write <strong>(default setting)</strong>
   </td>
   <td>Anyone can see and make changes to the project
   </td>
  </tr>
  <tr>
   <td>Read
   </td>
   <td>Anyone can see the project
   </td>
  </tr>
  <tr>
   <td>No Access
   </td>
   <td>Inca employees can only see the project if it’s public. For an employee to have access, an admin must add them as either a team member or collaborator
   </td>
  </tr>
</table>

Collaborators can be individually added via username or team, their role can be determined before sending them an invite. Roles can also be changed among existing collaborators as well. 

**_If an item cannot be seen_** on the project board, that means that the viewer may not have access to the originating repository. To view the item, make sure the viewer has all permissions necessary.

[No access](/img/github/project-no-access.png)

## Automation

Marketplace provides [solutions](https://github.com/marketplace/actions/project-beta-automations) to automate issues triage. You can use actions that do that based on issue features:

* Repository
    * All issues from one repo go to one board 
* Specific labels
    * Issues in common repositories with a team label will go to that team’s board

Project boards also allow basic automation: change issue status once they are added, reopened, or closed

### Using workflows

Under the options for the board, navigate to workflows to see and toggle default workflows. You can automatically add new issues/pull requests, reopen closed items, and even close a pull request the moment it is merged. The layout of each workflow follows this pattern: 

[Workflows](/img/github/project-workflowd.png)

Custom workflows will be available in the future.

### Iterations

The iteration field can be used to associate items with specific repeating blocks of time. This can be done to visualize upcoming work, focus on one iteration via filter, and sort by iterations.

Upon creating the iteration field, three iterations will automatically be created. These iterations can be edited by name, date, or duration.

Breaks can also be added to iterations in case of a break from work. The duration of the break can be adjusted as well.

## Use cases

Beta project boards can be used in different ways depending on the nature of your work:

<span style="text-decoration:underline;">Tech Team Board</span>

* Add issues and pull requests from multiple repositories, Github allows linking up to 25 repositories 
* Use the status field instead of status label for easier filtering
* Rather than use priority label, manually order cards within board view
* Special columns or views for difficult issues, which can be discussed regularly
* Use repos to filter into sub-team views
* Track the workload of team members by grouping issues by assignee, or creating individual views
* Create new issues in different repositories within the project board by choosing the repo from the dropdown list
* Set and sort by due dates

<span style="text-decoration:underline;">Business Team Board</span>

* Powerful spreadsheet for high level overview of sales pipeline
* Separate views for different issue types and labels
    * relationship trackers vs. actionable tasks, active clients vs. leads, high priority vs. low priority
* Don’t lose any ideas with quick draft issues
* Create text notes for issues
* Update issues from within the board by using the side panel
* Generate insights to see progress of milestones and other issues
* Iteration fields can be used to schedule work or create a timeline 
* Use manual fields to create custom fields to filter for specific projects

## Personal Project Boards
Personal Boards are there to keep and organize your tasks. Each person is in charge of their own board with collaboration of team manager. You can adjust the layout - add your column for specific topics if needed, but don’t forget to prioritize - make sure to keep the clear distinction between high and low priority issues. You can discuss issues priority with your team lead/manager.

![image](/img/github/personal-project-board.png)

Issues are added manually to the personal project board, make sure you always transfer your issues. Once you are assigned to an issue, [add it to your project](https://docs.github.com/en/issues/organizing-your-work-with-project-boards/tracking-work-with-project-boards/adding-issues-and-pull-requests-to-a-project-board).

**Tip:** You can also add other issues, discussions, even project boards - anything you are interested in following directly from the project column. Simply copy and paste the links and add a new project card. Project cards support GitHub Markdown, feel free to create lists, hyperlinks, use bold/italics, etc.
___
### Useful links:

* [Github Documentation](https://docs.github.com/en/issues/trying-out-the-new-projects-experience/quickstart)
* [Github Blog](https://github.blog/?s=projects)
