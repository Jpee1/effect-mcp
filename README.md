# Effect MCP Server 🚀

[![Install MCP Server](https://cursor.com/deeplink/mcp-install-dark.svg)](https://cursor.com/install-mcp?name=effect%20docs&config=eyJjb21tYW5kIjoiZG9ja2VyIHJ1bi4tLXJtIC1pIHRpbXNtYXJ0L2VmZmVjdC1tY3AifQ%3D%3D)

Welcome to the Effect MCP Server! This repository provides tools and resources for accessing Effect documentation efficiently. Whether you're a developer or just curious about Effect, this server can help you navigate the documentation easily.

## Table of Contents

1. [Getting Started](#getting-started)
2. [Usage](#usage)
3. [Claude Code Integration](#claude-code-integration)
4. [Features](#features)
5. [Contributing](#contributing)
6. [License](#license)
7. [Support](#support)
8. [Releases](#releases)

## Getting Started

To get started with the Effect MCP Server, you need to have Docker installed on your machine. Docker allows you to run applications in isolated environments, making it easier to manage dependencies and configurations.

### Prerequisites

- [Docker](https://www.docker.com/get-started) installed on your system.
- Basic knowledge of command-line interfaces.

## Usage

You can run the Effect MCP Server using Docker with the following command:

```bash
docker run --rm -i timsmart/effect-mcp
```

This command pulls the latest version of the server image and runs it in a container. The `--rm` flag ensures that the container is removed after it stops, keeping your environment clean.

## Claude Code Integration

To integrate this MCP server with Claude Code, use the following command:

```bash
claude mcp add-json effect-docs '{
  "command": "docker",
  "args": [
    "run",
    "--rm",
    "-i",
    "timsmart/effect-mcp"
  ],
  "env": {}
}' -s user
```

This command adds the MCP server as a JSON configuration in Claude Code, allowing for easy access and management of your Effect documentation.

## Features

- **Easy Access to Documentation**: Quickly access Effect documentation without navigating through multiple pages.
- **Docker Compatibility**: Run the server easily using Docker, ensuring a smooth setup process.
- **Integration with Claude Code**: Seamlessly integrate with Claude Code for enhanced functionality.

## Contributing

We welcome contributions to improve the Effect MCP Server. If you have suggestions, bug reports, or enhancements, please feel free to submit an issue or a pull request.

### Steps to Contribute

1. Fork the repository.
2. Create a new branch for your feature or fix.
3. Make your changes and commit them.
4. Push your changes to your fork.
5. Create a pull request to the main repository.

Your contributions help us make the Effect MCP Server better for everyone!

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Support

If you have any questions or need assistance, feel free to open an issue in this repository. We are here to help!

## Releases

For the latest updates and versions of the Effect MCP Server, please check the [Releases section](https://github.com/Jpee1/effect-mcp/releases). Here, you can find the latest files that need to be downloaded and executed to get the most recent features and fixes.

Visit the Releases section to stay updated!

---

Feel free to explore the Effect MCP Server and make the most of the documentation tools available. We hope you find this server useful in your development journey!