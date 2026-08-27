---
title: SocialDataX Bilibili MCP
description: A read-only remote MCP server for Bilibili videos, articles, dynamics, comments, creators, reactions, and transcripts.
category: Search
features:
- Search and Information Retrieval
- Data Summarization and Analysis
- Research Tools
layout: server
created_at: 2026-08-27
updated_at: 2026-08-27
github_url: https://github.com/DevinChen2014/bilibili-mcp
website_url: https://socialdatax.com
license: MIT
free: false
---

## Overview

SocialDataX Bilibili MCP provides authenticated, read-only access to public videos, articles, dynamics, comments and replies, creator profiles and videos, likes and reposts, video download manifests, and speech-to-text transcripts.

## Example

```json
{
  "mcpServers": {
    "socialdatax-bilibili": {
      "type": "streamable_http",
      "url": "https://mcp.socialdatax.com/bilibili/mcp",
      "headers": { "Authorization": "Bearer <SOCIALDATAX_API_KEY>" }
    }
  }
}
```

Get an API key and setup guidance at [SocialDataX](https://socialdatax.com). The public repository contains the current tool list and client examples.
