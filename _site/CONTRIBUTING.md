Adapted and created based on guidance provided by [mozillascience.github.io](https://mozillascience.github.io/working-open-workshop/)

Some content was also adopted from the [Atom contributing guide](https://github.com/atom/atom/blob/master/CONTRIBUTING.md#i-dont-want-to-read-this-whole-thing-i-just-have-a-question)

# Welcome CivicFolio Contributors!

We’re so excited that you’re ready to contribute and thank you for taking the time to contribute!!

The purpose of this guide is provide a brief outline of what you would need to contribute to CivicFolio and related assets, content, and packages, which are currently hosted under the GovFresh on GitHub. This document is intended to serve as a set of guidelines, not rules. Use your best judgement, and feel free to propose changes to this document in a pull request. 

If you haven’t already, please check out the repository README to get a project overview.


# **Code of Conduct**

This project and everyone participating in it is governed by the Code of Conduct. By participating, you are expected to uphold this code. Please report unacceptable behavior to [civicfolio@govfresh.com](mailto:civicfolio@govfresh.com)

# I don’t want to read this whole thing I just have a question!!!

> Note: Please don’t file an issue to ask a question. Instead opt for the resources blow.
> 

Our official discussion board is where all community members can ask questions or share advice. We recommend searching through the board first to see if a similar question as been asked in a previous thread before creating a new discussion thread. 

- CivicFolio [Discussion](https://github.com/govfresh/civicfolio/discussions) board

# How can I contribute?

## Reporting bugs

This section guides you through submitting a bug report for CivicFolio. Following these guidelines helps maintainers and the community understand your report 📝, reproduce the behavior 💻 💻, and find related reports 🔎.

> Note: If you find a Closed issue that seems like it is the same thing that you're experiencing, open a new issue and include a link to the original issue in the body of your new one.
> 

### **Before Submitting A Bug Report**

- **Check the discussions** for a list of common questions and problems.
- **Perform a cursory search** to see if the problem has already been reported. If it has **and the issue is still open**, add a comment to the existing issue instead of opening a new one.

### **How Do I Submit A (Good) Bug Report?**

Bugs are tracked as GitHub issues. Create an issue in this repository and provide the following information by filling in the template.

Explain the problem and include additional details to help maintainers reproduce the problem:

- **Use a clear and descriptive title** for the issue to identify the problem.
- **Describe the exact steps which reproduce the problem** in as many details as possible. For example, start by explaining how tried to add an extra page to the navigation page. When listing steps, **don't just say what you did, but explain how you did it**. For example, if you moved the cursor to the end of a line, explain if you used the mouse, or a keyboard shortcut, and if so which one?
- **Provide specific examples to demonstrate the steps**. Include links to files or GitHub projects, or copy/pasteable snippets, which you use in those examples. If you're providing snippets in the issue, use [Markdown code blocks](https://help.github.com/articles/markdown-basics/#multiple-lines).
- **Describe the behavior you observed after following the steps** and point out what exactly is the problem with that behavior.
- **Explain which behavior you expected to see instead and why.**
- **Include screenshots and animated GIFs** which show you following the described steps and clearly demonstrate the problem. If you use the keyboard while following the steps, **record the GIF/Video explainer with [Loom](https://www.loom.com/blog/loom-github-chrome-extension-integration)**.
- **If the problem wasn't triggered by a specific action**, describe what you were doing before the problem happened and share more information using the guidelines below.

Provide more context by answering these questions:

- **Did the problem start happening recently** (e.g. after updating to a new version of CivicFolio) or was this always a problem?
- If the problem started happening recently, **can you reproduce the problem in an older version of CivicFolio?** What's the most recent version in which the problem doesn't happen? You can download older versions of Atom from the releases page.

### **Suggesting Enhancements**

This section guides you through submitting an enhancement suggestion for Atom, including completely new features and minor improvements to existing functionality. Following these guidelines helps maintainers and the community understand your suggestion 📝 and find related suggestions 🔎.

When you are creating an enhancement suggestion, please include as many details as possible. Fill in the template, including the steps that you imagine you would take if the feature you're requesting existed.

### **Before Submitting An Enhancement Suggestion**

- **Perform a cursory search** to see if the enhancement has already been suggested. If it has, add a comment to the existing issue instead of opening a new one.

### **How Do I Submit A (Good) Enhancement Suggestion?**

Enhancement suggestions are tracked as [GitHub issues](https://guides.github.com/features/issues/). After you've determined [which repository](https://github.com/atom/atom/blob/master/CONTRIBUTING.md#atom-and-packages) your enhancement suggestion is related to, create an issue on that repository and provide the following information:

- **Use a clear and descriptive title** for the issue to identify the suggestion.
- **Provide a step-by-step description of the suggested enhancement** in as many details as possible.
- **Provide specific examples to demonstrate the steps**. Include copy/pasteable snippets which you use in those examples, as [Markdown code blocks](https://help.github.com/articles/markdown-basics/#multiple-lines).
- **Describe the current behavior** and **explain which behavior you expected to see instead** and why.
- **Include screenshots and animated GIFs** which help you demonstrate the steps or point out the part of Civic Folio the suggestion is related to. Tools like Loom are recommended.
- **Explain why this enhancement would be useful** to most Civic Folio users
- **List some other  applications where this enhancement exists.**

### **Pull Requests**

The process described here has several goals:

- Maintain Civic Folio’s
- Fix problems that are important to users
- Engage the community in working toward the best possible Civic Folio
- Enable a sustainable system for Civic Folio’s maintainers to review contributions

Please follow these steps to have your contribution considered by the maintainers:

1. Follow all instructions in the template
2. Follow the styleguides
3. After you submit your pull request, verify that all [status checks](https://help.github.com/articles/about-status-checks/) are passing
    - What if the status checks are failing?

While the prerequisites above must be satisfied prior to having your pull request reviewed, the reviewer(s) may ask you to complete additional design work, tests, or other changes before your pull request can be ultimately accepted.

## **Styleguides**

### **Git Commit Messages**

- Use the present tense ("Add feature" not "Added feature")
- Use the imperative mood ("Move cursor to..." not "Moves cursor to...")
- Limit the first line to 72 characters or less
- Reference issues and pull requests liberally after the first line
- When only changing documentation, include `[ci skip]` in the commit title
- Consider starting the commit message with an applicable emoji:
    - 🎨 `:art:` when improving the format/structure of the code
    - 🐎 `:racehorse:` when improving performance
    - 📝 `:memo:` when writing docs
    - 🐛 `:bug:` when fixing a bug
    - 🔥 `:fire:` when removing code or files
    - ✅ `:white_check_mark:` when adding tests
