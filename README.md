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

copilot-instructions.md files help guide GitHub Copilot by providing contextual details about your repository such as the type of workflow your team follows, tools and other project specific details such as coding style, frameworks used or project specific rules.

> [!TIP]
> Learn more about Copilot Instructions [here](https://code.visualstudio.com/docs/copilot/copilot-customization).

# Contents

- [Copilot Instructions](#copilot-instructions)
  - [Boilerplates & Templates](#boilerplates--templates)
  - [Language & Stack](#language--stack)
  - [Framework / Library](#framework--library)
  - [Tools](#tools)

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

### Infra as Code (IaC)

#### Terraform
- [Standard Focus](instructions/tools/infra-as-code/terraform/standard-focus/copilot-instructions.md)
- [Atmos](instructions/tools/infra-as-code/terraform/atmos/copilot-instructions.md)

# How to Use

## Setup Copilot in VSCode
1. Hover over the Copilot icon in the Status Bar and select Set up Copilot.
2. Select **Sign in** to sign in to your GitHub account or **Use Copilot** if you're already signed in.

> [!TIP]
> Read more [here](https://code.visualstudio.com/docs/copilot/setup).

## Setup Instructions

1. Set the `github.copilot.chat.codeGeneration.useInstructionFiles` setting to `true` to instruct Copilot in VS Code to use the custom instructions file.
2. Add the instructions file in `.github/copilot-instructions.md` at the root of your workspace. If needed, create a `.github` directory first.

> [!TIP]
> Read more [here](https://code.visualstudio.com/docs/copilot/copilot-customization).

# Contributing

All contributions are welcome! If you would like to share a copilot-instructions.md file, see the [contribution guide](CONTRIBUTING.md) for details.
