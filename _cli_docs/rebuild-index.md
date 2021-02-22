---
layout: single
permalink: /cli/rebuild-index/
sidebar:
  nav: "cli-docs"
---

# maestral rebuild-index

Rebuild the sync index.

Rebuilding the index may take several minutes, depending on the size of your Dropbox.
Any changes to local files will be synced once rebuilding has completed. If the daemon is
stopped during the process, rebuilding will start again on the next launch. If the daemon
is not currently running, a rebuild will be scheduled for the next startup.

### Syntax

```
maestral rebuild-index [OPTIONS]
```

### Options

```
-c, --config-name CONFIG  Run command with the given configuration.
--help                    Show this message and exit.
```