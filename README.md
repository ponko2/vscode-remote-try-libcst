# vscode-remote-try-libcst

## Getting Started

### Installation

Install the dependencies:

```sh
uv sync
```

Install the pre-commit script:

```sh
uvx pre-commit install
```

### Running Codemods

```sh
uv run -m libcst.tool codemod constant_folding.ConvertConstantCommand --help
```
