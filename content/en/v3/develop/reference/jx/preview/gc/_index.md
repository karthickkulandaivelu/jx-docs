---
title: jx preview gc
linktitle: gc
type: docs
description: 
aliases:
  - jx-preview_gc
---

## jx preview gc

Garbage collect Preview environments for closed or merged Pull Requests

### Usage

```
jx preview gc
```

### Synopsis

Garbage collect Jenkins X preview environments. 

If a pull request is merged or closed the associated preview environment will be deleted.

### Examples

  ```bash
  # garbage collect previews
  %s gc

  ```
### Options

```
  -h, --help   help for gc
```

### SEE ALSO

* [jx preview](..)	 - Preview commands

###### Auto generated by spf13/cobra on 1-Feb-2021