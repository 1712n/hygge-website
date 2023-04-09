---
title: "Github Project Boards: Begginer-friendly Guide to Self/Team Management"
authors: ["sofia"]
date: 2023-04-10T12:00:00Z
tags:
  - GitHub
  - async
  - iterations
  - guru
cover:
  image: /img/project-boards/dashboard.png
---

GitHub might be seen as a platform just for coding, but it also offers a broad range of [task tracking tools](https://hygge.work/github/project-boards/) that can benefit both personal and team projects. Hygge companies love using GitHub because it helps keeping everyone on the same page, managing tasks, and ensuring everyone meets their deadlines. Let's take a closer look at some examples of personal and team dashboards. 

The personal dashboard is super user-friendly and allows you to customize it with features that are perfect for your unique needs. In this context, Yana has optimized her dashboard to fit her workflow perfectly. 

![Example](/img/project-boards/yana-dash.png) 

- She's merged the concepts of priority and status, so she can easily prioritize her work based on each issue's status - as each issue moves through the different stages of development, the priority level is automatically adjusted to keep everything in sync with her predefined workflow. This makes it easy for Yana to focus on the most important tasks without having to update the priority levels manually.
- Yana has also created several fields that are integrated with her company repositories – this gives her a comprehensive overview of all the critical information she needs to stay informed about project developments. 
- Oh, and we almost forgot to mention - Yana's dashboard also has some seriously cool emojis for each column, as well as custom column names. They're a fun way to add a little personality to her dashboard and make it more enjoyable to use. For example, she calls her urgent tasks column "Hold My Coffee" to emphasize their importance and urgency.

Hygge companies also use GitHub to track team management, and Inca Digital’s Business Team dashboard is an excellent example of this. This dashboard serves as a comprehensive CRM tool that helps manage clients, projects, and product information:

![Example2](/img/project-boards/bsns.dash.png)

- Business Team members can organize clients and products by type and keep track of all client-related activities in one central location. The dashboard includes several fields, which allows filtering issues by goals, priorities, as well as product sales. This makes it easy for team members to quickly find the information they need and stay up-to-date on client projects and product developments. 
- The dashboard also allows for adding notes, products, and other relevant information to client profiles to have a complete overview of the customer's history with the company. This feature is crucial in managing client relationships and providing a personalized experience for each client. With all the relevant information in one place, team members can better understand the client's needs and provide better solutions to their problems.

Lastly, we’d like to share with you a really cool inspiration for a complex project dashboard. The open-source [Adobe 'RSP Component Milestones' dashboard](https://github.com/orgs/adobe/projects/19/views/18) is a great example of how GitHub can be used to manage complex projects and keep everyone on the same page:

![Example3](/img/project-boards/adobe.png)

- The dashboard is perfectly organized with a roadmap that displays the status of epics, milestones, and issues on the first page. It also includes all necessary labels, emojis, and filters, which allows for easy organization and filtering of issues based on their attributes. For instance, you can filter by`is:open` to show only open items, `assignee:@me` to see only items assigned to you or `last-updated:15days` - will show stale items, the opposite `-last-updated:15days` will show only items that were updated recently. Other useful [filters](https://docs.github.com/en/issues/planning-and-tracking-with-projects/customizing-views-in-your-project/filtering-projects) include grouping by repository, milestone, assignee, keyword, label, and more.
- The dashboard has well-developed fields with different columns and functionality, enabling contributors to easily track issues based on their current status and identify areas where they can contribute
- If you want to create a similar dashboard, why reinvent the wheel? You can [copy](https://docs.github.com/en/issues/planning-and-tracking-with-projects/creating-projects/copying-an-existing-project) any open-source project that fits your needs and customize it to make it your own.

To get started, check out the template below, which includes columns commonly found on the most functional open-source boards we've seen on GitHub:
To do/triage/new/inbox | Hold my coffee/Will be done today | In progress | Waiting for others/blocked/In review | Grooming/Need help | Tracking | Later/icebox | Delivered/done
 -- | --| -- | -- | -- | -- | -- | --
This item hasn't been started | Highest urgency/impact items that need to be closed asap (1 per team member) | Currently working on (5 per team member)| Dependent on something/somebody | Brainstorming is needed | High level efforts - milestone trackers, epics | Low priority/high effort stale items| Closed items 

When creating a new project on GitHub, you can choose from two templates: a team backlog template (Team Project) and a feature planning template (Feature). Both templates come equipped with pre-developed fields and emojis that you can use to organize your project. The team backlog template is designed for defining and planning your team's backlog, with a task board and custom fields for item priority and size. The feature planning template, on the other hand, is ideal for planning and tracking individual features across one-week iterations, with the added benefit of staying up-to-date on work in progress with linked pull requests. Utilizing these templates can be an excellent starting point for organizing your project and ensuring that all team members are on the same page. Keep in mind that GitHub is always releasing new features and adding cool functionality to their products. To get the most out of it keep an eye on their [blog](https://github.blog/changelog/label/projects/) and share your feedback in the [community](https://github.com/orgs/community/discussions/categories/issues).

All in all, GitHub offers a lot more than just code hosting and version control. With its robust task tracking tools and customizable dashboards, it's a versatile tool for personal and team project management. So why not give it a try and watch your productivity soar? 
