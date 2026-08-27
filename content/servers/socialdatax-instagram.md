---
title: SocialDataX Instagram MCP
description: A read-only remote MCP server for Instagram posts, comments, replies, public profiles, user posts, and Reels transcripts.
category: Search
features:
- Search and Information Retrieval
- Data Summarization and Analysis
- Research Tools
layout: server
created_at: 2026-08-27
updated_at: 2026-08-27
github_url: https://github.com/DevinChen2014/instagram-mcp
website_url: https://socialdatax.com
license: MIT
free: false
---

## Overview

SocialDataX Instagram MCP provides authenticated, read-only access to public Instagram posts, comments and replies, creator profiles and posts, plus speech-to-text transcripts for public videos and Reels.

## Example

```json
{
  "mcpServers": {
    "socialdatax-instagram": {
      "type": "streamable_http",
      "url": "https://mcp.socialdatax.com/instagram/mcp",
      "headers": { "Authorization": "Bearer <SOCIALDATAX_API_KEY>" }
    }
  }
}
```

Get an API key and setup guidance at [SocialDataX](https://socialdatax.com). The public repository contains the current tool list and client examples.
