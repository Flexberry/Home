# How to contribute
:+1::tada: First off, thanks for taking the time to contribute! :tada::+1:

The following is a set of guidelines for contributing to the Flexberry projects, which are hosted in the [Flexberry Organization](https://github.com/Flexberry) on GitHub. Please take a moment to review this document in order to make the contribution process easy and effective for everyone involved.

## GIT

### Message Format
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

### Branching
We want to keep our commit histories clean where possible.
- master / develop / feature-<name> / hotfixes / release-<version> for branches.
- merging with `--no-ff` option;
- remember about `git rebase`;
