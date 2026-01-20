# Screenshot MCP Server

[![MCP Compatible](https://img.shields.io/badge/MCP-Compatible-blue)](https://insightfulpipe.com/mcp-servers/screenshot)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

> **Capture high-quality website screenshots with AI through MCP.**

The Screenshot MCP server enables Claude, ChatGPT, Cursor, and other AI assistants to capture screenshots of web pages. Generate visual documentation, compare designs, and analyze page layouts.

![Screenshot MCP Server](https://insightfulpipe.com/images/ip-logo.png)

## MCP Server URL

```
https://screenshot.insightfulmcp.com/
```

## What is Screenshot MCP?

Screenshot MCP is a **remote Model Context Protocol server** that provides AI assistants with web page screenshot capabilities. This visual capture integration allows you to:

- Capture full-page and viewport screenshots
- Generate screenshots at various resolutions
- Capture mobile and desktop views
- Create visual documentation
- Get signed public URLs for captured images

## Installation

### Claude

1. Copy the MCP Server URL: `https://screenshot.insightfulmcp.com/`
2. Open [Claude Connectors Settings](https://claude.ai/settings/connectors)
3. Scroll to the bottom and click **Add custom connector**
4. Paste the URL and click **Add**
5. Click **Connect** on the connector to start authorization
6. Click **Authorize access** in the browser to complete the connection

### ChatGPT

1. Copy the MCP Server URL: `https://screenshot.insightfulmcp.com/`
2. Open ChatGPT Settings → **Connections**
3. Click **Add Connection** and paste the URL
4. Authorize with your InsightfulPipe account

### Claude Code

```bash
claude mcp add screenshot https://screenshot.insightfulmcp.com/
```

### Cursor

1. Open Cursor Settings → **MCP Servers**
2. Add new server with URL: `https://screenshot.insightfulmcp.com/`
3. Authorize the connection

## Available Actions

| Action | Description |
|--------|-------------|
| `capture` | Capture website screenshots and receive signed public URLs |

## Usage Examples

### Basic Screenshot

```
"Take a screenshot of https://example.com"
```

### Full Page Capture

```
"Capture a full-page screenshot of this landing page"
```

### Mobile Screenshot

```
"Take a mobile screenshot of this website"
```

### Documentation

```
"Screenshot this page for our documentation"
```

### Competitive Analysis

```
"Capture screenshots of these competitor websites"
```

## Features

- **Full page scrolling** - Capture long pages
- **JavaScript rendering** - Handle dynamic content
- **Custom viewports** - Any screen size
- **Device emulation** - Mobile/tablet simulation
- **Signed URLs** - Secure public access to images

## Why Screenshot MCP?

### For Designers
- **Design review** - Capture design implementations
- **Comparison** - Before/after screenshots
- **Documentation** - Visual design archives

### For QA Teams
- **Visual testing** - Capture for comparison
- **Bug documentation** - Screenshot issues
- **Cross-browser testing** - Different viewports

### For Marketers
- **Competitor monitoring** - Screenshot competitor sites
- **Campaign documentation** - Capture landing pages
- **Social proof** - Website screenshots for content

## Security & Privacy

- **Secure rendering** - Isolated browser instances
- **Signed URLs** - Secure access to images
- **Public URLs only** - By default
- **Data encryption** - Secure transmission

## Related MCP Servers

- [Web Crawler MCP](https://insightfulpipe.com/mcp-servers/crawler) - Web crawling
- [PageSpeed MCP](https://insightfulpipe.com/mcp-servers/pagespeed) - Performance
- [Google Search Console MCP](https://insightfulpipe.com/mcp-servers/google-search-console) - SEO

## Resources

- [Documentation](https://insightfulpipe.com/docs/screenshot)
- [Video Tutorial](https://www.youtube.com/playlist?list=PLJNzvjxzI5Xwe__BJJLAelSF0ewO3mEFk)
- [InsightfulPipe Blog](https://insightfulpipe.com/blogs)

## Support

- **Documentation**: [insightfulpipe.com/docs](https://insightfulpipe.com/docs)
- **Email**: support@insightfulpipe.com

## License

MIT License - see [LICENSE](LICENSE) for details.
