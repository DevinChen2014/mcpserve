---
title: SocialDataX Zhihu MCP
description: A read-only remote MCP server for Zhihu hot lists, content search, answers, articles, videos, comments, and creators.
category: Search
features:
- Search and Information Retrieval
- Data Summarization and Analysis
- Research Tools
layout: server
created_at: 2026-08-27
updated_at: 2026-08-27
github_url: https://github.com/DevinChen2014/zhihu-mcp
website_url: https://socialdatax.com
license: MIT
free: false
---

## Overview

SocialDataX Zhihu MCP provides authenticated, read-only access to public hot lists, content search, answer, article and video details, creator profiles and article lists, comments, and comment replies.

## Example

```json
{
  "mcpServers": {
    "socialdatax-zhihu": {
      "type": "streamable_http",
      "url": "https://mcp.socialdatax.com/zhihu/mcp",
      "headers": { "Authorization": "Bearer <SOCIALDATAX_API_KEY>" }
    }
  }
}
```

Get an API key and setup guidance at [SocialDataX](https://socialdatax.com). The public repository contains the current tool list and client examples.
