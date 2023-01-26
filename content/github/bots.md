---
title: 'Bots'
authors: ["asya"]
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
  - guru
---

![Bots](/img/github/bots.png)

It's always a good idea to automate managerial tasks. In your issues, you might encounter several bots that track GitHub's policies compliance.

1. [**Stale issue bot**](https://github.com/marketplace/actions/close-stale-issues-with-assignes) - pings an assignee if an issue is not updated. Beware: the stale bot can close issues if you ignore its messages.

**Tip:** Update your issues with any type of the progress. 

2. [**Required label bot**](https://github.com/marketplace/actions/pr-label-check-and-comment) - checks if the issue has all the needed labels. Pings an assignee asking to set labels in case of absence. Labels have functional values for you and others, they are essential for management and sorting.

**Tip:** If you need another team to help you with the issue - put their team label, that way, the manager will track these tasks directly from the team board.

3. **Sensitive bot** - detects sensitive information. 

Sensitive information types:
Sensitive clients names, trade secrets, etc

**Tip:**  Post sensitive data in dedicated repositories. If you need to mention it anywhere else - put a link to a related issue.

4. **[Reminder bot](https://github.com/marketplace/actions/issue-reminder)** for reminding you to check the issues in the following days/weeks/months.

 - Use `/remind` command in the issue comments. Do not set it up in the issue description or with capital letters ("/Remind").
  
 - Specify `what` you want to be reminded about and `when`. The bot will confirm your reminder by sending a message. Do not use "today" or "in 2 hours". It works only for the following days.

 - The bot will ping you in the issue when the day is due.