# stride-template

You can [use this repository template to create new repositories](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template). If you have an existing repository you want to bring into Github, please make sure you maintain a similar structure and procedures.

## Structure

### README.md

You can use the sections in this template file. Please describe briefly what this project is for and how someone else can run it in a new environment.

### .gitignore

Build artifacts, local settings, and configuration secrets should not get into the repository.

## Process

### Branching

Here is an [interesting article](https://nvie.com/posts/a-successful-git-branching-model/) about proper git branching practices. It usually depends on the project and how many collaborators are working on it, but we generally commit to:

- **main**: Contains the code of the most recent release that runs in production. Keep it production-ready at all times!
- **dev**: The development branch where we collect features until we make a release. Must be executable at all times.
- **feature-YYMMDD-xxx**: Feature branches for the development of new features (gets merged via PR into dev).
- **hotfix-YYMMDD-xxx**: Hotfix branches for the development of hotfixes (gets merged via PR into the main branch).
- Apply semantic versioning and tagging for commits to main (vX.X.X) ([cheat sheet](https://devhints.io/semver))
   - Major: All changes to the code which break backward compatibility and dependencies.
   - Minor: Significant code changes or added features.
   - Patch: Small changes and bug fixes that are fully backward compatible.

### CI/CD

Leverage automation to save time on repetitive tasks and make it easy to maintain standards in a team. Make use of tags for releases and trigger automatic tests and builds. A minimal workflow for automatic releases is included in this template and is ready to use out of the box.

Happy coding! :)



# stride-xxx (template for a README)

Short description of the purpose of the project.

## Getting started

These instructions will get you a copy of the project up and running.

### Prerequisites

Dependencies and necessary steps before installing the code.


### Installaton

How to install the project and get it running.

### Configuration

What configuration options exist and how to use them.

## Run

How to run the project.
