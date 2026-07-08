# arche

> An open-source computer language for physics knowledge.

> [!WARNING]
> This project is still a work in progress. Contributions are welcome.

## Overview

With the advent of AI, there has been a lot of talk about a knowledge corpus or graph for physics knowledge. **arche** is designed to be the bedrock of this knowledge graph.

## Goals

arche aims to be:

- **Contextual** — encode the context of a result via structured relationships to other results.
- **Descriptive** — encode the English description of a result.
- **Verifiable** — interconnect with [Lean](https://lean-lang.org/) and projects like [Mathlib](https://github.com/leanprover-community/mathlib4) and [Physlib](https://github.com/leanprover-community/physlib) for verification.
- **Versioned** — record changes to those descriptions over time.

## Organization

The project is organized into three components:

| Component | Description |
| --- | --- |
| `language` | The core language definition. |
| `vscode-extension` | Editor tooling and language support for VS Code. |
| `example` | Worked examples demonstrating the language. |
| `docs` | Docuemntation on the language. | 


## Contributing

Contributions are welcome, please do so via a fork or a pull-request. 
