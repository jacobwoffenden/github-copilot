# GitHub Copilot

[![Open in Dev Container](https://raw.githubusercontent.com/ministryofjustice/.devcontainer/refs/heads/main/contrib/badge.svg)](https://vscode.dev/redirect?url=vscode://ms-vscode-remote.remote-containers/cloneInVolume?url=https://github.com/jacobwoffenden/github-copilot) [![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/jacobwoffenden/github-copilot)

A collection of notes and configuration for using [GitHub Copilot](https://github.com/features/copilot).

## Web

### [Chat](https://github.com/copilot)

### [Agents](https://github.com/copilot/agents)

### [Spaces](https://github.com/copilot/spaces)

### [Spark](https://github.com/spark)

### [MCP Registry](https://github.com/mcp)

## [CLI](https://github.com/github/copilot-cli) (Public Preview)


1. Authenticate with GitHub

    ```bash
    gh auth login --git-protocol ssh --skip-ssh-key --web
    ```

1. Launch GitHub Copilot CLI

    ```bash
    GITHUB_TOKEN=$(gh auth token) copilot
    ```

## [Visual Studio Code](https://code.visualstudio.com/docs/copilot/overview)

### [Chat](https://code.visualstudio.com/docs/copilot/chat/copilot-chat)

Launch GitHub Copilot Chat with Command + Shift + I

### [MCP](https://code.visualstudio.com/docs/copilot/customization/mcp-servers)

[`.vscode/mcp.json`](.vscode/mcp.json)
