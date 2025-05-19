<!-- omit from toc -->
# Contributing to mindbuttergold

Welcome! Thank you very much for your interest in contributing. We are grateful for your help in making best practices more tangible and accessible!

mindbuttergold is a public collection of production-quality demonstrations showing modern software and infrastructure best practices. Contributions are open to anyone, as long as they meet the guidelines outlined below.

<!-- omit from toc -->
# Table of Contents

- [Contributing New Ideas](#contributing-new-ideas)
- [Code Contribution Guidelines](#code-contribution-guidelines)
- [Commit Requirements](#commit-requirements)
- [Pull Request Requirements](#pull-request-requirements)
- [Code Contribution Process](#code-contribution-process)


## Contributing New Ideas

If you have a new idea for a best practice demonstration, but there is no relevant existing repository:

- Open a new "Idea" post in the Discussions section.
- If the idea receives at least 4 thumbs up, a maintainer will create a public repository for it (Github doesn't allow community members to create repositories directly). This bar is set high, to help promote engagement and ensure best practices demonstrated are valuable to the community at large.
- Once the repository is created, anyone can open a PR to contribute to it.

## Code Contribution Guidelines

Code should be clear, complete, and fully usable in real-world systems. It should align with mindbuttergold's [Guiding Values](https://github.com/mindbuttergold#guiding-values).

All contributions must include a `README.md` that explains how to use the code, including setup, prerequisites, and supporting references about the best practice demonstrated.

**Do not include:**

- Placeholder or unfinished code
- Code copied from other places with a license that does not permit its use in this project
- Redundant or self-evident code comments
- Emojis or other random AI-generated artifacts unrelated to functionality

Submissions that don't meet these expectations will be closed.

## Commit Requirements

All commits should follow [Conventional Commit standards](https://www.conventionalcommits.org/en/v1.0.0/) to allow us to perform automated semantic versioning. 

Also, please use clear and descriptive commit messages.

## Pull Request Requirements

All PRs must be reviewed and approved by at least **4 total people**. If the PR author is not a maintainer, at least one of the 4 approvals must come from a maintainer.

The number of required approvals is intentionally set high, to ensure the contribution meets an agreed upon high-standard of the community - given that the goal of this project is to model best practices.

Maintainers agree to review PRs that meet the contributing guidelines within 1 week of initial submission - to the best of their ability.

Every PR must include:
- A PR title that follows the same [Conventional Commit standards](https://www.conventionalcommits.org/en/v1.0.0/) as commits, and is clear and descriptive. 
- An explanation / rationale for the best practice(s) being demonstrated.
- Evidence of testing and all functionality working as expected.

## Code Contribution Process

To contribute code to a repository in this project, follow these steps:

**1. Review the [Code Contribution Requirements](#code-contribution-requirements)**

**2. Fork the Repository** 

Go to the GitHub page of the repository and click the **"Fork"** button at the top-right corner. This creates a copy of the repository under your GitHub account. See [About Forks](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/about-forks) for more information.

**3. Clone Your Fork** 
  ```bash
  git clone <FORKED_REPO_URL>
  cd <FORKED_REPO_NAME>
  ```

**4. Add the Original Repository as Remote Upstream**

  ```bash
  git remote add upstream <ORIGINAL_REPO_URL>
  
  git remote -v
  ```

**5. Create a Feature Branch**

**6. Make Your Changes**

**7. Commit Your Changes**

Review the [Commit Requirements](#commit-requirements).

**8. Push Your Branch to Your Fork**

**9. Open a Pull Request in the Original Repo** 

Review the [Pull Request Requirements](#pull-request-requirements).

See [Creating a Pull Request From a Fork](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request-from-a-fork) for more information.

**10. Respond to Feedback**

Make any requested changes or provide supporting rationale for not making changes. Debate is welcome and encouraged, but abide by the [Code of Conduct](./CODE_OF_CONDUCT.md).
