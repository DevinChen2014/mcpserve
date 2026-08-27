---
title: SocialDataX Kuaishou Kwai MCP
description: A read-only remote MCP server for Kuaishou / Kwai hot lists, works, comments, creators, and video transcripts.
category: Search
features:
- Search and Information Retrieval
- Data Summarization and Analysis
- Research Tools
layout: server
created_at: 2026-08-27
updated_at: 2026-08-27
github_url: https://github.com/DevinChen2014/kuaishou-mcp
website_url: https://socialdatax.com
license: MIT
free: false
---

## Overview

SocialDataX Kuaishou / Kwai MCP provides authenticated, read-only access to public Kuaishou data. It supports hot lists, work and creator search, work details, comments and replies, creator profiles and works, and video speech-to-text transcripts.

## Example

```json
{
  "mcpServers": {
    "socialdatax-kuaishou": {
      "type": "streamable_http",
      "url": "https://mcp.socialdatax.com/kuaishou/mcp",
      "headers": { "Authorization": "Bearer <SOCIALDATAX_API_KEY>" }
    }
  }
}
```

Get an API key and setup guidance at [SocialDataX](https://socialdatax.com). The public repository contains the current tool list and client examples.
