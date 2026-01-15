---
Status: Active Client
Services:
  - Supervision
client_type: individual
company:
  - - Company-XYZ
contact_name:
contact_email:
contact_phone:
client_status: Active
health_score:
Client Services:
billing_rate:
start_date:
next_follow_up: 2025-01-15
tags:
  - client
---
# Josh Lane

## Overview
- Industry: (insert text)
- Key goals: (insert text)
- Relationship notes: (insert text)

---
## Related Knowledge
```dataview
LIST
FROM "5. Knowledge Vault"
WHERE contains(clients, this.file.link)
SORT file.mtime DESC
````
---
## Meetings & Sessions

```dataview

TABLE dateformat(Session_Date, "yyyy-MM-dd") AS "Date", summary AS "Summary"
FROM "2. Content/2. Dare Greatly OS/3. Meetings & Sessions"
WHERE contains(client, this.file.link)
SORT file.ctime DESC
```
---
## Projects & Deliverables
```dataview
LIST
FROM "4. Projects & Deliverables"
WHERE contains(client, this.file.link)
SORT file.mtime DESC
```
---
## Quick Notes / Timeline

- (insert text)