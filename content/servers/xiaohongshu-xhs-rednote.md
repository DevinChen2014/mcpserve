---
title: SocialDataX Xiaohongshu XHS RedNote MCP
description: A read-only remote MCP server for Xiaohongshu / XHS / RedNote note and product research, comments, replies, and creator insights.
category: Search
features:
- Search and Information Retrieval
- Data Summarization and Analysis
- Research Tools
layout: server
created_at: 2026-04-29
updated_at: 2026-10-20
github_url: https://github.com/DevinChen2014/xiaohongshu-xhs-rednote-mcp
website_url: https://socialdatax.com/ai?from=mcpserve
license: MIT
free: false
---

## Overview

The SocialDataX Xiaohongshu XHS RedNote MCP server is a read-only remote service for public note and product research. It provides note search and details, product search and details, comments and replies, creator profiles, creator note lists, search suggestions, and account balance lookup.

The service is exposed through a remote `streamable_http` endpoint and uses API key authentication through the `Authorization` header.

## Use Cases

- **Xiaohongshu note discovery:** Search notes by keyword and inspect relevant post metadata for trend tracking and research.
- **Comment and sentiment review:** Read first-level comment pages to understand audience feedback, pain points, and discussion themes.
- **Creator intelligence:** Retrieve creator profiles and creator post lists for account research, benchmarking, and collaboration discovery.
- **Content planning:** Use note and creator data to support topic selection, campaign ideation, and audience insight workflows.

## Example

To connect from an MCP client that supports remote `streamable_http`, use the following configuration and replace `<SOCIALDATAX_API_KEY>` with your API key from [SocialDataX](https://socialdatax.com/ai?from=mcpserve):

```json
{
  "mcpServers": {
    "socialdatax-xhs": {
      "type": "streamable_http",
      "url": "https://mcp.socialdatax.com/xhs/mcp",
      "headers": {
        "Authorization": "Bearer <SOCIALDATAX_API_KEY>"
      }
    }
  }
}
```

For the current tool list and additional client examples, see the public repository linked above.

Business calls consume SocialDataX points. Use your own API key and review the current pricing before use.
