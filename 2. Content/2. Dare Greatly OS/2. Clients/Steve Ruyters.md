---
categories:
  - "[[People]]"
people_type:
  - client
status: Active
company:
  - - Company-XYZ
contact_name:
contact_email:
contact_phone:
next_follow_up: 2025-01-15
tags:
  - radio
client_services: Supervision
---
# Steve Ruyters

## Overview
- Industry: Radio / Fundraising
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
FROM "3. Meetings & Sessions"
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

[[Steve Ruyters - Session Notes|Steve Ruyters - Session Notes]]

[[Steve Ruyters - Session Notes Transcript|Steve Ruyters - Session Notes Transcript]]

[[Steve Ruyters - Session Notes 1|Steve Ruyters - Session Notes 1]]


