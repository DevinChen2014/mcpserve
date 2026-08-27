---
title: SocialDataX X Twitter MCP
description: A read-only remote MCP server for X / Twitter post search, post details, comments, replies, public profiles, and user posts.
category: Search
features:
- Search and Information Retrieval
- Data Summarization and Analysis
- Research Tools
layout: server
created_at: 2026-08-27
updated_at: 2026-08-27
github_url: https://github.com/DevinChen2014/x-twitter-mcp
website_url: https://socialdatax.com
license: MIT
free: false
---

## Overview

SocialDataX X / Twitter MCP provides authenticated, read-only access to public post search and details, comments and replies, public user profiles, and user post lists.

## Example

```json
{
  "mcpServers": {
    "socialdatax-x": {
      "type": "streamable_http",
      "url": "https://mcp.socialdatax.com/x/mcp",
      "headers": { "Authorization": "Bearer <SOCIALDATAX_API_KEY>" }
    }
  }
}
```

Get an API key and setup guidance at [SocialDataX](https://socialdatax.com). The public repository contains the current tool list and client examples.
