---
title: chocolatey Notes
menu:
  notes:
    name: chocolatey
    identifier: notes-chocolatey
    weight: 10
---

{{< note title="Using Public & Corporate sources" >}}

```powershell
choco source add -n=chocolatey -s'https://chocolatey.org/api/v2/' --priority=1
choco source
choco install --source=chocolatey PackageName
```