## About The Project

This project is a Visual Studio Code extension for [Colang](https://github.com/NVIDIA/NeMo-Guardrails/blob/develop/docs/user_guides/colang-language-syntax-guide.md) language.

## Getting Started

You can install the extension manually by following the steps below.

### Manual installation

#### Prerequisites

- The Visual Studio Code Extension Manager

```sh
npm install -g vsce
```

#### Installation

- Clone this project

```sh
git clone https://github.com/dangmarm/colang-lang.git
```

- Build extension

```sh
vsce package
```

- Install extension

```sh
code --install-extension .\colang-lang-0.0.1.vsix
```

## Features

- Syntax highlight
- Shortcut to comment code

## License

Distributed under the MIT License. See `LICENSE` for more information.
