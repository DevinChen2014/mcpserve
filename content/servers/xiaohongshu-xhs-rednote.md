---
title: Xiaohongshu XHS RedNote Insights MCP
description: A read-only MCP server for Xiaohongshu (Little Red Book / RedNote / XHS) note search, note details, comments, creator profiles, and creator post lists.
category: Search
features:
- Search and Information Retrieval
- Data Summarization and Analysis
- Research Tools
layout: server
created_at: 2026-04-29
updated_at: 2026-04-29
github_url: https://github.com/DevinChen2014/xiaohongshu-xhs-rednote-mcp
website_url: https://52choujiang.com/assistant
license: MIT
free: false
---

## Overview

The Xiaohongshu XHS RedNote Insights MCP server is a read-only remote MCP service for Xiaohongshu social media research workflows. It provides tools for note search, note detail retrieval, comment pagination, creator profile lookup, and creator post list retrieval. This makes it useful for market research, creator analysis, comment insights, topic discovery, and competitive monitoring inside AI assistants and MCP-compatible clients.

The service is exposed through a remote `streamable_http` endpoint and uses API key authentication through the `Authorization` header.

## Use Cases

- **Xiaohongshu note discovery:** Search notes by keyword and inspect relevant post metadata for trend tracking and research.
- **Comment and sentiment review:** Read first-level comment pages to understand audience feedback, pain points, and discussion themes.
- **Creator intelligence:** Retrieve creator profiles and creator post lists for account research, benchmarking, and collaboration discovery.
- **Content planning:** Use note and creator data to support topic selection, campaign ideation, and audience insight workflows.

## Example

To connect this MCP server from an MCP client that supports remote `streamable_http`, use the following configuration and replace `<XHS_MCP_API_KEY>` with your own API key:

```json
{
  "mcpServers": {
    "xiaohongshu-xhs-rednote-insights": {
      "type": "streamable_http",
      "url": "https://mcp.52choujiang.com/xhs/mcp",
      "headers": {
        "Authorization": "Bearer <XHS_MCP_API_KEY>"
      }
    }
  }
}
```

You can then use tools such as:

- `xhs_search_notes`
- `xhs_get_note_detail_by_note_id`
- `xhs_get_note_comments_by_note_id`
- `xhs_get_user_info_by_user_id`
- `xhs_get_user_posted_notes_by_user_id`

For API key details and client setup examples, see the public repository and documentation links above.
