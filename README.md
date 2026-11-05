# droidtop-plugin-oldversions
droidtop source plugin: older versions of free software and freeware (OldVersion.com first, then GitHub/GitLab releases and other archives). Droidtop/tracker#647

## Branches

The owner, 2026-11-05: "ALL plugins should keep the recipe on plugin-core, overlaid onto the release branch when
needed. That's our standard operation." This plugin has no upstream project, so its one branch is **`plugin-core`**
(the default branch): the whole recipe. Every change lands on it through a `ci/` branch, and releases are built
from it. There is no `main` or `master`.
