# Contributing to Qalculate!

:+1::tada: First off, thanks for taking the time to contribute! :tada::+1:

The following is a set of guidelines for contributing to Qalculate! and its packaging, which are hosted in [these GitHub repositories][1]. These are mostly guidelines, not rules. Use your best judgment, and feel free to propose changes to this document in a pull request.

## Code of Conduct

This project and everyone participating in it is governed by the [Contributor Covenant Code of Conduct][2]. By participating, you are expected to uphold this code. Please report unacceptable behavior to [hanna.knutsson@protonmail.com][3]

## How Can I Contribute?

### Reporting Bugs

This section guides you through submitting a bug report for Qalculate. Following these guidelines helps developers and the community understand your report :pencil:, reproduce the behavior :computer: :computer:, and find related reports :mag_right:.

Before creating bug reports, please check [this list][4] as you might find out that you don't need to create one. When you are creating a bug report, please [include as many details as possible][5]. Fill out [the required template][6], the information it asks for helps us resolve issues faster.

**Note:** If you find a **Closed** issue that seems like it is the same thing that you're experiencing, open a new issue and include a link to the original issue in the body of your new one.

#### Before Submitting A Bug Report

* **Perform a [cursory search][7]** to see if the problem has already been reported. If it has **and the issue is still open**, add a comment to the existing issue instead of opening a new one.

#### How Do I Submit A (Good) Bug Report?

Bugs are tracked as [GitHub issues][8], not through the bug tracker of any package repository, so this is where they belong. If you've encountered behavior by qalc/Qalculate! that you can't explain and have done your best to troubleshoot it using Google, create an issue and provide the following information by filling in [the template][6].

Explain the problem and include additional details to help developers reproduce the problem:

* What: 
  * **Use a clear and descriptive title** for the issue to identify the problem.
* Where:
  * **Describe the exact steps which reproduce the problem** in as many details as possible. For example, start by explaining how you started qalc/Qalculate! (e.g. which command exactly you used in the terminal or which launcher you used in your GUI). When listing steps, **don't just say what you did, but explain how you did it**.
* How:
  * **Provide specific examples to demonstrate the steps**. Include all the calculations/commands you performed leading up to the problem, not just the last step that generated the error. If that proves to be lengthy, use [Markdown code blocks][9].
* When:
  * **Describe the behavior you observed after following the steps** and point out what exactly is the problem with that behavior.
* Why:
  * **Explain which behavior you expected to see instead and why.**
* **If you're reporting that Qalculate! crashed**, include a stack trace in the issue in a [code block][9], a [file attachment][10], or put it in a [Gist][11] and provide link to that gist in the body of the issue.
* **If the problem is related to performance or memory**, include a [perf CPU profile capture][12] with your report.

Provide more context by answering these questions:

* **Did the problem start happening recently** (e.g. after updating to a new version of your distribution, desktop environment or Qalculate!) or was this always a problem?
* **Can you reliably reproduce the issue?** If not, provide details about how often the problem happens and under which conditions it normally happens.

Include details about your configuration and environment:

* **Which version of Qalculate! do you have installed?** You can confirm the exact version by opening a terminal and issuing the command `qalc -v` for errors that happened on the command line or `qalculate-gtk` for errors that happened in the GUI, and the commands `whereis qalc` and `whereis qalculate-gtk` will inform you of all copies of Qalculate that are present in your $PATH directories (if there's more than one, definitely mention that).
* **What's the name and version of the OS you're using**?
* **Are you running Qalculate in a virtual machine?** If so, which VM software are you using and which operating systems and versions are used for the host and the guest?

### Suggesting Enhancements

This section guides you through submitting an enhancement suggestion for Qalculate!, including completely new features and minor improvements to existing functionality. Following these guidelines helps maintainers and the community understand your suggestion :pencil: and find related suggestions :mag_right:.

Before creating enhancement suggestions, please check [this list][13] as you might find out that you don't need to create one. When you are creating an enhancement suggestion, please [include as many details as possible][14]. Fill in [the template][6], including the steps that you imagine you would take if the feature you're requesting existed.

#### Before Submitting An Enhancement Suggestion

* **Perform a [cursory search][7]** to see if the enhancement has already been suggested. If it has, add a comment to the existing issue instead of opening a new one.

#### How Do I Submit A (Good) Enhancement Suggestion?

Enhancement suggestions are tracked as [GitHub issues][8]. After you've determined that your enhancement suggestion hasn't already been made/discussed, create an issue and provide the following information:

* **Use a clear and descriptive title** for the issue to identify the suggestion.
* **Provide a step-by-step description of how it would operate for users** in as many details as possible.
* **Provide specific examples to demonstrate what it would produce from a few different inputs**. Include snippets which you use in those examples, as [code blocks][9].
* **Describe the best result you can get with the current version** and **explain what you were trying to accomplish and couldn't** so we can gauge how many users might benefit from doing the same.
* **Include screenshots and animated GIFs** which help you demonstrate the steps or point out the part of Qalculate! which the suggestion is related to. You can use [this tool][15] or [this one][16] on Linux.
* **Specify the name and version of the OS you're using.**

### Pull Requests

Please follow these steps to have your contribution considered by the maintainers:

* Follow all instructions in [the template][17]
* Follow the [styleguides][18]

While the prerequisites above must be satisfied prior to having your pull request reviewed, the reviewer(s) may ask you to complete additional work, tests, or other changes before your pull request can be ultimately accepted.

## Styleguides

### Git Commit Messages

* Use the present tense ("Add feature" not "Added feature")
* Use the imperative mood ("Move cursor to..." not "Moves cursor to...")
* Limit the first line to 72 characters or less
* Reference issues and pull requests liberally after the first line
* Consider starting the commit message with an applicable emoji:
    * :art: `:art:` when improving the format/structure of the code
    * :racehorse: `:racehorse:` when improving performance
    * :non-potable_water: `:non-potable_water:` when plugging memory leaks
    * :memo: `:memo:` when writing docs
    * :bug: `:bug:` when fixing a bug
    * :white_check_mark: `:white_check_mark:` when adding tests
    * :lock: `:lock:` when dealing with security

[1]: https://github.com/Qalculate
[2]: CODE_OF_CONDUCT.md
[3]: mailto:hanna.knutsson@protonmail.com
[4]: #before-submitting-a-bug-report
[5]: #how-do-i-submit-a-good-bug-report
[6]: .github/ISSUE_TEMPLATE/ISSUE_TEMPLATE.md
[7]: https://github.com/Qalculate/libqalculate/issues?q=is%3Aissue
[8]: https://guides.github.com/features/issues/
[9]: https://help.github.com/articles/markdown-basics/#multiple-lines
[10]: https://help.github.com/articles/file-attachments-on-issues-and-pull-requests/
[11]: https://gist.github.com/
[12]: http://www.brendangregg.com/perf.html
[13]: #before-submitting-an-enhancement-suggestion
[14]: #how-do-i-submit-a-good-enhancement-suggestion
[15]: https://github.com/phw/peek
[16]: https://www.maartenbaert.be/simplescreenrecorder/
[17]: .github/PULL_REQUEST_TEMPLATE/PULL_REQUEST_TEMPLATE.md
[18]: #styleguides
