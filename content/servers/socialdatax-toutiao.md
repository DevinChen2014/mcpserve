---
title: SocialDataX Toutiao MCP
description: Search public Toutiao posts and users, get hot searches and suggestions, and read post details, comments, replies, creator profiles and creator posts.
category: Search
features:
- Data Summarization and Analysis
layout: server
created_at: 2026-10-20
updated_at: 2026-10-20
github_url: https://github.com/DevinChen2014/toutiao-mcp
website_url: https://socialdatax.com/ai?from=mcpserve
license: MIT
free: false
---

## Overview

Search public Toutiao posts and users, get hot searches and suggestions, and read post details, comments, replies, creator profiles and creator posts.

## Connection

```json
{
  "mcpServers": {
    "socialdatax-toutiao": {
      "type": "streamable_http",
      "url": "https://mcp.socialdatax.com/toutiao/mcp",
      "headers": {
        "Authorization": "Bearer <SOCIALDATAX_API_KEY>"
      }
    }
  }
}
```

Use your own `SOCIALDATAX_API_KEY`. Get an API key and setup guidance at [SocialDataX](https://socialdatax.com/ai?from=mcpserve). Business calls consume SocialDataX points; see the current pricing before use. The public repository contains documentation and connection examples under MIT; the service implementation is privately hosted.
