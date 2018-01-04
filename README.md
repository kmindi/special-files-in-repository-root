# Common *special files* found in the root directory of a repository

Description for and list of popular special files like README/CHANGELOG/LICENSE and others.

# README-like

## ReadMe `README.md` `README`

The ReadMe is usually the first document people will see of your project. Depending on your project it should give a **short** introduction and usage/build examples. It **should only contain the information you expect users to read**. It is usually possible to link to other documentation files using the **markdown syntax** which gets rendered as html by popular repository hosting platforms.

[awesome-readme](https://github.com/matiassingers/awesome-readme): List of **good/awesome Readmes** and links to *How to write a good ReadMe*.

## Change Log `CHANGELOG.md` `CHANGELOG` (`CHANGES`/`HISTORY`/`NEWS`/`RELEASES`)

The change log **lists all important changes between different, even unreleased, versions of your project**. It should not contain every commit message, as that information may be too detailed and can be fetched from the version control system too.

- [keepachangelog.com](http://keepachangelog.com/): How to keep a changelog 

## Contribution Guidelines `CONTRIBUTING.md` `CONTRIBUTING`

In the open source world many people can easily contribute to your project. If you want to set certain guidelines that the contributors should respect they usually are found in this file. 

On [GitHub](https://github.com/blog/1184-contributing-guidelines) this file will be linked on the *New Issue* and *New Pull Request* pages, to increase contributor awareness for the guidelines.

## License `LICENSE.md` `LICENSE` (`COPYING`)

It is important to explicitly state the license (or licenses) under which you publish your project. If you don't the default copyright laws apply. 

If you have no experience in choosing a license you should consider contacting a lawyer, especially if your project contains other (licensed) work, (future) legal trademarks and other intellectual property that needs careful protection. There is also an online service that helps you choose a license: [choosealicense.com](http://choosealicense.com/)

It is common that the **name of the license is also mentioned in the ReadMe** and links to the full text which is found in this `LICENSE` file.

## List of Contributors `CONTRIBUTORS.md` `CONTRIBUTORS` (see `AUTHORS`)

Special list of people and/or organizations that have contributed to your project. Depending on your project and your contribution guidelines, 
- contributors may decide themselves if they should appear in that list, 
- they have to appear (by adding their name themselve) in that list or 
- that only substantial contributions will be mentioned in that file by a responsible person of your project management team or you (see `AUTHORS` for this purpose)

## List of copyright holders/authors `AUTHORS.md` `AUTHORS`  (see `CONTRIBUTORS`)

Legally relevant contributors/authors of the project should be listed in this file.

According to the GNU ["Only the contributions that are legally significant for copyright purposes (see Legally Significant) need to be listed. Small contributions, bug reports, ideas, etc., can be omitted."](https://www.gnu.org/prep/maintain/html_node/Recording-Contributors.html)


## Acknowledgments `ACKNOWLEDGMENTS.md` `ACKNOWLEDGMENTS`

Mentioning other work, their copyright notice and used license can be done in `ACKNOWLEDGMENTS.md`.

If your project builds upon other software, parts of software (libraries) or simply work owned by someone else, it depends on their license how you have to acknowledge its usage in your project. Usually you have to state their copyright notice and license used somewhere in your project.

# Other

## Code of Conduct `CODE_OF_CONDUCT.md`

A more general and broad form of rules (than the ones in `CONTRIBUTING`) that people interacting with your project have to obey.
See [contributor-covenant.org](http://contributor-covenant.org/) for an example.

# Platform-dependent features/templates

## *New Issue* `ISSUE_TEMPLATE`

- [GitHub Blog Post](https://github.com/blog/2111-issue-and-pull-request-templates)

## *New Pull Request* `PULL_REQUEST_TEMPLATE`

- [GitHub Blog Post](https://github.com/blog/2111-issue-and-pull-request-templates)

## *Code Owners* `CODEOWNERS`

A CODEOWNERS file defines users who are resposible for code.

[On GitHub](https://help.github.com/articles/about-codeowners/), these users are automatically requested to review pull requests that modify code that they own.

# Frequently Asked Questions
## When should I name the file ending in **.md**?

In general only files that end in `.md` will be renderd using markdown. So whenever you want to use markdown features that should be rendered visually (like headings/sections/lists/clickable links/bold/italic/...) you should use `.md`.
