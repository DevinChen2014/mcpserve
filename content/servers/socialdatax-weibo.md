---
title: SocialDataX Weibo MCP
description: A read-only remote MCP server for Weibo hot search, posts, comments, users, user posts, and video transcripts.
category: Search
features:
- Search and Information Retrieval
- Data Summarization and Analysis
- Research Tools
layout: server
created_at: 2026-08-27
updated_at: 2026-08-27
github_url: https://github.com/DevinChen2014/weibo-mcp
website_url: https://socialdatax.com
license: MIT
free: false
---

## Overview

SocialDataX Weibo MCP provides authenticated, read-only access to public Weibo data. It supports hot search, post search and details, comments and replies, user profiles and posts, and video speech-to-text transcripts.

## Example

```json
{
  "mcpServers": {
    "socialdatax-weibo": {
      "type": "streamable_http",
      "url": "https://mcp.socialdatax.com/weibo/mcp",
      "headers": { "Authorization": "Bearer <SOCIALDATAX_API_KEY>" }
    }
  }
}
```

Get an API key and setup guidance at [SocialDataX](https://socialdatax.com). The public repository contains the current tool list and client examples.
