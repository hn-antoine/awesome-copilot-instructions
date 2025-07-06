<h1 align="center">
  <img src="./imgs/awesome-github-copilot.svg" alt="Awesome Copilot Instructions" height="300">
</h1>

<h4 align="center">✨ A curated list of awesome GitHub copilot-instructions.md files for enhancing your GitHub Copilot AI experience.</h4>

<p align="center">
  <a href="hhttps://awesome.re">
    <img src="https://awesome.re/badge-flat2.svg" alt="Awesome">
  </a>
</p>

<hr>
<p align="center">
	<a href="CONTRIBUTING.md">📖 Contribution Guide</a>
</p>
<br>

# Why copilot-instructions.md files?

`copilot-instructions.md` files help guide GitHub Copilot by providing contextual details about your repository such as the type of workflow your team follows, tools and other project specific details such as coding style, frameworks used or project specific rules.

> [!TIP]
> Learn more about Copilot Instructions [here](https://code.visualstudio.com/docs/copilot/copilot-customization).

# Contents

- [Copilot Instructions](#copilot-instructions)
  - [Boilerplates & Templates](#boilerplates--templates)
  - [Language & Stack](#language--stack)
  - [Framework / Library](#framework--library)
  - [Tools](#tools)
  - [Workflows](#workflows)

# Copilot Instructions

## Boilerplates & Templates

### Language Templates
- [Standard Language Template](instructions/templates/standard-language/copilot-instructions.md)

## Language & Stack

### C
- [Standard Focus](instructions/languages/c/standard-focus/copilot-instructions.md)

### C#
- [Standard Focus](instructions/languages/csharp/standard-focus/copilot-instructions.md)

### C++
- [Standard Focus](instructions/languages/cplusplus/standard-focus/copilot-instructions.md)

### Go
- [Standard Focus](instructions/languages/go/standard-focus/copilot-instructions.md)

### Java
- [Standard Focus](instructions/languages/java/standard-focus/copilot-instructions.md)

### Javascript
- [Standard Focus](instructions/languages/javascript/standard-focus/copilot-instructions.md)

### Kotlin
- [Standard Focus](instructions/languages/kotlin/standard-focus/copilot-instructions.md)

### Lua
- [Standard Focus](instructions/languages/lua/standard-focus/copilot-instructions.md)

### Python
- [Standard Focus](instructions/languages/python/standard-focus/copilot-instructions.md)

### Rust
- [Standard Focus](instructions/languages/rust/standard-focus/copilot-instructions.md)

### Swift
- [Standard Focus](instructions/languages/swift/standard-focus/copilot-instructions.md)

### Typescript
- [Standard Focus](instructions/languages/typescript/standard-focus/copilot-instructions.md)

## Framework / Library

### Cobra CLI (Go)
- [Charmbracelet Bubbles CLI](instructions/frameworks/cobra-cli-go/charmbracelet-cli/copilot-instructions.md)

### NodeJS (Typescript)
- [Azure Function App](instructions/frameworks/nodejs-typescript/azure-function-app/copilot-instructions.md)
- [Express API](instructions/frameworks/nodejs-typescript/express-api/copilot-instructions.md)

## Tools

### Content Management Systems (CMS)

#### Drupal
- [Standard Focus for Drupal 11](instructions/tools/cms/drupal/11/standard-focus/copilot-instructions.md)

### Infra as Code (IaC)

#### Terraform
- [Standard Focus](instructions/tools/infra-as-code/terraform/standard-focus/copilot-instructions.md)
- [Atmos](instructions/tools/infra-as-code/terraform/atmos/copilot-instructions.md)

## Workflows

### AI Development Tasks
*Adapted from [snarktank/ai-dev-tasks](https://github.com/snarktank/ai-dev-tasks)*

A comprehensive workflow for AI-assisted development featuring structured approaches to planning, task generation, and execution:

- [PRD Creation](instructions/workflows/ai-development-tasks/prd-creation/prd-creation.instructions.md) - Create detailed Product Requirements Documents ([prompt](instructions/workflows/ai-development-tasks/prd-creation/prd-creation.prompt.md))
- [Task Generation](instructions/workflows/ai-development-tasks/task-generation/task-generation.instructions.md) - Break PRDs into actionable development tasks ([prompt](instructions/workflows/ai-development-tasks/task-generation/task-generation.prompt.md))
- [Task Execution](instructions/workflows/ai-development-tasks/task-execution/task-execution.instructions.md) - Systematic task execution with proper testing and git practices ([prompt](instructions/workflows/ai-development-tasks/task-execution/task-execution.prompt.md))

# How to Use

## Setup Copilot in VSCode
1. Hover over the Copilot icon in the Status Bar and select Set up Copilot.
2. Select **Sign in** to sign in to your GitHub account or **Use Copilot** if you're already signed in.

> [!TIP]
> Read more [here](https://code.visualstudio.com/docs/copilot/setup).

## Setup Instructions

1. Set the `github.copilot.chat.codeGeneration.useInstructionFiles` setting to `true` to instruct Copilot in VS Code to use the custom instructions file.
2. Create instruction files using the latest naming conventions:
   - **Workspace instructions**: Place `*.instructions.md` files in `.github/instructions/` directory
   - **Workspace prompts**: Place `*.prompt.md` files in `.github/prompts/` directory
   - **Legacy format**: `.github/copilot-instructions.md` (still supported)

### File Types
- **`.instructions.md`**: Contextual instructions that apply to specific files or file types
- **`.prompt.md`**: Reusable prompts for specific tasks or workflows
- **Front matter**: Use YAML front matter to specify metadata like `applyTo`, `mode`, and `description`

> [!TIP]
> Read more about the latest naming conventions [here](https://code.visualstudio.com/docs/copilot/copilot-customization).

# Contributing

All contributions are welcome! If you would like to share instruction files (`.instructions.md`) or prompt files (`.prompt.md`), see the [contribution guide](CONTRIBUTING.md) for details.
