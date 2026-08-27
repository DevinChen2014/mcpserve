---
title: SocialDataX WeChat Channels and Official Account MCP
description: A read-only remote MCP server for WeChat Channels videos, image posts, comments, users, transcripts, and Official Account articles.
category: Search
features:
- Search and Information Retrieval
- Data Summarization and Analysis
- Research Tools
layout: server
created_at: 2026-08-27
updated_at: 2026-08-27
github_url: https://github.com/DevinChen2014/wechat-channels-mcp
website_url: https://socialdatax.com
license: MIT
free: false
---

## Overview

SocialDataX WeChat Channels and Official Account MCP provides authenticated, read-only access to public video, image-post, comment, creator, transcript, and Official Account article information for research workflows.

## Example

```json
{
  "mcpServers": {
    "socialdatax-wechat": {
      "type": "streamable_http",
      "url": "https://mcp.socialdatax.com/wechat/mcp",
      "headers": { "Authorization": "Bearer <SOCIALDATAX_API_KEY>" }
    }
  }
}
```

Get an API key and setup guidance at [SocialDataX](https://socialdatax.com). The public repository contains the current tool list and client examples.
