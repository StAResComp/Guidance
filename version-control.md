# Version control

## Introduction

When working with computer files of any kind, keeping track of changes is important. For example, you may want to

- Keep track of who made what changes to a document - and why.
- Be able to quickly roll back to a previous version of your software after that new feature caused some unexpected behaviour.
- Run the version of your software that you used for that experiment last month.

A version control system like [Git](https://git-scm.com) can greatly ease these activities, particularly when working with [plain text](https://en.wikipedia.org/wiki/Plain_text) file formats like source code and markup.

If you make some changes to a set of files or *repository* under version control, you then *commit* those changes with a short message describing why the changes were made. It is possible to review all the commits made, revert to any previously committed version, or to view the differences between any two versions. Specific versions can be *tagged* e.g. as releases.

*Branches* allow for multiple versions to exist in parallel. For example, you release version 1.0 of your software. It probably makes sense to maintain one branch for working on bugfixes for version 1.0 while working on the new features for 1.1 in another. These branches can later be *merged*. Branches are particularly useful when multiple people are working on something together, synchronising their repositories with a central server.

**It is strongly recommended that all source code be placed under version control.**

To learn more about version control in general and Git in particular, take a look at *Pro Git* by Scott Chacon and Ben Straub and published by Apress, available to [read online](https://git-scm.com/book/en/v2).

## GitHub

[GitHub](https://github.com) is a hosted Git repository service, widely used by open source projects. Anyone can register and create public repositories, with the ability to create private repositories available as a paid-for service. However, **academics can get [private repositories for free](https://education.github.com/discount_requests/new)**.

GitHub is a U.S. company and data they collect will be [stored and processed in the United States](https://help.github.com/articles/github-privacy-statement/#githubs-global-privacy-practices). As such it is not appropriate for any data or code which is sensitive e.g. data which includes information which could be used to identify individuals or software developed with industrial partners which is commercially sensitive.

Take a look at [GitHub's documentation](https://guides.github.com/activities/hello-world/) for help on getting up and running with the service.

## Clients

Version control systems can typically be used either via command-line or graphical clients. In the case of Git, [SourceTree](https://www.sourcetreeapp.com) and [GitHub Desktop](https://desktop.github.com) (for working with GitHub repositories) are good free graphical clients.

{% include footer.html %}
