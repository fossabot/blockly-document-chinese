# Issue Labels

Labels are a cool feature of GitHub that allow you to filter issues and pull requests. They help you find something fun to work on that fits with your level of experience.

For our repositories, adding new labels to issues is handled exclusively by the core Blockly team, to make sure that things don't end up in the wrong spot.

::: tip Note
For more information about using labels, see [Filtering issues and pull requests](https://help.github.com/en/github/managing-your-work-on-github/filtering-issues-and-pull-requests-by-labels).
:::

### Size

Some issues are bite-sized and beautiful, while others could take weeks to defeat. These labels help you tell how much work an issue will probably take.

-   **[Good first issue](https://github.com/google/blockly-samples/labels/good%20first%20issue):** These issues are great for people who are new to the repository. They should take less than half a day's work and require limited familiarity with the code base. You can start work on these issues immediately, without approval from the team.

### Jurisdiction

Working on a widely-used repo can be a sensitive process, and some issues can be more sensitive than others. These labels help you tell which issues are open for contribution, and which issues to steer clear of.

-   **[Help wanted](https://github.com/google/blockly-samples/labels/help%20wanted):** These issues are reserved for contributors. Often they are features the core team think would be useful, but don't have time to implement. They may need either discussion or implementation, so check the status label to see what work is needed. This is a good place to find fun creative projects!
-   **[Internal](https://github.com/google/blockly-samples/labels/internal):** These issues are reserved for members of the core team. Often they are sensitive or complex bugs that need special discussion. It's best to steer clear of these because the situation around them could change rapidly!
-   **[Neither](https://github.com/google/blockly-samples/issues?q=is%3Aissue+is%3Aopen+-label%3A%22help+wanted%22+-label%3A%22internal%22):** Issues that have neither label can be fixed by contributors _and_ members of the core team. If you see an unlabeled issue that seems interesting to you, go ahead and take it!

### Status

Certain issues (particularly feature requests) go through a few different stages before they can be considered "closed". These labels tell you what stage an issue is currently in, so you can know what needs to be done.

-   **[Discussion](https://github.com/google/blockly-samples/labels/status%3A%20discussion):** These issues are in the [discussion phase](https://github.com/google/blockly-samples/wiki/Adding-A-Plugin#discussion), which means there are still questions that need to be answered before implementation. If you have any thoughts related to this issue, feel free to leave a comment! We're always looking for more input.
-   **[Implementation](https://github.com/google/blockly-samples/labels/status%3A%20implementation):** These issues have had enough discussion that they are clearly defined, and have moved into the [implementation phase](https://developers.google.com/blockly/guides/modify/contribute#implementation). They are either waiting for implementation, or already being implemented. If you're interested in working on one of these, read through the whole issue and then leave a comment saying which part you want to work on, then go ahead and dive in!
-   **[Neither](https://github.com/google/blockly-samples/issues?q=is%3Aissue+is%3Aopen+-label%3A%22status%3A+discussion%22+-label%3A%22status%3A+implementation%22+):** Issues that have neither label could be in either state. If you have an opinion about how the issue should be implemented, go ahead and leave a comment! Alternatively if you're interested in _working_ on the issue, it is best to leave a comment asking if it is ready to be implemented.

### Type

Different issues require different responses. Some only require editing a few lines of code, while others need lots of design and discussion. These labels tell you what type of action an issue will need.

-   **[Bug](https://github.com/google/blockly-samples/labels/type%3A%20bug):** These issues document a problem with the codebase. They often take some debugging to diagnose what's causing the problem, but some can be fixed in a wink. If you like digging deep to learn how the code ticks, these will be great issues for you. You can help either by fixing the bug or by digging to understand the issue and writing a clear explanation of the root cause.
-   **[Feature request](https://github.com/google/blockly-samples/labels/type%3A%20feature%20request):** These issues document a feature that someone would like to have added. This can apply to the repository as a whole, or to an individual project. If you like fleshing out design ideas and adding new functionality, these could be the perfect issues for you.
-   **[Question](https://github.com/google/blockly-samples/labels/type%3A%20question):** These issues document a question someone has about the codebase. Generally these questions are redirected to the [developer forum](https://groups.google.com/forum/#!forum/blockly), but if you see a question you feel you could help with, feel free to jump in and respond.

### Category

This repository contains a few different kinds of projects, with a few different kinds of target audiences. If you are passionate about tutorials, or love working on plugins, these labels can help you find issues you're interested in.

-   **[Codelab](https://github.com/google/blockly-samples/labels/category%3A%20codelab):** These issues relate to Blockly [codelabs](https://developers.google.com/blockly/guides/plugins/samples_repository_structure#codelabs), a suite of interactive tutorials.
-   **[Example](https://github.com/google/blockly-samples/labels/category%3A%20example):** These issues relate to Blockly [examples](https://developers.google.com/blockly/guides/plugins/samples_repository_structure#examples), a set of self-contained demos showcasing how to include and extend Blockly.
-   **[Plugin](https://github.com/google/blockly-samples/labels/category%3A%20plugin):** These issues relate to Blockly [plugins](https://developers.google.com/blockly/guides/plugins/samples_repository_structuree#plugins), a collection of extensions that add functionality Blockly.

### Project

And if you want to get even more fine-grained there are also tags for individual projects. These are usually created for plugins, which tend to have more issues related to them, but they can also be created for codelabs and examples. If you have a particular project you are interested in, these labels can help you find issues related to that project.

Also note that new projects are added often so this list may go out of date! Check the [full list of labels](https://github.com/google/blockly-samples/labels) if you don't see an entry for the project you are interested in.

-   **[Dev tools](https://github.com/google/blockly-samples/labels/%E2%9A%AA%20dev-tools):** These issues relate to the [dev tools](https://github.com/google/blockly-samples/tree/master/plugins/dev-tools) package, a library of common utilities for Blockly extension development.
-   **[Field date](https://github.com/google/blockly-samples/labels/%E2%9A%AA%20field-date):** These issues relate to the [date field](https://github.com/google/blockly-samples/tree/master/plugins/field-date) package, a date picker field that uses the Google Closure date picker.
-   **[Field slider](https://github.com/google/blockly-samples/labels/%E2%9A%AA%20field-slider):** These issues relate to the [slider field](https://github.com/google/blockly-samples/tree/master/plugins/field-slider) package, a number input field with a slider UI.
-   **[Plugin workspace search](https://github.com/google/blockly-samples/labels/%E2%9A%AA%20plugin-workspace-search):** These issues relate to the [workspace search](https://github.com/google/blockly-samples/tree/master/plugins/workspace-search) package, a plugin which adds workspace search support.

### Other

As with any collection of things, there are a few odd-balls you should also know about. These labels may not be as helpful when you're looking for an issue to work on, but they can still be informative.

-   **[Triage](https://github.com/google/blockly-samples/labels/triage):** These issues have yet to be properly labeled by the core team. Issues with this label may already include another simple label like [bug](https://github.com/google/blockly-samples/labels/type%3A%20bug) or [feature request](https://github.com/google/blockly-samples/labels/type%3A%20feature%20request), but it is likely that more labels will be added soon.
-   **[Duplicate](https://github.com/google/blockly-samples/labels/duplicate):** These issues document a problem, request, or question that is already covered by another issue. This label tells you that you should not reply to this issue, but instead reply to the original issue.