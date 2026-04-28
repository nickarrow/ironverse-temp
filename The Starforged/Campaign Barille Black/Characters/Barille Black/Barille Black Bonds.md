
```dataview
TABLE WITHOUT ID file.link as "Bonds"
FROM "The Starforged/Campaign Barille Black/Progress/Barille" and #incomplete
WHERE track-type = "Connection"
WHERE character = [[Barille Black]]
SORT file.mtime DESC
```