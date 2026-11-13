---
'lint-staged': patch
---

_Lint-staged_ no longer says that unstaged changes have been kept back in a patch file after it has successfully reverted to the original state. The patch file is removed during the revert, so the message pointed to a file that didn't exist.
