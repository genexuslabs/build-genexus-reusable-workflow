# build-genexus-reusable-workflow

This repository contains a collection of reusable workflows used by different GeneXus components. These workflows aim to streamline and automate various tasks related to GeneXus development, making the development process more efficient and productive.

## Table of Contents

- [Introduction](#introduction)
- [Usage](#usage)
- [Repository Content](#repository-content)
- [Workflows](#workflows)
  - [run-beta-bot](#run-beta-bot)
  - [GeneXus Dependency Sync](#genexus-dependency-sync)
- [Contributing](#contributing)
- [License](#license)

## Introduction

GeneXus is a powerful low-code development platform used to build enterprise applications. It allows developers to create applications for various platforms, such as web, mobile, and desktop, using a single code base. As GeneXus applications can be complex and involve multiple components, it is important to have standardized workflows to ensure consistency and maintainability.

This repository aims to provide a centralized location for storing and sharing reusable workflows that can be used across different GeneXus components. These workflows are designed to automate common tasks and help developers perform their work more efficiently.

## Usage

To utilize the workflows in your GeneXus development process, follow these steps:

1. Navigate to the workflow you want to use in the repository.

2. Read the documentation accompanying the workflow to understand its purpose and usage instructions.

3. Adapt the workflow to fit your specific use case, if required. Modify any necessary parameters or configurations to suit your project's needs.

4. Execute the workflow using your preferred automation tool or directly from the command line, following the provided instructions.

5. Monitor the workflow execution and handle any errors or exceptions that may occur.

## Structure

This repository contains the following folders:

### .github/workflows

The `.github/workflows` folder contains reusable workflows that can be called by workflows in other repositories within the same organization. These workflows are designed to automate specific tasks and can be easily integrated into your own workflow configurations. The documentation within each workflow file provides instructions on how to utilize and customize them for your needs.

### templates

The `templates` folder contains several samples that demonstrate how to use the reusable workflows from other repositories. These templates provide a starting point and guidance on how to configure your workflows to invoke the reusable workflows. You can copy and modify these templates to suit your specific requirements.

## Workflows

### run-beta-bot

The run-beta-bot workflow is used to handle a reserved branch named 'beta'. This workflow automates the process of merging changes from the 'beta' branch into the main development branch. It ensures that the 'beta' branch remains up-to-date with the latest changes and allows for easy testing of new features before merging them into the main branch.

To use the run-beta-bot workflow, follow the instructions provided in the workflow file located in the `.github/workflows` folder.

### GeneXus Dependency Sync

The GeneXus Dependency Sync workflow is used to update the version of a component in the GeneXus source code repository. This workflow automates the process of synchronizing the component version across multiple projects, ensuring consistency and reducing the chance of errors.

To use the GeneXus Dependency Sync workflow, follow the instructions provided in the workflow file located in the `.github/workflows` folder.

## Contributing

Contributions and forking of this repository are not allowed at the moment. The workflows provided here are maintained by a dedicated team and are not open for external contributions.

## License

This repository and its contents are licensed under the [MIT License](LICENSE). Please review the license file for more information.

---

We hope that the workflows provided in this repository help streamline your GeneXus development process and improve your productivity. Feel free to explore and use the workflows in your own projects. If you have any questions or feedback, please don't hesitate to reach out to us. Happy coding!
