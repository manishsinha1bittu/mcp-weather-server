# MCP Weather Server 🌦️

A Model Context Protocol (MCP) server that provides weather tools
for Claude Desktop using the National Weather Service API.

## Features
- Get active weather alerts by US state
- Get weather forecasts using latitude & longitude
- Built with Python + FastMCP
- Uses STDIO transport (Claude Desktop compatible)

## Tools
- `get_alerts(state: str)`
- `get_forecast(latitude: float, longitude: float)`

## How to Run
```bash
uv run weather.py

MCP Integration

Configured via claude_desktop_config.json

Author

Manish Sinha
