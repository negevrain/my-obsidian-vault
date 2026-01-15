---
categories:
  - "[[People]]"
people_type:
  - client
client_type: individual
company:
  - - Company-XYZ
contact_name:
contact_email:
contact_phone:
client_status: Active
health_score:
Client Services: Coaching
billing_rate:
start_date:
next_follow_up: 2025-01-15
tags:
  - client
---
# David Miles

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


[[David Miles - 20221021 - Coaching Session Notes|David Miles - 20221021 - Coaching Session Notes]]

[[David Miles - Session Notes|David Miles - Session Notes]]

[[David Miles - Session Notes 2|David Miles - Session Notes 2]]

[[David Miles - Session Notes 1|David Miles - Session Notes 1]]

[[David Miles - Email re Sheldon|David Miles - Email re Sheldon]]

[[David Miles - Chronological Report on Statements Pertaining to Aquiess' Weather Modification Efforts|David Miles - Chronological Report on Statements Pertaining to Aquiess' Weather Modification Efforts]]

[[David Miles - Business Plan of Sorts|David Miles - Business Plan of Sorts]]

[[David Miles - A few suggestions from today|David Miles - A few suggestions from today]]

[[Session Notes_ Sheldon Roger’s|Session Notes_ Sheldon Roger’s]]

[[David Miles - Primary Tasks|David Miles - Primary Tasks]]

[[Session Notes_ David Miles|Session Notes_ David Miles]]

[[Miles Research Team Meeting|Miles Research Team Meeting]]

[[Miles Research Automations|Miles Research Automations]]

[[Consulting Brief for Miles Research|Consulting Brief for Miles Research]]