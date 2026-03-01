
### [Project: System Admin] Agent Model Configuration
- **Result**: (from 2026-02-27)
- **Files**: `C:\Users\Administrator\.clawdbot\clawdbot.json`
- **Lesson**: Permanent model changes for the main agent require a configuration file patch (`gateway config.patch`), which triggers a system restart. Sub-agents can be spawned with different models if the configuration allows.
- **Tags**: #model-switching #configuration #clawdbot

### [Project: Research] Web Scraping E-commerce Site
- **Result**: (from 2026-02-27)
- **Files**: N/A
- **Lesson**: When direct access with `browser` or `web_fetch` is blocked by anti-bot measures or login walls, a successful workaround is to use the `browser` tool to perform a site-specific Google search (e.g., `site:shopee.tw "product title"`) and extract key information from the search result snippets.
- **Tags**: #web-scraping #browser #workaround #shopee

### [Project: System Admin] Cron Job Creation
- **Result**: (from 2026-02-27)
- **Files**: N/A
- **Lesson**: Constructing the correct JSON object for the `cron` tool's `job` parameter can be complex and error-prone. A more reliable method is to use the `exec` tool to call the `clawdbot cron add` CLI command, which has simpler-to-use flags like `--cron`, `--at`, `--tz`, and `--system-event`. The CLI's help (`--help`) can be inspected to learn the correct syntax.
- **Tags**: #cron #automation #cli #workaround
