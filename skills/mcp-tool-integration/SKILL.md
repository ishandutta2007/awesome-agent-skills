---
name: mcp-tool-integration
description: Implementing and connecting Model Context Protocol (MCP) tools. Use when you need to extend an agent's capabilities with external data sources or execution environments.
---

# MCP Tool Integration

## Overview
Model Context Protocol (MCP) is the standard for connecting AI agents to external tools and context. This skill guides the integration and development of new MCP tools.

## When to Use
- You need to access data outside the agent's current context
- You are building custom tools for Claude Desktop or other MCP-compatible clients
- Integrating REST APIs, databases, or local services via MCP

## Process
1. **Define the Protocol**: Choose standard stdio or SSE depending on the deployment environment.
2. **Design Tool Schemas**: Create clear, descriptive JSON schemas for tool inputs.
3. **Implement Handlers**: Write the execution logic.
4. **Test Locally**: Verify tool execution and error handling.
5. **Configure Client**: Add the MCP server to the agent's configuration file.
