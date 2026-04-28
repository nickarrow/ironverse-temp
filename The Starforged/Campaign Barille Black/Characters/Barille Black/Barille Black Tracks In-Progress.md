
```dataview
TABLE WITHOUT ID file.link as "Vows"
FROM "The Starforged/Campaign Barille Black/Progress/Barille" and #incomplete
WHERE track-type = "Vow"
WHERE character = [[Barille Black]]
SORT file.mtime DESC
```

```dataview
TABLE WITHOUT ID file.link as "Tracks"
FROM "The Starforged/Campaign Barille Black/Progress/Barille" and #incomplete
WHERE track-type != "Vow"
WHERE track-type != "Connection"
WHERE iron-vault-kind != "clock"
WHERE character = [[Barille Black]]
SORT file.mtime DESC
```