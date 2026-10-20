---
title: SocialDataX YouTube MCP
description: A read-only remote MCP server for YouTube video search, details, comments, channels, channel posts, and transcripts.
category: Search
features:
- Search and Information Retrieval
- Data Summarization and Analysis
- Research Tools
layout: server
created_at: 2026-08-27
updated_at: 2026-10-20
github_url: https://github.com/DevinChen2014/youtube-mcp
website_url: https://socialdatax.com/ai?from=mcpserve
license: MIT
free: false
---

## Overview

SocialDataX YouTube MCP provides authenticated, read-only access to public video search and details, top-level comments and replies, channel information, channel videos or Shorts, and video speech-to-text transcripts.

## Example

```json
{
  "mcpServers": {
    "socialdatax-youtube": {
      "type": "streamable_http",
      "url": "https://mcp.socialdatax.com/youtube/mcp",
      "headers": { "Authorization": "Bearer <SOCIALDATAX_API_KEY>" }
    }
  }
}
```

Get an API key and setup guidance at [SocialDataX](https://socialdatax.com/ai?from=mcpserve). The public repository contains the current tool list and client examples.

Business calls consume SocialDataX points. Use your own API key and review the current pricing before use.
