# bridgit
Bridgit — AI-first construction workforce planning (Bench) from Kitchener, Ontario

## API
- **[Bridgit Bench API](https://gobridgit.com/bridgit-bench-api-documentation/)** — REST API (OpenAPI 3.0) covering accounts, projects, people, roles, allocations, phases, certifications, custom fields, groupings, notes, tasks, attachments, workforce spend reports, and user administration.
  - Base URL: `https://bench.gobridgit.com/rp/api/v1/`
  - Auth: OAuth bearer tokens via `POST /auth/signin` (service account) + refresh via `POST /auth/token`
  - Swagger: <https://bench.gobridgit.com/rp/swagger/index.html>
  - Spec: [`openapi/bridgit-bench-openapi.yml`](openapi/bridgit-bench-openapi.yml)

## Integrations
- **CRM**: Salesforce, HubSpot, Microsoft Dynamics, Unanet CRM, Zoho, Pipedrive
- **HRIS / ERP**: Workday, BambooHR, UKG, Oracle, ADP, Namely
- **Project Management**: Procore, Autodesk Build, CMiC, Trimble
- **Data / Productivity**: Snowflake, Microsoft Office 365

## Links
- Website: <https://gobridgit.com>
- Bridgit Bench: <https://gobridgit.com/bridgit-bench/>
- Integrations: <https://gobridgit.com/integrations/>
- GitHub: <https://github.com/Bridgit>
- LinkedIn: <https://www.linkedin.com/company/bridgit>
