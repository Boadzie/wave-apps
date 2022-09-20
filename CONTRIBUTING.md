# Contributing Guide

We appreciate all contributions. If you are planning to contribute back bug-fixes, please do so without any further discussion.

If you plan to contribute new features, please first [open an issue](https://github.com/h2oai/wave-apps/issues/new) and discuss the feature with us. Sending a PR without discussion might end up resulting in a rejected PR because we might be taking the software in a different direction than you might be aware of.

(Based on the [PyTorch Contribution Guide](https://pytorch.org/docs/stable/community/contribution_guide.html).)

## About open source development

If this is your first time contributing to an open source project, some aspects of the development process may seem unusual to you.

- **There is no way to "claim" issues.** People often want to "claim" an issue when they decide to work on it, to ensure that there isn’t wasted work when someone else ends up working on it. This doesn’t really work too well in open source, since someone may decide to work on something, and end up not having time to do it. Feel free to give information in an advisory fashion, but at the end of the day, we will take running code and rough consensus.

- **There is a high bar for new functionality that is added.** Unlike in a corporate environment, where the person who wrote code implicitly "owns" it and can be expected to take care of it in the beginning of its lifetime, once a pull request is merged into an open source project, it immediately becomes the collective responsibility of all maintainers on the project. When we merge code, we are saying that we, the maintainers, are able to review subsequent changes and make a bugfix to the code. This naturally leads to a higher standard of contribution.

## Proposing new features

New feature ideas are best discussed on a specific issue. Please include as much information as you can, any accompanying data, and your proposed solution. The H2O team and community frequently reviews new issues and comments where they think they can help. If you feel confident in your solution, go ahead and implement it.

## Reporting issues

If you’ve identified an issue, first search through the list of existing issues on the repo. If you are unable to find a similar issue, then create a new one. Supply as much information you can to reproduce the problematic behavior. Also, include any additional insights like the behavior you expect.

## Implementing features

If you want to fix a specific issue, it’s best to comment on the individual issue with your intent. However, we do not lock or assign issues except in cases where we have worked with the developer before. It’s best to strike up a conversation on the issue and discuss your proposed solution. The H2O team can provide guidance that saves you time.

Issues that are labeled **good first issue**, **low** or **medium** priority are great places to start. Only issues that have assigned a milestone or are tagged with **help needed** / **good first issue** will be merged.

## Improving documentation and tutorials

We aim to produce high quality documentation and tutorials. On rare occasions that content includes typos or bugs. If you find something you can fix, send us a pull request for consideration.

## Submitting pull requests

You can view a list of all [open issues](https://github.com/h2oai/wave-apps/issues). Commenting on an issue is a great way to get the attention of the team. From here you can share your ideas and how you plan to resolve the issue.

For more challenging issues, the team will provide feedback and direction for how to best solve the issue.

If you’re not able to fix the issue yourself, commenting and sharing whether you can reproduce the issue can be useful for helping the team identify problem areas.

## Improving code readability

Improved code readability helps everyone. It is often better to submit a small number of pull requests that touch few files versus a large pull request that touches many files. Opening an issue related to your improvement is the best way to get started.

## Adding test cases

Additional test coverage is appreciated.  Help us make the codebase more robust.

## Security vulnerabilities

If you discover a security vulnerability within H2O Wave, please send an email to Prithvi Prabhu at prithvi@h2o.ai. All security vulnerabilities will be promptly addressed.

## Development

Since this repo is a collection of apps. You only need Python3.7 installed and you can start coding your [H2O Wave app](https://wave.h2o.ai/docs/apps). When contributing a new app, make sure your project structure matches the one other apps use as well.
