# About
I really like the idea of the whole [commitizen](http://commitizen.github.io/cz-cli/)
 or the [conventional commits](https://www.conventionalcommits.org)
 conventions but I wanted to modify prefixes and add better notes.

The real goal is to avoid that kind of messages: http://whatthecommit.com 😇


# Prefixes
I do like bracketed 3 letters capitalized prefixes. A good part of them are
adapted from the original
[conventional-commit-types](https://github.com/commitizen/conventional-commit-types/blob/master/index.json)
repo:

```
* [ADD] → ADD: When the project welcome new files

* [BLD] → BUILD: Changes that affect the build system or external dependencies
  (example scopes: gulp, broccoli, npm)

* [BTF] → BEAUTIFULLAGE: (aka style) Changes that do not affect the meaning of
  the code (white-space, formatting, missing semi-colons, etc)

* [C.I] → CONTINUOUS INTEGRATION: Changes to the CI configuration files and
  scripts

* [DOC] → DOCUMENTATION: Documentation only changes

* [FIX] → FIXE: A bug fix

* [FT.] → FEATURE: A new feature

* [HOC] → HOUSE CLEANING: Changes that make the repository more clean (wiping,
  cleaning, mopping)

* [IGN] → IGNORE: When adding a .gitignore file

* [OTH] → OTHER: Other changes that don't modify src or test files

* [PRF] → PERFORMANCE: A code change that improves performance

* [RFA] → REFACTOR: A code change that neither fixes a bug nor adds a feature

* [RVT] → REVERT: Reverts a previous commit

* [STY] → STYLE: Changes that mainly change the style, look and feel or visual
  appearance

* [TST] → TEST: Adding missing tests or correcting existing tests

* [TYP] → TYPO: An error (as of spelling) in typed or typeset material

* [VER] → VERSION: Bump version

* [WIP] → WORK IN PROGRESS: e.g. in case of fire
```

Please note they are sorted by prefixes in alphabetical order. 

# Notes on commits messages

* https://git.kernel.org/pub/scm/git/git.git/tree/Documentation/SubmittingPatches


1. If applied, this commit will…
1. Summarize changes in around 50 characters or less
1. Explain why this change is being made
1. Provide links to any relevant tickets, articles or other resources
1. If you use an issue tracker, put references to them at the bottom, like this:
   - Resolves: #123
   - See also: #456, #789

# Notes
* https://chris.beams.io/posts/git-commit/#seven-rules
* git config --global commit.template "~/dotfiles/commit-msg-template"
* https://dev.to/shreyasminocha/how-i-do-my-git-commits-34d
* https://dev.to/gauravchaddha1996/what-i-learned-this-month-2nbi
