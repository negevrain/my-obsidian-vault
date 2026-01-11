## All Recipes

```dataview
TABLE WITHOUT ID file.link AS "Name", tags AS "Tags", link AS "Link"
FROM "2. Personal Hub/Recipes"
WHERE file.name != this.file.name
SORT file.name ASC