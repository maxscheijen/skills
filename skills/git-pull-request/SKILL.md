---
name: git-pull-request
description: Generate a pull request message
---

Look at the difference between the current git branch and the "main". Write a Pull Request description in the style of conventional commit.

The most important thing about pull request message is the **Why** behind a change. The engineer can see the **What** has changed in the diff, but the pull request message should reflect **Why** the change was made. Because usually, when reading Pull Request messages, isn’t not because something good happened.

The output should be formatted in markdown.