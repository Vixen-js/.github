# Contributing to Vixen-js projects

First off, thanks for taking the time to contribute!

The following is a set of guidelines for contributing to Vixen-js and its packages, which are hosted in the [Vixen-js Organization](https://github.com/vixen-js) on GitHub. These are mostly guidelines.


## Code of Conduct

This project and everyone participating in it is governed by the [Vixen Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code. Please report unacceptable behavior to [Seobryn](mailto:ing.jose.joya@gmail.com).

## I don't want to read this whole thing I just have a question!!!

`Please spend a moment to read this before asking questions. You'll get faster results by using the resources below and you will also save time of other contributors.`

## What should I know before I get started?

### Vixen-js and Packages

Vixen-js is an open source project &mdash; it's made up of multiple repositories (https://github.com/vixen-js).

Vixen-js is designed on a plugin based architecture. That means while it provides core features through the main package at https://github.com/vixen-js/core, many of its features and extensions will be implemented as plugins. For example, while the Vixen-js core package contains many useful widgets and APIs, newer and heavier features like webview will be implemented as a plugin.

Also, Vixen-js will act as a base package for varous rendering targets like React. The official renderer for React is [Vixen-js Core React](https://github.com/vixen-js/core-react)


#### Plugin Conventions

There are a few conventions around packages:
- All plugins should be named as vixen-plugin-<name_of_plugin>. for example, if the plugin is webview, it would be called as vixen-plugin-webview. This will allow users to search for plugins easily.

### Design Decisions

There are certain design decision made by the maintainers and the contributors of the project. Any major architectural changes will not be entertained at this time. This is because the project is at its infancy and the goal currently is to provide more features and usable widgets to the end users of this library. Although this will change in future if/when the project is adopted more or if need arises.

## How Can I Contribute?

### Reporting Bugs

This section guides you through submitting a bug report for Vixen-js Projects. Following these guidelines helps maintainers and the community understand your report 📝, reproduce the behavior 🖥️, and find related reports 🔎.

While reporting a bug, please fill out [the required template](https://github.com/vixen-js/.github/blob/master/.github/ISSUE_TEMPLATE/report_bugs.md), the information it asks for helps us resolve issues faster. If the bug report is not filed with the issue template it might be closed without any response.

> **Note:** If you find a **Closed** issue that seems like it is the same thing that you're experiencing, open a new issue and include a link to the original issue in the body of your new one.

#### Before Submitting A Bug Report

* **Check the [FAQ](https://vixen-js.github.io/docs/faq).** You might be able to find the cause of the problem and fix things yourself. Most importantly, check if you can reproduce the problem [in the latest version of Vixen-js]
  
* **Determine which repository the problem should be reported in**.
  
* **Perform a [cursory search](https://github.com/search?q=+is%3Aissue+user%3AVixen-js)** to see if the problem has already been reported. If it has **and the issue is still open**, add a comment to the existing issue instead of opening a new one.


### Suggesting Enhancements

This section guides you through submitting an enhancement suggestion for Vixen-js, including completely new features and minor improvements to existing functionality. Following these guidelines helps maintainers and the community understand your suggestion 📝 and find related suggestions 🔎.

Before creating enhancement suggestions, please check the roadmap as you might find out that you don't need to create one. When you are creating an enhancement suggestion, please fill in [the template](https://github.com/vixen-js/.github/blob/master/.github/ISSUE_TEMPLATE/request_new_features.md), including the steps that you imagine you would take if the feature you're requesting existed.


#### Before Submitting An Enhancement Suggestion

*  Most importantly, check if you're using the latest version of Vixen-js.
  
* **Check if there's already a third party plugin that provides this enhancement?**
  
* **Perform a [cursory search](https://github.com/search?q=+is%3Aissue+user%3AVixen-js)** to see if the enhancement has already been suggested. If it has, add a comment to the existing issue instead of opening a new one.
  
* If a enhancement can be created as a plugin, please try and implement it as a plugin instead of a core feature.

#### Enhancement that will not be considered at this time

* Any major architectural changes to the codebase: If the enhancement you want requires major architectural changes, there is a good chance that it will not be considered at this point of time.  This is because the project is at its infancy and the goal currently is to provide more features and usable widgets to the end users of this library. This will change in future if/when the project is adopted more or if need arises.

* Opinionated changes: Things like styleguide, linting, addition of external dependencies (including test framework) etc unless extrememly critical will not be considered at this time. Again, this will change in future once we reach a basic stable release. All these will be fixed by the core team and then we can have a discussion on what needs to be changed. Currently the project is in its experimental stage and hence nothing is really fixed. 


#### Enhancements that will be considered

Anything that is not opinionated, helpful for the end user.