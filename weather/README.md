# Weather MCP Server

## Usage

`uv run weather.py`

## Claude Desktop configuration

Open configuration file:  
`vi ~/Library/Application\ Support/Claude/claude_desktop_config.json`

Configure it to add our weather server:  
```json
{
    "mcpServers": {
        "weather": {
            "command": "/Users/rommel/.local/bin/uv",
            "args": [
                "--directory",
                "/Users/rommel/code/play/python/mcp_tutorial/weather",
                "run",
                "weather.py"
            ]
        }
    }
}
```
