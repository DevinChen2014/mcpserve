---
title: SocialDataX TikTok MCP
description: A read-only remote MCP server for TikTok video and image posts, comments, replies, creators, creator posts, and transcripts.
category: Search
features:
- Search and Information Retrieval
- Data Summarization and Analysis
- Research Tools
layout: server
created_at: 2026-08-27
updated_at: 2026-10-20
github_url: https://github.com/DevinChen2014/tiktok-mcp
website_url: https://socialdatax.com/ai?from=mcpserve
license: MIT
free: false
---

## Overview

SocialDataX TikTok MCP provides authenticated, read-only access to public video and image post search and details, comments and replies, creator profiles and posts, and video speech-to-text transcripts.

## Example

```json
{
  "mcpServers": {
    "socialdatax-tiktok": {
      "type": "streamable_http",
      "url": "https://mcp.socialdatax.com/tiktok/mcp",
      "headers": { "Authorization": "Bearer <SOCIALDATAX_API_KEY>" }
    }
  }
}
```

Get an API key and setup guidance at [SocialDataX](https://socialdatax.com/ai?from=mcpserve). The public repository contains the current tool list and client examples.

Business calls consume SocialDataX points. Use your own API key and review the current pricing before use.
