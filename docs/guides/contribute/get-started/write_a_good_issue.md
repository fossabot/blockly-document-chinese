# Writing a Good Issue

All great projects are built on user feedback. Blockly uses GitHub issues to track feedback. This page details how to write an issue that is easy for a developer to read and respond to, which makes it more likely that your bug report/feature request will be addressed!

## Pre-work

### Got Questions?

We love hearing your questions! But GitHub issues aren't a very good medium for them. If you have a question, head over to our [developer forum](https://groups.google.com/forum/#!forum/blockly) instead. If you ask your question there you're more likely to get a timely and thorough response because it is filled with developers that have been using Blockly for years!

### Check for Duplicates

Before you go about writing _any_ type of issue, it is always good to see if a matching one already exists. If one does, this saves you the effort of having to write it up yourself! So before you get started writing, do some searches for duplicates or related issues.

- Search in [blockly-samples](https://github.com/google/blockly-samples/issues?q=is%3Aissue+mySearchHere)
- Search in [Blockly core](https://github.com/google/blockly/issues?q=is%3Aissue+mySearchHere)
- Search the [forum](https://groups.google.com/g/blockly/search?q=mySearchHere)

If you find a matching issue, give it a thumbs up or add a comment detailing your thoughts. This is especially important for bug reports and feature requests. If developers see that an issue is getting a lot of attention, it is more likely to get worked on!

## Report a Bug

So you think you've discovered a bug? Great! We love hearing bug reports because we want this project to be as stable as possible. Here are some steps you can follow to help your bug get fixed.

1.  [Check for Duplicates](/guides/contribute/get-started/write_a_good_issue#check-for-duplicates)
2.  [Gather Evidence](/guides/contribute/get-started/write_a_good_issue#gather-evidence)
3.  [Locate the Issue](/guides/contribute/get-started/write_a_good_issue#locate-the-issue)
4.  [Solidify your Reproduction](/guides/contribute/get-started/write_a_good_issue#reproduce-it)
5.  [Suggest a Cause](/guides/contribute/get-started/write_a_good_issue#suggest-a-cause)
6.  [Write your Issue!](/guides/contribute/get-started/write_a_good_issue#write-the-issue)

### Gather Evidence

Generally, the more information your bug has, the better. Here are a few things you might want to provide:

- **Screenshots or Gifs** can be really helpful if a bug causes a visual problem.
- **Sample Code** is useful if a bug only affects certain kinds of blocks, or configurations of workspaces.
- **A Hosted Site** is great if you're having trouble reproducing your bug outside your specific environment.

### Locate the Issue

Between the core library, the plugins, the examples, and the codelabs, we've got a lot of Blockly code. Help us out by telling us exactly where the issue is.

If the problem is in core, which component? For instance, it could be an issue with the toolbox, or with the zoom controls, or with the library blocks. Be as specific as possible.

If the problem is in blockly-samples, figure out which plugin, codelab, or example it's in. If you find the same bug in multiple places, tell us that too.

### Solidify your Reproduction

A bug is only fixable if it is reproducible, so before you submit an issue, make sure you have a solid way of getting your bug to occur.

You should end up with a numbered list of steps that tell a developer how to reproduce the bug. For example:

1.  Open X codelab.
2.  Go to Y page.
3.  Run Z example code.
4.  Observe the bad behavior, which looks like W.

If your issue is in Blockly core, try to reproduce it in the [playground](https://blockly-demo.appspot.com/static/tests/playground.html).

### Suggest a Cause

If you think you know why the bug is happening, include that information as well. Again, be as specific as possible.

### Write your Issue!

The time has come to write your bug report. Select your repository:

- [Blockly core](https://github.com/google/blockly/issues/new?assignees=&labels=type%3A+bug%2C+triage&template=bug_report.md)
- [Blockly-samples](https://github.com/google/blockly-samples/issues/new?assignees=&labels=type%3A+bug%2C+triage&template=bug_report.md)

Be sure to fill out all of the sections of the issue template, even the ones not detailed here.

Thank you for your interest in reporting a bug, and happy issue writing!

### What's Next?

- Your bug report is automatically tagged for triage.
- The on-call member of the Blockly team will take a look and possibly ask clarifying questions. They will also add labels, which we use to keep our bugs organized.
- The issue may be marked "Help Wanted", in which case you can claim it and start working on it.
- The issue may be assigned to a member of the Blockly team for a fix.
- The issue may be marked with a quarterly milestone, to indicate when it will be done.
- The issue may be placed in the Icebox milestone, meaning that we do not intend to work on it in the foreseeable future.
  - This may happen for low-frequency issues or bugs with known workarounds.
  - You can still work on Iceboxed issues.
- The issue may be placed in the Bug Bash Backlog milestone, meaning that it is non-urgent but we still want to fix it.
  - At the end of every quarter the team spends a few weeks working on bugs pulled from the Bug Bash Backlog milestone.
- The issue may be moved from Blockly core to blockly-samples (or the opposite direction) if needed.
- The issue may be closed.

## Feature Request

Is there something you want to change to make Blockly better? Do you have an idea for a plugin, example, or codelab? Maybe there's already one you like, and you've come up with a way to improve it. If so then you've come to the right place! Here are steps to help you create a great feature request that gets a response.

1.  [Check for Duplicates](/guides/contribute/get-started/write_a_good_issue#check-for-duplicates)
2.  [Check the Requirements](/guides/contribute/get-started/write_a_good_issue#check-the-requirements)
3.  [Gather your Thoughts](/guides/contribute/get-started/write_a_good_issue#gather-thoughts)
4.  [Write your Feature Request!](/guides/contribute/get-started/write_a_good_issue#write-the-request)

### Check the Requirements

We would love to allow every single idea to enter this repository! But sadly we're only human, so we have some guidelines in place about what kinds of requests we will pursue.

Here are the guidelines for each of the different categories of projects:

- [Blockly core](/guides/modify/contributing)
- [Plugins](/guides/plugins/overview#first-party-criteria)
- Examples: Show how to use only one or two Blockly features.
- Codelabs: Show how to complete a single task or implement a single behaviour.

But these aren't hard and fast rules. They're just meant to give you an idea of what we're looking for before you put time into building your feature request.

If you're unsure whether something fits, try posting it on our [developer forums](https://groups.google.com/forum/#!forum/blockly). And remember, even if your idea doesn't get accepted, we would still love for you to build it as a third party plugin or tutorial!

### Gather your Thoughts

Your idea doesn't need to be 100% fleshed out with tinsel and diagrams before you go ahead and submit, but you should have a solid idea of what you're looking for. These are some good questions to ponder before you start to write:

- Why do I want this feature?
- Does this feature solve a problem?
- Who is the intended audience for this feature?
- Why does this feature serve them?
- What are some alternative options that could achieve the same thing?

Once you have those things figured out, you'll be most of the way to a good feature request!

### Write your Feature Request!

Now you're ready to write your feature request. Select your repository:

- [Blockly core](https://github.com/google/blockly/issues/new?assignees=&labels=type%3A+feature+request%2C+triage&template=feature_request.md)
- [Blockly-samples](https://github.com/google/blockly-samples/issues/new?assignees=&labels=type%3A+feature+request%2C+triage&template=feature_request.md)

Be sure to fill out all of the sections of the issue template, even the ones not detailed here.

Thank you for your interest in submitting a feature request, and happy issue writing!

### What's Next?

- Your feature request is automatically tagged for triage.
- The on-call member of the Blockly team will take a look and possibly ask clarifying questions. They will also add labels, which we use to keep our bugs organized.
- The feature may be marked "Help Wanted", in which case you can claim it and start working on it.
- The feature may be assigned to a member of the Blockly team for implementation.
- The feature request may be moved from Blockly core to blockly-samples (or the opposite direction) if needed.
- The feature request may be closed, in which case you still have the option to implement it as a third-party plugin.
