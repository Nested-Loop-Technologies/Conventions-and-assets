<!-- TOC -->
* [General-conventions](#general-conventions)
* [Repository](#repository)
    * [Naming convention](#naming-convention)
    * [Readme](#readme)
    * [License](#license)
* [Publishing project](#publishing-project)
* [General-conventions](#general-conventions-1)
* [Repository](#repository-1)
    * [Naming convention](#naming-convention-1)
    * [Readme structure](#readme-structure)
    * [Version Control](#version-control)
        * [Versioning Guidelines](#versioning-guidelines)
<!-- TOC -->

# General-conventions
This repository contains the general rules and conventions you should follow while making new projects or contributing
to existing ones.

# Repository

## Naming convention

The repositories located in Nested Loop organization may come in all shapes and sizes, and therefore we would like to
have some sort of structure to them. We are using the following structure for the repository name:
`<framework>-<project-name>`. An example of a NextJs project for the community website, would have the following name:
`nextjs-community-website`.

## Readme structure

Every project must have a properly written out Readme.md file containing details like:

1. General introduction to the project
    - What is it about
    - What are the features (e.g., a table using MoSCoW method explaining the features)

2. How to run and compile the project

3. How to contribute to the project

Feel free to add additional items to the readme file, like project directory structure, images, versions, etc.

If you wish to add directory structure, here's an example:

```
markdown-project-example/
├── src/
│   ├── app/
│   │   ├── classes/
│   │   ├── interfaces/
│   │   └── ...
│   ├── assets/
│   └── environments/
└── ...
```

Note the use of `...`. This is used to show the reader that the directory contains files. Projects might have many
boilerplate files and listing all of them does not add anything of value to the structure, therefore omitting them is
preferred.

## Version Control

### Versioning Guidelines

To maintain consistency across projects within Nested Loop organization, follow these versioning guidelines:

1. **Semantic Versioning (SemVer):** Adhere to Semantic Versioning for version numbers: `MAJOR.MINOR.PATCH`.
    - **MAJOR:** Increment for incompatible API changes.
    - **MINOR:** Increment for backward-compatible functionality additions.
    - **PATCH:** Increment for backward-compatible bug fixes.

2. **Version Tagging:** Use version tags to mark significant releases or milestones in the repository.
    - Tag releases following the SemVer format (`vX.Y.Z`) to clearly identify versions.

3. **Release Notes:** Create release notes for each version. Include details about changes, additions, and bug fixes.

4. **Branching Strategy:** Define a branching strategy (e.g., GitFlow, trunk-based development) for managing different
   types of changes.

Example of Semantic Versioning:

Version 1.2.3

1. Major version: introduces significant changes, possibly breaking compatibility.
2. Minor version: introduces new features without breaking existing functionality.
3. Patch version: contains bug fixes or minor updates without altering existing features.
