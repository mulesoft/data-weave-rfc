# Contributing Guide For DataWeave RFC

This page lists the operational governance model of this project, as well as the recommendations and requirements for how to best contribute to the DataWeave RFC repository. We strive to obey these as best as possible. As always, thanks for contributing – we hope these guidelines make it easier and shed some light on our approach and processes.

# Governance Model

## Salesforce Sponsored

The intent and goal of open sourcing this project is to increase the contributor and user base. However, only Salesforce employees will be given `admin` rights and will be the final arbitrars of what contributions are accepted or not.

# Getting started

Please join our community [Slack](https://join.slack.com/t/dataweavelanguage/shared_invite/zt-1ewv2igp0-3ZiqQqaMdO_utwaEjxBpTw) and the `#opensource` channel. Also read the [README](README.md) for the full RFC process description.

# Issues, requests & ideas

Use GitHub [Issues](https://github.com/mulesoft/data-weave-rfc/issues) to discuss ideas or problems before writing a formal RFC.

### Proposing a Substantial Change
-  If you'd like the subject to be discussed before jumping into a formal RFC, [create an issue](https://github.com/mulesoft/data-weave-rfc/issues/new) explaining the idea or the problem you'd like to solve.
-  A corresponding [proposal](https://github.com/mulesoft/data-weave-rfc/tree/master/proposals) can be merged simultaneously to later expedite the RFC process.
-  Once you are ready to move forward, follow the [RFC process](README.md#the-process) described in the README: copy `0000-template.md` to `text/0000-my-feature.md`, complete it, and submit a Pull Request against this repository.

### Tests, Documentation, Miscellaneous
-  If you'd like to improve the RFC process documentation, fix typos, or make any other change, we would be happy to hear about it!
   -  If it's a trivial change, go ahead and [send a Pull Request](#creating-a-pull-request) with the changes you have in mind.
   -  If not, [open an Issue](https://github.com/mulesoft/data-weave-rfc/issues/new) to discuss the idea first.

# Contribution Checklist

- [x] Clean, well written proposals
- [x] Commits should be atomic and messages must be descriptive. Related issues should be mentioned by Issue number.
- [x] The RFC must at a minimum: motivate the need for the change, clearly explain the technical details, highlight potential impacts, and consider alternative solutions.
- [x] Reviews
  - Changes must be approved via peer code review

# Creating a Pull Request

1. **Ensure the bug/feature was not already reported** by searching on GitHub under Issues. If none exists, create a new issue so that other contributors can keep track of what you are trying to add/fix and offer suggestions (or let you know if there is already an effort in progress).
2. **Fork** the repo to your own account.
3. **Copy** `0000-template.md` to `text/0000-my-feature.md` for RFC proposals, or create a new branch for other changes.
4. **Commit** changes to your own branch.
5. **Push** your work back up to your fork.
6. **Submit** a Pull Request against the `master` branch and refer to the issue(s) you are addressing. Try not to pollute your pull request with unintended changes. Keep it simple and small.
7. **Sign** the Salesforce CLA (you will be prompted to do so when submitting the Pull Request)

> **NOTE**: Be sure to [sync your fork](https://help.github.com/articles/syncing-a-fork/) before making a pull request.

# Contributor License Agreement ("CLA")
In order to accept your pull request, we need you to submit a CLA. You only need
to do this once to work on any of Salesforce's open source projects.

Complete your CLA here: <https://cla.salesforce.com/sign-cla>

# Issues
We use GitHub issues to track public bugs. Please ensure your description is
clear and has sufficient instructions to be able to reproduce the issue.

# Code of Conduct
Please follow our [Code of Conduct](CODE_OF_CONDUCT.md).

# License
By contributing your code, you agree to license your contribution under the terms of our project [LICENSE](LICENSE.txt) and to sign the [Salesforce CLA](https://cla.salesforce.com/sign-cla)
