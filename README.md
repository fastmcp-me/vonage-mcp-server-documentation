[![Add to Cursor](https://fastmcp.me/badges/cursor_dark.svg)](https://fastmcp.me/MCP/Details/1562/vonage-documentation)
[![Add to VS Code](https://fastmcp.me/badges/vscode_dark.svg)](https://fastmcp.me/MCP/Details/1562/vonage-documentation)
[![Add to Claude](https://fastmcp.me/badges/claude_dark.svg)](https://fastmcp.me/MCP/Details/1562/vonage-documentation)
[![Add to ChatGPT](https://fastmcp.me/badges/chatgpt_dark.svg)](https://fastmcp.me/MCP/Details/1562/vonage-documentation)
[![Add to Codex](https://fastmcp.me/badges/codex_dark.svg)](https://fastmcp.me/MCP/Details/1562/vonage-documentation)
[![Add to Gemini](https://fastmcp.me/badges/gemini_dark.svg)](https://fastmcp.me/MCP/Details/1562/vonage-documentation)

# Vonage Documentation MCP Server

<img src="https://developer.nexmo.com/images/logos/vbc-logo.svg" height="50px" alt="Vonage" />

An MCP (Model Context Protocol) server that provides AI assistants with access to Vonage API documentation, code snippets, tutorials, and troubleshooting resources.

## Overview

This MCP server enables AI assistants like Claude, GitHub Copilot, and others to interact with Vonage's comprehensive developer documentation. It provides tools for searching documentation, generating code snippets, finding tutorials, troubleshooting issues, and more.

## Features

- **Documentation Search**: Search through Vonage's official developer documentation for guides, tutorials, and API references
- **Code Generation**: Generate complete, runnable code snippets in multiple programming languages (Node.js, Python, PHP, etc.)
- **API Reference**: Access detailed information about specific Vonage API endpoints, parameters, and response schemas
- **SDK Information**: Retrieve installation instructions, supported features, and version numbers for Vonage SDKs
- **Troubleshooting**: Get error code explanations, debugging advice, and solutions for common issues
- **Tutorial Finder**: Discover step-by-step tutorials and blog posts from the Vonage Developer blog
- **Use Case Examples**: Explore real-world use cases and customer stories for Vonage products

## Available Tools

The server provides the following tools:

- `vonage_docs_search` - Search Vonage documentation
- `vonage_code_generator` - Generate code snippets for Vonage APIs
- `vonage_api_reference` - Get API endpoint documentation
- `vonage_sdk_info` - Retrieve SDK information
- `vonage_troubleshooter` - Get troubleshooting help
- `vonage_tutorial_finder` - Find tutorials and guides
- `vonage_use_case_examples` - Discover use cases

## Installation

### Using the MCP Marketplace

This server is available through the Model Context Protocol marketplace. To install:

1. Open your MCP-compatible client (Claude Desktop, Cline, etc.)
2. Navigate to the MCP marketplace
3. Search for "Vonage Documentation"
4. Click Install

### Manual Configuration

Add this to your MCP settings configuration:

```json
{
  "mcpServers": {
    "vonage-documentation": {
      "url": "https://documentation-mcp.vonage.dev/mcp",
      "transport": "streamable-http"
    }
  }
}
```

## Usage Examples

Once installed, you can ask your AI assistant questions like:

- "How do I send an SMS with Vonage?"
- "Show me a code example for making a voice call in Node.js"
- "What are the parameters for the Messages API?"
- "Help me troubleshoot error code 1320"
- "Find a tutorial about building a voice proxy"
- "What versions of the Python SDK are available?"

## Server Endpoint

The MCP server is hosted at: `https://documentation-mcp.vonage.dev/mcp`

## Repository Structure

```
.
├── server.json          # MCP marketplace configuration
├── README.md           # This file
├── CONTRIBUTING.md     # Contribution guidelines
├── CODE_OF_CONDUCT.md  # Code of conduct
└── LICENSE.txt         # License information
```

## Contributing

We welcome contributions! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for details on how to contribute to this project.

## Code of Conduct

This project adheres to the Vonage Code of Conduct. By participating, you are expected to uphold this code. Please see [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) for details.

## License

See [LICENSE.txt](LICENSE.txt) for license information.

## Support

- **Documentation**: [developer.vonage.com](https://developer.vonage.com)
- **Community Slack**: [Vonage Community Slack](https://developer.vonage.com/community/slack)
- **Issues**: [GitHub Issues](https://github.com/Vonage/vonage-mcp-server-documentation/issues)

## About Vonage

Vonage is a global leader in cloud communications, providing APIs for SMS, Voice, Video, Messaging, and more. Visit [vonage.com](https://www.vonage.com) to learn more.

---

Made with ❤️ by Vonage
