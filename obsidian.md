```
date:
tags:
desc: test
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
TABLE type, layer, network, start
FROM "Crp/Pro"
WHERE type != "waitlist" AND my_sort = 1
sort my_sort asc
```

```dataview
LIST
FROM "Crypto/Project"
LIMIT 5
```


