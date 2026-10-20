---
title: SocialDataX Sensitive Text Check MCP
description: Check text for potential platform review risks and query SocialDataX account points balance. Results are screening aids and do not guarantee platform acceptance.
category: Data Summarization and Analysis
features:
- Data Summarization and Analysis
layout: server
created_at: 2026-10-20
updated_at: 2026-10-20
github_url: https://github.com/DevinChen2014/socialdatax-sensitive-check-mcp
website_url: https://socialdatax.com/ai?from=mcpserve
license: MIT
free: false
---

## Overview

Check text for potential platform review risks and query SocialDataX account points balance. Results are screening aids and do not guarantee platform acceptance.

Text submitted to the checking tool is sent to the hosted service.

## Connection

```json
{
  "mcpServers": {
    "socialdatax-sensitive-check": {
      "type": "streamable_http",
      "url": "https://mcp.socialdatax.com/sensitive-check/mcp",
      "headers": {
        "Authorization": "Bearer <SOCIALDATAX_API_KEY>"
      }
    }
  }
}
```

Use your own `SOCIALDATAX_API_KEY`. Get an API key and setup guidance at [SocialDataX](https://socialdatax.com/ai?from=mcpserve). Business calls consume SocialDataX points; see the current pricing before use. The public repository contains documentation and connection examples under MIT; the service implementation is privately hosted.
