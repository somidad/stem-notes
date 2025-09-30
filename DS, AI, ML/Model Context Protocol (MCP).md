---
aliases:
  - MCP
---

# Model Context Protocol (MCP)

## Introduction

[MCP](https://modelcontextprotocol.io/) by [Anthropic](https://anthropic.com) (of [Claude](https://claude.ai/)) is a standardized way for an [LLM](LLM.md) to interact with external resources.

Roughly, a user prompt and a list of tools (APIs) as a prompt are given to an LLM and it generates a message containing an API name and required parameters to invoke an API.

## Components

MCP host

- You can think it as your main application with an LLM

LLM

MCP server

- It provides certain services, each can be either a tool, a resource or a prompt (template)
- A tool: 
- A resource: 
- A prompt: 

MCP client

- It resides in an MCP host
- Mainly a communication bridge between an MCP host and an MCP server
- And it manages a tool list exposed by an MCP server and a connection between the server
- 1 MCP client is needed for 1 MCP server


