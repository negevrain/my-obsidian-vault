---
categories:
  - "[[People]]"
people_type:
  - client
client_type: individual
client_status: Active
Client Services: Consulting
company:
  - - Company-XYZ
health-score: ""
contact_name:
contact_email:
contact_phone:
health_score:
billing_rate:
date-added: 27/12/2025
start_date:
next_follow_up: 2025-01-15
tags:
  - client
---
# Ray Archer

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
- 

[[Sabbath Holy To-Do List]]
