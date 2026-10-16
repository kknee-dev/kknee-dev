### Hi, I'm Cary 👋

I build **校招宝 (Xiaozhaobao)** — a campus-recruitment data platform for new graduates in China — plus the open-source pieces around it.

🌐 **[xiaozhaobao.com.cn](https://xiaozhaobao.com.cn)** · 📦 **[recruit-hub](https://github.com/kknee-dev/recruit-hub)** (MIT, zero-dependency)

---

#### 🤖 校招宝 MCP Server

China campus recruitment data — fall/spring hiring, internships, early batches — for AI agents.
**No API key, no sign-up, read-only.**

```json
{
  "mcpServers": {
    "xiaozhaobao": {
      "type": "http",
      "url": "https://xiaozhaobao.com.cn/mcp"
    }
  }
}
```

`search_campus_jobs` · `get_job_detail` · `get_company_profile` · `list_urgent_deadlines` · `get_stats`

> The server deliberately exposes **no application endpoints** — you always apply on the original posting page.

---

#### 🔧 What I work on

- **Zero-dependency Node 22 + `node:sqlite`** web apps — SSR + PWA, no `npm install`, no build step
- **MCP servers** — and getting them discovered by AI clients (Cursor, Claude, VS Code, Gemini CLI)
- **Data quality for Chinese campus recruitment** — dedup, desensitised public datasets, GEO/SEO
