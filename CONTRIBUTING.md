# How to contribute
:+1::tada: First off, thanks for taking the time to contribute! :tada::+1:

The following is a set of guidelines for contributing to the Flexberry projects, which are hosted in the [Flexberry Organization](https://github.com/Flexberry) on GitHub. Please take a moment to review this document in order to make the contribution process easy and effective for everyone involved.

## GIT

### Commit Message Format
There are a few basic rules that makes Git commit messages more readable on the terminal and GitHub. The most important rule is use the first line as a summary and to keep it short.

According to [Pro Git: Chapter 5.2](http://progit.org/book/ch5-2.html#Commit-Guidelines) we use this template:

    Short (50 chars or less) summary of changes

    More detailed explanatory text, if necessary.  Wrap it to about 72
    characters or so.  In some contexts, the first line is treated as the
    subject of an email and the rest of the text as the body.  The blank
    line separating the summary from the body is critical (unless you omit
    the body entirely); tools like rebase can get confused if you run the
    two together.

    Further paragraphs come after blank lines.

    - Bullet points are okay, too

    - Typically a hyphen or asterisk is used for the bullet, preceded by a
      single space, with blank lines in between, but conventions vary here

- Write the summary line in the imperative present tense: "Fix", "Add" instead of "Fixed", "Added" or "Adding".
- Don't end the summary line with a period - it's a title and titles don't end with a period.

### Branching
We want to keep our commit histories clean where possible.
- master / develop / feature-<name> / hotfixes / release-<version> for branches.
- merging with `--no-ff` option;
- remember about `git rebase`;

## Pull Requests
- When you send a pull request, please send it to the `develop` branch.
- Give a short description in the pull request what you're doing and why.

## Code Review
From the beginning, we want to maintain very high level of code quality in our projects. That's why we use [Atlassian Crucible](https://www.atlassian.com/software/crucible) for reviewing our code.

Feel free to [participate](http://cr.flexberry.net/)!

## Coding Guidelines
- Try to [stick](http://thecodelesscode.com/case/94) to the existing coding style.
- Use `.editorconfig` file to ensure consistent line-endings, tabs/spaces, etc., if it provided with the repository (see [EditorConfig](http://editorconfig.org) for details).
- Make sure you have added the necessary tests for your changes.

### Javascript Styleguide
- Please follow the rules contained in [Flexberry/javascript-style-guide](https://github.com/Flexberry/javascript-style-guide). These rules are partially covered with the `.jshintrc` file in a repository root.
- All public API methods must be documented with [jsdoc](http://usejsdoc.org).

### CSharp Styleguide
- Make sure your changes comply to our [StyleCop](https://stylecop.codeplex.com) rules, which are defined in the Settings.Stylecop file in a repository root.
