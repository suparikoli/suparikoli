### Manoj — Mithtech

Building open-source ERP and commerce systems at [Mithtech](https://mith.tech) — Frappe, ERPNext, Medusa.js, n8n. Open-source is the default here, not a fallback.

**Elsewhere:** [mith.tech](https://mith.tech) · [Mithtech-Bengaluru](https://github.com/Mithtech-Bengaluru) · [LinkedIn](https://www.linkedin.com/company/mithtech-is)

#### What I build

| Repo | What it is |
| --- | --- |
| [Pulse](https://github.com/mithtech-is/Pulse) | Agile project management inside Frappe/ERPNext — sprints, Kanban, epics, OKRs, retros, timesheets. MIT |
| [polygin](https://github.com/suparikoli/polygin) | WhatsApp Business integration for ERPNext |
| [smartflo](https://github.com/suparikoli/smartflo) | Smartflo telephony integration for ERPNext |
| [ntfynext](https://github.com/suparikoli/ntfynext) | Notification layer built on ntfy |
| [medusync](https://github.com/suparikoli/medusync) | ERPNext ↔ Medusa.js sync |

#### Upstream

Fixes sent back to the projects Mithtech implements, not just around them:

- [medusajs/medusa#16416](https://github.com/medusajs/medusa/pull/16416) — RegExp route matchers matched inconsistently and cached the wrong result
- [medusajs/medusa#16418](https://github.com/medusajs/medusa/pull/16418) — wildcard cache invalidation compiled a key straight into a regex instead of a glob
- [medusajs/medusa#16417](https://github.com/medusajs/medusa/issues/16417) — same root cause reachable through CORS configuration
- [frappe/frappe#41827](https://github.com/frappe/frappe/pull/41827) · [#41828](https://github.com/frappe/frappe/pull/41828) — a base-class arity mismatch and a frozen loop condition
- [frappe/erpnext#57705](https://github.com/frappe/erpnext/issues/57705) — five reports were mislabelling their Yearly column
