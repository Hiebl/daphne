<!--
Copyright 2021 The DAPHNE Consortium

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
-->

# Contributing to the DAPHNE System

*Thank you* for your interest in contributing to the DAPHNE system.
Our goal is to build an **open and inclusive community of developers** around the system.
Thus, **contributions are highly welcome**, both from *within the DAPHNE project consortium* and from *external researchers/developers*.

In the following, you find some rough **guidelines on contributing**, which will most likely be extended and further clarified in the future.

## Ways of Contributing

There are **various ways of contributing** including (but not limited to):
- actual implementation
- writing test cases
- writing documentation
- reporting bugs or any other kind of issue
- contributing to discussions

We encourage **open communication** about the system through *comments* on *issues* and *pull requests* directly on GitHub.
That way, discussions are made *accessible and transparent* to everyone interested.
This is important to *involve people* and to *avoid repetition* in case multiple people have the same question/comment or encounter the same problem.
So feel free to create an issue to start a discussion on a particular topic (including these contribution guidelines) or to report a bug or other problem.

## Issue tracking

All open/ongoing/completed **work is tracked as issues** on GitHub.
These could be anything from precisely defined small tasks to requests for complex components.
In any case, we will try to keep the book-keeping effort at a low level; at the same time, we should make each other aware of what everyone is working on to avoid duplicate work.

If you would like to contribute and are **looking for a task** to work on, browse the [list of issues](https://github.com/daphne-eu/daphne/issues).
If you are a *new contributor*, you might want to watch out for ["good first issues"](https://github.com/daphne-eu/daphne/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22).

Furthermore, everyone is invited to **create issues**, e.g., for *tasks* you want to work on or *problems* you encountered.
This is also a good way to enable discussion on the topic.
Note that there is a set of *labels* that can be attached to your issue to clarify what it is about and to make it more easy to find.

## Contributing to the Source Code

We appreciate that different contributors can have different levels of familiarity with the code base, and try to adapt to that accordingly.

### New DAPHNE Contributors

**Contributions from new people are always welcome**, both from within the DAPHNE project consortium and external!
We are aware that contributing to a new code base *can be challenging* in the beginning.
Thus, we want to *keep the barrier of entry low* for new contributors.
That is, please try your best to make a good-quality contribution and we will help you with constructive feedback.

**The procedure is roughly as follows:**

1. **Fork the repository** on GitHub and **clone your fork** (see [GitHub docs](https://docs.github.com/en/get-started/quickstart/fork-a-repo)).
   We recommend cloning by `git clone --recursive https://github.com/<USERNAME>/daphne.git` (note the `--recursive`), as specified in [Getting Started](/doc/GettingStarted.md).
3. **Create your own local branch**: `git checkout -b BRANCH_NAME`.
   `BRANCH_NAME` should clearly indicate what the branch is about; the recommended pattern is `123-some-short-title` (where `123` is the issue number).
3. **Add as many commits as you like** to your branch, and `git push` them to your fork.
   Use `git push --set-upstream origin BRANCH_NAME` when you push the first time.
5. If you work longer on your contribution, make sure to **get the most recent changes from the upstream** (original DAPHNE system repository) from time to time (see [GitHub docs](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/syncing-a-fork)).
6. Once you feel ready (for integration or for discussion/feedback), **create a pull request** on GitHub (see [GitHub docs](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request)).
   Please choose an expressive title and provide a short description of your changes.
   Feel free to mark your pull request "WIP: " or "Draft: " in the title.
   Note that you can add more commits to your pull request after you created it.
6. You **receive feedback** on your proposed contribution.
   You may be asked to apply certain changes, or we might apply straightforward adjustments ourselves before the integration.
7. If it looks good (potentially after some help), **your contribution becomes a part of DAPHNE**.

### Experienced DAPHNE Contributors

We appreciate *continued commitment* to the DAPHNE system.
Thus, **frequent contributors can become collaborators** on GitHub.
Currently, this requires **at least three non-trivial contributions** to the system.
Collaborators have *direct write access* to all branches of the repository, including the main branch.

The goal is to **make development easier for frequent contributors**.
Collaborators do not need to create a fork, and do not need to go through pull requests to integrate their changes.
At the same time, this freedom comes with certain responsibilities, which are roughly sketched here:

1. Please **follow some simple guidelines when changing the code**:
   - Feel free to directly push to the main branch, but *be mindful of what you commit*, since it will affect everyone.
     As a guideline, commits fundamentally changing how certain things work should be announced and discussed first, whereas small changes or changes local to "your" component are not critical.
   - But **never force push to the main branch**, since it can lead to severe inconsistencies in the Git history.
   - Even *collaborators may still use pull requests* (just like new contributors) to suggest larger changes.
     This is also suitable whenever you feel unsure about a change or want to get feedback first.
2. Please **engage in the handling of pull requests**; especially those affecting the components you are working on.
   This includes:
   - reading the code others suggest for integration
   - trying if it works
   - providing constructive and *actionable* feedback on improving the contribution prior to the integration
   - actually merging a pull request in
   
   Balancing the handling of pull requests is important to *keep the development process scalable*.
