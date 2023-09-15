# Contributing to BerylliumOS

## Table of contents

- [Code of conduct](#code-of-conduct)
- [Issues](#issues)
    - [Bug report](#bug-report)
    - [Feature request](#feature-request)
- [Pull requests](#pull-requests)
    - [Document your code](#document-your-code)
    - [Testing](#testing)
    - [Coding standards](#coding-standards)
    - [Commit message](#commit-message)

Thank you for your interest in the Beryllium Operating System. There are various things you can do to directly contribute to the code base of the operating system. This document provides an overview for the guidelines to follow.

## Code of conduct

Please keep in mind that we have a [code of conduct](CODE_OF_CONDUCT) that our community members must follow.

## Issues

We use GitHub's [issue tracker](https://github.com/berylliumos/BerylliumOS/issues) to maintain bug reports, feature requests, and pull requests.

### Bug report

If you run into a bug, you can create a [bug report](https:/github.com/berylliumos/BerylliumOS/issues/new?assignees=&labels=&template=bug_report.yml). The bug report should be clear, and the bug should be reproducable on other systems. Make sure that the bug you found has not been previously opened as an issue.

### Feature request

You can create a [feature request](https://github.com/berylliumos/BerylliumOS/issues/new?assignees=&labels=&template=feature_request.yml) if you have a feature you would like to suggest. Be as detailed as possible, and consider the feature relevancy and practicality.

## Pull requests

To directly contribute to the codebase, you need to make a pull request which will be reviewed by the repository owner. Before making a pull request, make sure that the repository maintainers are aware of the change being performed, if it is a major update. The best way to do this is to use a [feature request](#feature-request).

### Document your code

For a pull request to be accepted, it must be completely clear what the features are meant to do, as well as annotating the source code. There are Doxygen comments in the C/C++ code which should be added in a similar way as they appear. 

### Testing

The changes must be thoroughly tested before merging into the main branch. A pull request is only approved if:

1. New unit tests have been written for each new feature.
2. Old unit tests can be performed successfully.

### Coding standards

Please review the [coding standards](CODING_STANDARDS.md) to make sure your code follows the correct style and formatting. Making exceptions from the coding standard is done by the programmer's own discretion.

To make sure coding standards are followed, we use clang-tidy and clang-format, which should process the C/C++ source files.

### Commit message

The git commit message should be correctly formatted and descriptive. The following rules should be followed:

1. The message has a short title, which is the first line of the message, followed by a line break and then the extended description.
2. The short title should be under 72 characters.
3. The extended description should be wrapped at 80 characters.
