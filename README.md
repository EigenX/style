# Eigen X: Coding Standards and Style Guides
A guide for preferred coding standards and styles at Eigen X.

## Contents

1. [Agile Developer Mindset](#agile)
1. [Deployment Guidelines](#deployment)
1. [Versioning and Source Control Guidelines](#versioning)
1. [Style Guide](#style)
1. [IDE's and Code Editors](#ide)
1. [Testing Guidelines](#testing)

# Agile

Agile development is not a process, it is a mindset. It's important to note that developers should use their discretion when implementing this guide based on the individual project. For small projects it is prudent to avoid unnecessary overhead, for large projects this repo may need to be forked and adapted to that project as a deliverable.

> Individuals and interactions over processes and tools

Favor collaboration and code reviews on Pull Requests over mandating ide's and excessive tooling.

> Working software over comprehensive documentation

Favor meeting requirements over excessive

> Customer collaboration over contract negotiation

Our goal is to provide the most value within the scope of our projects. We need to be in constant contact with our customers to focus on what is important to them.

> Responding to change over following a plan

Tech changes quickly, we should use tech that is appropriate for the project at hand. Favor good tech over old habits.

* Quotes from the [Agile Manifesto](http://agilemanifesto.org/)*


# Versioning
In all projects there needs to be a reliable method of source/version control. [git](https://git-scm.com/) is the preferred tool.

## General Branching Strategy

[Branching Strategy Overview](style/assets/branching.png)

## Git Repo Hosting
One of the following should be used:
- GitHub
- BitBucket

# Deployment
- single source of truth
- based on tooling and client requiremnts there are a couple of strategies.
- Tuan's post
# Style
# IDE
# Testing

## Languages and Frameworks - Tools and Style Guides

1. `Apex`
    - **Style Guide:** [PMD Apex Rule Sets](https://pmd.github.io/pmd-5.5.7/pmd-apex/rules/index.html). If applicable, `Java` conventions should be followed where there is no guidance specific to `Apex`.
    - **Code Analyzer:**
        - [PMD](https://pmd.github.io/) can be used with [apex](https://github.com/pmd/pmd/tree/master/pmd-apex).
1. `CSS/Sass`
    - **Style Guide:** [Airbnb CSS / Sass Styleguide](https://github.com/airbnb/css)
    - **Linters:**
        - Use [sass-lint](https://github.com/sasstools/sass-lint) with the [airbnb config](https://github.com/airbnb/css)
1. `HTML`
    - You should be writing Valid HTML according to the [living standard](https://html.spec.whatwg.org/)
    - **Validators:** 
        - [W3 HTML Validation](https://validator.w3.org/nu/) you can also use [a command-line version of this](https://github.com/zrrrzzt/html-validator-cli)
1. `Java`
    - **Style Guide:** [Google Java Style Guide](https://google.github.io/styleguide/javaguide.html)
    - **Dev Tools:**
        - [PMD]
1. `Javascript` - 
1. `Python`
    - **Style Guide:** [PEP 8](https://www.python.org/dev/peps/pep-0008/)
1. `Salesforce Lightning` -
1. `VisualForce`
    - **Style Guide:** [PMD Apex Rule Sets](https://pmd.github.io/pmd-5.5.7/pmd-apex/rules/index.html). If applicable, `Javascript/HTML/CSS` conventions should be followed where there is no guidance specific to `VisualForce`.
    - **Dev Tools:** [PMD](https://pmd.github.io/) can be used with [VisualForce](https://github.com/pmd/pmd/tree/master/pmd-visualforce).
    
1. https://google.github.io/styleguide/shell.xml

## General Practices for Adoption of this guide
1. Favor people over Process - Code Reviews > Process
1. Linters are good, but should not get in the way of development.
1. Code reviews should catch style/standards errors
1. Editor Independent
    
    
## Preferred Editors and IDEs
While there is some advantages to standardizing a team on an editor.
We leave that decision up to the individual developer, coding standard/style guides should be editor/ide independent.

Our devs like to use the following:

- Atom
- Sublime
- VS Code
- Vim
- Intellij
- Eclipse

Related: [What Editor Do you Use?](https://medium.com/humans-create-software/what-editor-do-you-use-fun-fun-function-31-cab6d2e61a25)

# Contributing
There are two main branches:
1. `master` - a release branch that should be considered active and in use.
2. `proposal` - a staging branch for all proposed changes.

If you have would like to contribute or have a suggestion for this style guide, please submit them by making a pull request into the `proposal` branch.
