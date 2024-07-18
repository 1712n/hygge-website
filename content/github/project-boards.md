---
title: "Project Boards"
authors: ["marina"]
date: 2024-07-18T12:00:00Z
menu:
  sidebar:
    parent: github
weight: -131
tags:
  - collaboration
  - tools
  - GitHub
  - leading
cover:
  image: /img/github/project-boards.png
---

![Project Boards](/img/github/project-boards.png)

Having a helicopter view of your workflow offers numerous advantages. While focusing on individual tasks is important, the ability to step back and see the bigger picture allows for better strategic planning, resource allocation, and overall project management. This broader perspective not only enhances team efficiency but also contributes to personal professional growth.

Projects are a great way to manage GitHub workflow from a high-level perspective. They allow for comprehensive project management and task tracking, making it easier to oversee progress and collaborate effectively.

#### Key Features of GitHub Projects

1. **Centralized Management**:

   - Create, update, comment on, and close all your issues from inside a single project instead of navigating through multiple repositories.
   - Keep your ideas for future tasks by creating draft issues and leaving notes in a custom text field.
   - [Bulk edit](https://github.blog/changelog/2023-04-06-github-issues-projects-april-6th-update/#t-rex-bulk-editing-in-tables) items in a table view by dragging a cell's contents.

2. **Task Management**:

   - Use a simple Kanban board for native task management by dragging and dropping tasks from one status (or any custom field) to another, which is ideal for personal boards.
   - Leverage [custom fields](https://docs.github.com/en/issues/planning-and-tracking-with-projects/understanding-fields) and advanced filtering, grouping, and slicing to manage a team’s work or a complex product launch.

3. **Tracking and Updates**:
   - Track deadlines on a [Roadmap](https://github.blog/changelog/2023-01-31-roadmap-in-projects-public-beta/) view by filling in due date custom fields.
   - Let your teammates always know the [status](https://github.blog/changelog/2024-01-18-github-issues-projects-project-status-updates-issues-side-panel/#green_circle-project-status-updates) of your project and the latest high-level updates.

### Quick Start Guide

1. [Create](https://docs.github.com/en/issues/planning-and-tracking-with-projects/learning-about-projects/quickstart-for-projects#creating-a-project) a Project by selecting one of GitHub’s or your organization’s templates that fits your use case.
2. [Add](https://docs.github.com/en/issues/planning-and-tracking-with-projects/managing-items-in-your-project/adding-items-to-your-project#searching-for-an-issue-or-pull-request) existing issues and PRs.
3. [Automate](https://docs.github.com/en/issues/planning-and-tracking-with-projects/automating-your-project/adding-items-automatically) the addition of future items from up to 5 repositories. If this limit is insufficient, consider creating issues directly in the project, or if you create them from a repository, assign a project manually.
4. [Customize](https://docs.github.com/en/issues/planning-and-tracking-with-projects/customizing-views-in-your-project/customizing-the-table-layout) your views if needed: hide or delete unnecessary fields, set up filters and grouping. Remember to save your updates to the view (a blue dot signifies unsaved changes)!
5. [Add](https://docs.github.com/en/issues/planning-and-tracking-with-projects/managing-your-project/managing-access-to-your-projects#managing-access-for-teams-and-individual-members-of-your-organization) collaborators with the necessary permission levels in settings.

### Useful Tips and Ideas

#### Auto-add Items to Project

Configure the auto-add workflow to automatically add new items as they are created or updated in a repository. You can filter these items based on labels, assignees, and reasons. Each workflow covers one repository, and currently, you can create up to 5 such workflows by duplicating them. Note that auto-add will not bulk-add items matching the filter when the workflow is enabled. You can also set up more advanced project automation with actions.

#### Make a Project Your Own

GitHub enables you to add custom fields to your project view. Besides the productivity classics (priority, status, size), your project can benefit from start dates, due dates, text notes, single select, or iteration fields. Don't be afraid to use creative names or add emojis – this personal touch can help with motivation.

Take a look at this example of a customized minimal board layout. It's straightforward and easy to maintain, as it merges the concepts of status and priority:

![Example](/img/project-boards/yana-dash.png)

If you are looking for a more complex example, huge open source projects like the [one from Adobe](https://github.com/orgs/adobe/projects/19/views/18) will provide you some inspiration. This dashboard is perfectly organized with a roadmap displaying the status of epics, milestones, and issues. While it offers vast workflow insights, it also requires significant maintenance.

![Example3](/img/project-boards/adobe.png)

#### Select What You See:

- Hide closed issues and PRs while keeping them for future reference: `-status:closed`
- Show items from specific repos or milestones: `repo:myrepo milestone:mymilestone`
- Create a view where each team member sees only items assigned to them: `assignee:@me reviewers:@me`
- Identify stale items: `last-updated:10days`
- Track issues that were recently updated: `-last-updated:5days`

For more filtering options, refer to [GitHub documentation](https://docs.github.com/en/issues/planning-and-tracking-with-projects/customizing-views-in-your-project/filtering-projects).
