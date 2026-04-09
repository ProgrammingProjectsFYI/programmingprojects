# Programming Projects

This repository is the source for the website [programmingprojects.fyi](https://programmingprojects.fyi/). It aims to be a one stop shop for programmers and would be programmers to find project ideas.

**Why?** Because the best way to learn to program is to program!

---

## Development

This site is built with [Hugo](https://gohugo.io/) using the [PaperMod](https://github.com/adxoph/hugo-PaperMod) theme.

### Prerequisites

- [Git](https://git-scm.com/)
- [Hugo](https://gohugo.io/installation/) (extended edition recommended)

### Getting started

Clone the repository and initialise the theme submodule:

```bash
git clone https://github.com/ProgrammingProjectsFYI/programmingprojects.git
cd programmingprojects
git submodule update --init --recursive
```

### Running the development server

```bash
hugo server -D
```

This starts a local development server at `http://localhost:1313/` with live reload. The `-D` flag includes draft posts.

### Adding a new project

Create a new post in `content/posts/`:

```bash
hugo new posts/my-project.md
```

Then edit the generated file to add a title, description, tags, categories, and content. See existing posts for the expected format.

## Contribute

If you would like to contribute, please see the [contribution guidelines](/CONTRIBUTING.md) and [code of conduct](/CODE_OF_CONDUCT.md).

## License
For copyright and license information please see the [license file](/LICENSE).
