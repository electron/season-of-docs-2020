



# Electron: Google Season of Docs 2020

*[Website](https://electronjs.org) | [GitHub](https://github.com/electron/electron) | [Season of Docs](https://developers.google.com/season-of-docs)*

The Electron maintainers are excited to be applying to the second edition of Google's [Season of Docs](https://developers.google.com/season-of-docs) program! Season of Docs is an initiative that pairs technical writers with open source organizations to improve their project documentation.


## What is Electron?

[Electron](https://electronjs.org) is a JavaScript framework that empowers developers to create cross-platform desktop applications using HTML, CSS, and JavaScript. Over the years, it has grown to be a leader in desktop app development, with [over 80000 stars on GitHub](https://github.com/electron/electron) and a long list of companies that trust it to to build high-quality applications that users love, including [WhatsApp](https://www.whatsapp.com/), Microsoft Teams, Slack, and Visual Studio Code.

## Project Ideas

Although [our documentation pages](https://www.electronjs.org/docs) get hundreds of thousands of unique pageviews every month, we are very far away from having the structure and clarity of documentation we admire. The project list below outlines a couple ideas we have for Season of Docs 2020, but these are only a few examples of the many improvements we could make. A technical writer involved in any of these project ideas will work alongside Electron's [Ecosystem Working Group](https://github.com/electron/governance/tree/master/wg-ecosystem) to refine these initial idea drafts and implement them in the electronjs.org documentation.

### 1. Electron Tutorial Flow

#### Description

Currently, the main way to access Electron's documentation is through the "Docs" page in the navbar at electronjs.org, which brings you to the [Docs](https://www.electronjs.org/docs) page.

There is some degree of organization there already: new developers can easily access the "Setting up the Development Environment" and "Creating your First App" sections to get started. However, it is unclear where new developers should go from there, as the breadth of topics that Electron covers can seem overwhelming to developers who are new to the framework.

Examples of things that could be structured better are:
* Introducing the [application architecture](https://www.electronjs.org/docs/tutorial/application-architecture)
* Guides for specific Electron features
* Deploying an application to production

#### Expected Outcomes

Ideally, we would have a more focused tutorial flow to streamline this learning process. This would involve updating the existing tutorial content and providing a better information architecture that can teach newcomers with a minimal amount of friction.

#### Project Deliverables

* Rewrite and expansion of the [First App](https://www.electronjs.org/docs/tutorial/first-app) tutorial that attempts to include more Electron fundamentals in its explanation.
* Inclusion of [electron/electron-api-demos](https://github.com/electron/electron-api-demos) repository content in documentation.
* Reorganization of our existing guides to complement the new tutorial.
* Restructuring of [Docs directory](https://www.electronjs.org/docs) to provide new users with a visual hierarchy of important documentation.
* *Bonus*: Integration of [Electron Fiddle](https://electronjs.org/fiddle) examples into our docs. We already have the architecture set up to launch Electron Fiddle directly from our website (see [electron/electronjs.org#2848](https://github.com/electron/electronjs.org/pull/2848)), but we have not yet leveraged this powerful capability.

#### Preferred skills

Experience with JavaScript in the past (Browser or Node.js).


### 2. Contributor Documentation

#### Description

The barrier of entry for contributing to Electron internals is unfortunately higher than for most other JavaScript frameworks because of its complex build process and the codebase's reliance on C++ and Objective-C.

Although we do have a section on [Contributing to Electron](https://www.electronjs.org/docs/development) in our documentation, the documentation is not nearly complete enough to onboard potential new contributors, and the documentation that *is* there focuses mostly on the mechanics of submitting a contribution rather than.

One good place to start would be to integrate the following [talk from Covalence Conference 2020](https://www.youtube.com/watch?v=1h8Fv4D-bTA), where core maintainer [@ckerr](https://github.com/ckerr) gave a great intro to contributing, into a concise doc. Another would be to do the same for other learning materials such as the [electron/onboarding-guide](https://github.com/electron/onboarding-guide) repository, but haven't integrated into our website.

Examples of things that could be documented better are:
* Updated tooling guides (e.g [electron/build-tools](https://github.com/electron/build-tools)).
* Reasoning about the C++ codebase (see [electron/onboarding-guide](https://github.com/electron/onboarding-guide)).

#### Expected Outcomes

Ideally, this revamped Contributor onboarding experience would be enough for a developer familiar with Electron to understand enough about the framework's internals to make contributions to the codebase.

#### Deliverables
* Better information architecture for the existing [development docs](https://www.electronjs.org/docs/development).
* A new onboarding tutorial that explains a high-level overview on how to navigate the codebase.
* An updated [Build Instructions](https://www.electronjs.org/docs/development/build-instructions-gn) guide that involves newer tooling used by Electron maintainers, such as [electron/build-tools](https://github.com/electron/build-tools).

#### Preferred skills

Experience with Node.js and/or C++ in the past.
