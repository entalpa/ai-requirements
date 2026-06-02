# Entalpa: Transforming Intent into Engineering Truth

**[Entalpa.com](https://entalpa.com)** is the architectural engine built for the era of AI-Driven Development (ADD). Entalpa (formerly entalpa) turns your initial "vibe" or project concept into high-density, rigorous technical specifications.

## The Entalpa Lifecycle

The Entalpa workflow is designed to eliminate architectural drift and AI hallucinations:

1.  **Specify:** Use Entalpa’s Socratic Elicitation Engine to find "blind spots" and generate structured stories and requirements.
2.  **Connect:** Link your project context directly to your AI agent via the **Model Context Protocol (MCP)**.
3.  **Implement:** Your agent reads the "Engineering Truth" and builds the code exactly as intended.

---

## Connecting via MCP (Model Context Protocol)

Entalpa provides a native MCP server, allowing your AI Agent (Cursor, Windsurf, Claude Desktop) to query your live requirements and stories in real-time.

### Quick Start: MCP Configuration

Add the following to your MCP configuration file:

```json
{
  "mcpServers": {
    "entalpa": {
      "httpUrl": "https://api.entalpa.com/mcp"
    }
  }
}
```

### Authentication Flow
When you activate the server, Entalpa ensures secure access through a standardized flow:
* **Redirect:** You will be redirected to the Entalpa login page (powered by Keycloak).
* **Authorize:** Log in to verify your identity.
* **Handshake:** The browser securely passes the session back to your local MCP client, giving your agent immediate access to tools like `get_project_stories` and `list_requirements`.

---
*Ready to build? Explore our [SaaS Professional Suite](./templates/saas-professional-suite/) to see the Entalpa output in action.*
