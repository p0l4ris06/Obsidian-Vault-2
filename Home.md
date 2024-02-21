
---
## [](https://github.com/TfTHacker/DashboardPlusPlus/blob/master/Dashboard%2B%2B.md#vault-info)Vault Info
- 🗄️ Recent file updates `$=dv.list(dv.pages('').sort(f=>f.file.mtime.ts,"desc").limit(5).file.link)`
- 〽️ Stats
    - File Count: `$=dv.pages().length`

## Backlog
```dataview
list from #Backlog 
```