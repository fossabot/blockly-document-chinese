# Writing a Good Pull Request

Pull requests are like the life blood of a repository. They keep everything healthy and moving. This page details how to create a PR that is complete and easy to review, which makes it more likely that your PR will get merged.

Here are steps you can take to make sure you create the best PR possible.

1.  [Communicate](/guides/contribute/get-started/write_a_good_issue#communicate-1)
2.  [Get Set Up](/guides/contribute/get-started/write_a_good_issue#get-set-up)
3.  [Keep it Small](/guides/contribute/get-started/write_a_good_issue#keep-it-small)
4.  [Keep it Clean](/guides/contribute/get-started/write_a_good_issue#keep-it-clean)
5.  [Test your Change](/guides/contribute/get-started/write_a_good_issue#test-your-change)
6.  [Communicate (pt2)](/guides/contribute/get-started/write_a_good_issue#communicate-2)

### Communicate

Before you jump in and start writing code, it's helpful to communicate with the core team so they know what you're interested in.

If there is an issue you are interested in, put a comment on the issue saying you're going to start to work on it. This makes sure that we don't have multiple people working on the same thing. A team member will respond to confirm that it's yours.

If you have an idea which is not covered by an issue, please [write one up](/guides/modify/contribute/write_a_good_issue) before you begin work. This gives the team a chance to discuss how best to build out the change _before_ you start building, which saves you work in the long run.

### Get Set Up

If this is your first time contributing to Blockly or blockly-samples, start at the [development setup](/guides/modify/development_setup) page.

### Keep it Small

Always try to keep your changes small and focused. We would much rather review multiple smaller PRs than review one giant PR. Some good rules of thumb are:

- **Fix one problem.** Don't try to tackle multiple issues at once.
- **Limit the scope.** Usually a PR should take < 8hrs (depending on your familiarity with the codebase).
- **Use commits.** If your PR feels a little big, split the changes into logical groups using git commits.

### Keep it Clean

Why care about code style? We're in it for the long term, and consistent style makes maintenance easier. Style refers to how you name your variables, but also covers how you structure your code, write comments, and more. Where possible we use tools such as eslint to automate style checks.

In addition to eslint, please follow these guides:

- [Google JavaScript style guide](https://google.github.io/styleguide/jsguide.html).
- [Commit Message Guide](/guides/contributing/commits)
- [Guidelines on Using Blockly APIs](/guides/plugins/using_blockly_apis)
- [Codelab style guide](https://github.com/google/blockly-samples/wiki/Writing-a-Codelab#writing-tips)

### Test your Change

Before you put up a PR you should always test that your changes are working, so that you don't have to go back and fix things later. Here are some ideas for testing the different categories of projects:

- For **plugins**: write automated mocha tests covering your changes.
- For **examples**: manually test all of your demonstrated functionality.
- For **codelabs**: run through the entire tutorial in a clean environment and test any example code you provide.

### Communicate

This is the last and arguably the most important part of creating a PR: writing the summary.

Writing a great PR summary helps other developers review your changes, making it more likely that it will get accepted faster!

Your summary should include things like:

- What issue your PR is related to.
- What change your PR adds.
- How you tested your change.
- Anything you want reviewers to scrutinize.
- Any other information you think reviewers need.

If you follow the PR template when your create your request you should be good to go. Just remember to be as **concise** and **complete** as possible.

Happy Coding!
