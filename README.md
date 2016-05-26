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

## List of Contributors `CONTRIBUTORS.md` `CONTRIBUTORS`

## List of copyright holders/authors `AUTHORS.md` `AUTHORS`

# Other

## Code of Conduct `CODE_OF_CONDUCT.md`

A more general and broad form of rules (than the ones in `CONTRIBUTING`) that people interacting with your project have to obey.
See [contributor-covenant.org](http://contributor-covenant.org/) for an example.

# Platform-dependent features/templates

## *New Issue* `ISSUE_TEMPLATE`

- [GitHub Blog Post](https://github.com/blog/2111-issue-and-pull-request-templates)

## *New Pull Request* `NEW_PULL_REQUEST`

- [GitHub Blog Post](https://github.com/blog/2111-issue-and-pull-request-templates)

# Frequently Asked Questions
## When should I name the file ending in **.md**?

In general only files that end in `.md` will be renderd using markdown. So whenever you want to use markdown features that should be rendered visually (like headings/sections/lists/clickable links/bold/italic/...) you should use `.md`.
