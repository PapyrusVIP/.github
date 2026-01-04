# Contributing

Welcome! We’re excited that you’re interested in contributing to our projects.
Your contributions help us keep everything running smoothly.

This document outlines the best practices for contributing to our repositories.

## Reporting security issues

Please refer to our [security policy](SECURITY.md) for instructions on how to responsibly report security vulnerabilities.

## Reporting other issues

A great way to contribute is to send a detailed report when you encounter an issue.

If you find a bug in the source code, please [submit an issue](#submitting-an-issue) in the relevant GitHub repository.
Even better, if you can, [submit a pull request](#submitting-a-pull-request) with a fix.

## Requesting a Feature

You can *request* new features by [submitting an issue](#submitting-an-issue) in our GitHub repository.
If you’re interested in *implementing* a feature, please evaluate the size and impact of the change before deciding how to proceed:

  - For **Major features**, please start by opening an issue to outline your proposal and allow for discussion.
    This process helps coordinate development efforts, reduce duplication,
    and work together to shape the change so it can be successfully accepted into the project.

  - **Small features** can be implemented and [submitted directly as a pull request](#submitting-a-pull-request).

**Note:** If you're unsure how big the feature is, or just want to play it safe, please open an issue.

## Submission Guidelines

### Submitting an Issue

If you're using one of our open source projects and run into any issues, feel free to open an issue on the repository.
Whether or not you think the problem is with the project itself.

Before you submit an issue, please search and check if there's already an existing issue for your problem. 
You might even find useful discussions or workarounds that can help you.

Please try to use our issue templates whenever possible, to reduce the amount of back and forth communication.

### Submitting a Pull request

Please use the search feature to ensure that no one else is working on your change before you start.

Then you can fork the repository and make your changes in a feature branch:

```
git checkout -b feature-branch main
```

When making commits, remember to [sign them off](#sign-your-work).

After you make your change, please make sure you run any formatter, linter or tests the project provides to make sure they pass.

Remember to update any tests and/or documentation the project has if you add a new feature or change anything significant.

After that, you can use the Github website to submit a Pull request.
Just make sure the pull request description is easy to understand and includes a reference to every issue it addresses.


## Conventions

### Commit Messages

We follow the [Conventional Commits](https://www.conventionalcommits.org) standard for all Git commit messages.

```
<type>(scope): <short summary>
```

### Sign your work

The sign-off is a simple line at the end of the explanation for the patch. Your
signature certifies that you wrote the patch or otherwise have the right to pass
it on as an open-source patch. The rules are pretty simple: if you can certify
the below (from [developercertificate.org](http://developercertificate.org)):

```
Developer Certificate of Origin
Version 1.1

Copyright (C) 2004, 2006 The Linux Foundation and its contributors.

Everyone is permitted to copy and distribute verbatim copies of this
license document, but changing it is not allowed.

Developer's Certificate of Origin 1.1

By making a contribution to this project, I certify that:

(a) The contribution was created in whole or in part by me and I
    have the right to submit it under the open source license
    indicated in the file; or

(b) The contribution is based upon previous work that, to the best
    of my knowledge, is covered under an appropriate open source
    license and I have the right under that license to submit that
    work with modifications, whether created in whole or in part
    by me, under the same open source license (unless I am
    permitted to submit under a different license), as indicated
    in the file; or

(c) The contribution was provided directly to me by some other
    person who certified (a), (b) or (c) and I have not modified
    it.

(d) I understand and agree that this project and the contribution
    are public and that a record of the contribution (including all
    personal information I submit with it, including my sign-off) is
    maintained indefinitely and may be redistributed consistent with
    this project or the open source license(s) involved.
```

Then you just add a line to every git commit message:

    Signed-off-by: Joe Smith <joe.smith@email.com>

Use your real name or github username (sorry, no pseudonyms or anonymous contributions.)

If you set your `user.name` and `user.email` git configs, you can sign commits automatically with `git commit -s`

## Community Guidelines

All contributors and participants are expected to follow our [Code of Conduct](CODE_OF_CONDUCT.md)
to help keep our community safe and welcoming.

## Contact

If you have any questions, please reach out to [opensource@papyrus.vip](mailto:opensource@papyrus.vip).
