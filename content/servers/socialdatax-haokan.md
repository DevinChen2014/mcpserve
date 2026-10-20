---
title: SocialDataX Haokan MCP
description: Search public Haokan videos and creators, read video details, comments, replies and creator videos, and get search suggestions and hot searches.
category: Search
features:
- Data Summarization and Analysis
layout: server
created_at: 2026-10-20
updated_at: 2026-10-20
github_url: https://github.com/DevinChen2014/haokan-mcp
website_url: https://socialdatax.com/ai?from=mcpserve
license: MIT
free: false
---

## Overview

Search public Haokan videos and creators, read video details, comments, replies and creator videos, and get search suggestions and hot searches.

## Connection

```json
{
  "mcpServers": {
    "socialdatax-haokan": {
      "type": "streamable_http",
      "url": "https://mcp.socialdatax.com/haokan/mcp",
      "headers": {
        "Authorization": "Bearer <SOCIALDATAX_API_KEY>"
      }
    }
  }
}
```

Use your own `SOCIALDATAX_API_KEY`. Get an API key and setup guidance at [SocialDataX](https://socialdatax.com/ai?from=mcpserve). Business calls consume SocialDataX points; see the current pricing before use. The public repository contains documentation and connection examples under MIT; the service implementation is privately hosted.
