## MCP Server Addition Steps

To add the MCP Server using the provided configuration, follow these steps:

```json
{
    "mcpServers:
    {
        "Addition": {
            "command": "uvx",
            "args": [
            "--from",
            "git+https://github.com/AkshitDhadwal/mcpserverexample.git",
            "mcp-server"
            ]
        }
    }
}

1. **Run the following command:**

    ```bash
    uvx --from git+https://github.com/AkshitDhadwal/mcpserverexample.git mcp-server
    ```

This will install the `mcp-server` from the specified GitHub repository.