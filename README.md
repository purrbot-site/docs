[purr]: https://purrbot.site/github

[formatting help]: https://docs.purrbot.site/contribute/formatting-help

[boxes]: https://squidfunk.github.io/mkdocs-material/extensions/admonition/#admonition
[MkDocs]: https://www.mkdocs.org

[squidfunk]: https://github.com/squidfunk
[facelessuser]: https://github.com/facelessuser

[pymdown]: https://github.com/facelessuser/pymdown-extensions/

[netlifyImg]: https://www.netlify.com/img/press/logos/full-logo-light.svg
[netlify]: https://www.netlify.com

# Docs
![forthebadge](https://forthebadge.com/images/badges/made-with-markdown.svg)

This repository is home of the content found on https://docs.purrbot.site  
It currently houses the API-documentation for the various endpoints under https://purrbot.site/api and the official wiki of [\*Purr*][purr].

## Contributions
Any contributions to update and improve the wiki, as well as the API-documentation are welcome, but please follow those basic guidelines:

### Only edit the content in the docs-folder and mkdocs.yml
The content found under the "docs" folder is the place to edit files in. Each file is saved as a markdown (.md) file.  
Only the docs folder (and the mkdocs.yml file if new pages where added or got removed) should be altered.  
At no point should you touch the content of any other file outside the docs-directory.  
Any pull request which alters any file other than the above mentioned ones will be denied.

### Markdown formatting
We use [MkDocs] to turn Markdown files into static HTML pages.  
MkDocs *mostly* follows the basic markdown formatting with some minor exceptions and alterations.  
Please take a look at the [formatting help] page for important information about differences compared to the normal markdown syntax.

## Builds
We use [Netlify] to generate and deploy previews of Pull requests in order to see, if the PR in question would break something in terms of look and design.

[![netlifyImg]][netlify]

## Credits
A big thank you goes to the following people/groups:
- [MkDocs] for providing the software, to generate documentation.
- [squidfunk] for the MkDocs Material Theme.
- [facelessuser] for the [PyMdown Extensions][pymdown]
