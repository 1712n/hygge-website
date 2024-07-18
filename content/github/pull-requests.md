---
title: "Pull Requests"
authors: ["marina", "inga"]
date: 2022-03-10T12:00:00Z
menu:
  sidebar:
    parent: github
weight: -130
tags:
  - GitHub
  - iterations
  - collaboration
  - async
  - guru
cover:
  image: /img/tools/pull-request.png
---

The pinnacle of mastering the async process is communicating through pull requests.

**What is a pull request about?**

[Pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-branches) is a tool for programmers to sustainably collaborate on code. In a larger context, pull request are useful for suggesting changes policies, wikis, and iteratively collaborating on complex documents. When companies are growing and changing, their approach to work also does: benefits, tools, and best practices are evolving. Before making a change, it's always great to run your ideas by teammates and give others an opportunity to contribute to the final decision.

{{< youtube w3jLJU7DT5E >}}

**Other relevant terms**

- [Reviewers](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/requesting-a-pull-request-review)

Just like issues, GitHub's pull request have assignees. In addition to this, they have reviewers - people or teams whose review opinion is especially valuable.

- [Codeowners](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-code-owners)

The bigger your team, the more order you need to and manage knowledge ownership. One of the tools to keep the order is to document codeowners, who are in charge of their respective repository sections. The easiest way to manage codeowners is through [GitHub teams](https://docs.github.com/en/organizations/organizing-members-into-teams/about-teams). If you set a particular team as a codeowner for a repository or a part of it, all changes in the corresponding files and directories need to be approved by this team.

- [Branch](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-branches)

You can think of a branch as your own workspace. Make any changes there! You cannot break anything as long you stay in your branch. Merging your changes to the main branch is usually protected by the pull request process and involves a review from an experienced team member who makes sure the proposed changes don't break anything.

- [Commit](https://docs.github.com/en/pull-requests/committing-changes-to-your-project/creating-and-editing-commits/about-commits)

Recorded changes made to the files in the branch. Each commit is tracked to make versioning and reverting changes easier.

## Step-by-Step Guide

Let’s imagine you read a wiki and disagree with a policy or a process. Being able to change them is a part of Hygge Company [guiding principles](https://hygge.work/guiding-principles/): nothing is set in stone, and you can always propose and transparently discuss your changes through a pull request.

### Initiating your pull request

Create a branch. Do it directly from the issue or [from the code page.](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-and-deleting-branches-within-your-repository) Give your branch a distinctive name, and you can start making changes!

![Making a branch](/img/pull-requests/create-a-branch.gif)

From your branch, choose the file you want to change. Press `Commit Changes`

![Commit changes](/img/pull-requests/making-a-commit.gif)

When you finish with your changes, initiate a pull request. Briefly describe what you did and why.  Assigning reviewers is like pinging for opinion in the issue, however you wouldn't be able to merge your changes to the main branch until you get their approval.

![Open a pull request](/img/pull-requests/open-a-pull-request.gif)

### Working on a pull request

**Reviewer**

If you were assigned as a reviewer, [follow these steps.](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/reviewing-changes-in-pull-requests/reviewing-proposed-changes-in-a-pull-request)

![The merge is blocked](/img/pull-requests/changesarerequested.png)

If you are the ones who asked for the review, you might receive a request for changes. This means the merge is blocked, and you have something to fix. Select your branch and make the requested changes. After that, re-request review:
![Making a change](/img/pull-requests/making-change.gif)

Once you get the final approval, press the `Merge` button.

![Merge](/img/pull-requests/merge.gif)

You are all set! Your changes are synchronized with the main branch and have become the single source of truth.
