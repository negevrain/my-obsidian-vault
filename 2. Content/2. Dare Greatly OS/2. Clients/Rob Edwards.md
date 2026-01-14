---
client_type: individual
name: Rob Edwards
Client Services: Supervision
client_status: Active
health-score: 85
tags:
  - client
  - active
date-added: 26/12/2025
company:
  - - Company-XYZ
contact_name:
contact_email:
contact_phone:
next_follow_up: 2025-01-15
---
# Rob Edwards

## Overview
- Industry: Pastor
- Key goals: 
- Relationship notes: 

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

TABLE file.ctime AS "Date", summary AS "Summary"
FROM "3. Dare Greatly OS/3. Meetings & Sessions"
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

[[Rob Edwards - Session Notes|Rob Edwards - Session Notes]]

[[Rob Edwards - Care Calls|Rob Edwards - Care Calls]]