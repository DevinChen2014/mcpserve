---
title: SocialDataX Hongguo MCP
description: Search Hongguo short dramas, read series and episodes, reviews, video comments/replies and episode download links.
category: Search
features:
- Data Summarization and Analysis
layout: server
created_at: 2026-11-10
updated_at: 2026-11-10
github_url: https://github.com/DevinChen2014/hongguo-mcp
website_url: https://socialdatax.com/ai?from=mcpserve
license: MIT
free: false
---

## Overview

Search Hongguo short dramas, read series and episodes, reviews, video comments/replies and episode download links.

## Connection

```json
{
  "mcpServers": {
    "socialdatax-hongguo": {
      "type": "streamable_http",
      "url": "https://mcp.socialdatax.com/hongguo/mcp",
      "headers": {
        "Authorization": "Bearer <SOCIALDATAX_API_KEY>"
      }
    }
  }
}
```

Use your own `SOCIALDATAX_API_KEY`. Get an API key and setup guidance at [SocialDataX](https://socialdatax.com/ai?from=mcpserve). Business calls consume SocialDataX points; see the current pricing before use. The public repository contains documentation and connection examples under MIT; the service implementation is privately hosted.

Production exposes 12 tools, including the shared free points-balance tool. Current service does not provide weekly or historical rankings.
