```
date:
tags:
desc: test
hp:
```

Obsidian

all files in your vault:

```dataview
LIST
```

```dataview
TASK
FROM ""
WHERE file.name = "crp_Task"
LIMIT 6
```

```dataview
TABLE
file.name as "Title",
file.folder as "Folder",
file.tags as "tags"
FROM "Crypto/Project"
LIMIT 5
```

```dataview
LIST
FROM "Crypto/Project"
LIMIT 5
```
