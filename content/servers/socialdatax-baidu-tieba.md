---
title: SocialDataX Baidu Tieba MCP
description: Search public Baidu Tieba threads and users, read thread details, comments and nested replies, and explore creator profiles, posts and forums.
category: Search
features:
- Data Summarization and Analysis
layout: server
created_at: 2026-10-20
updated_at: 2026-10-20
github_url: https://github.com/DevinChen2014/baidu-tieba-mcp
website_url: https://socialdatax.com/ai?from=mcpserve
license: MIT
free: false
---

## Overview

Search public Baidu Tieba threads and users, read thread details, comments and nested replies, and explore creator profiles, posts and forums.

## Connection

```json
{
  "mcpServers": {
    "socialdatax-baidu-tieba": {
      "type": "streamable_http",
      "url": "https://mcp.socialdatax.com/baidu-tieba/mcp",
      "headers": {
        "Authorization": "Bearer <SOCIALDATAX_API_KEY>"
      }
    }
  }
}
```

Use your own `SOCIALDATAX_API_KEY`. Get an API key and setup guidance at [SocialDataX](https://socialdatax.com/ai?from=mcpserve). Business calls consume SocialDataX points; see the current pricing before use. The public repository contains documentation and connection examples under MIT; the service implementation is privately hosted.
