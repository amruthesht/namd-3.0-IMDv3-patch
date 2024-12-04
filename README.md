# NAMD-3.0 IMDv3 patch

This repository contains the diff file required to apply a pathc to the source code of NAMD to enable the new IMDv3 protocol. The patch is based on the NAMD 3.0 source code.

We encourage the user to register for and download the NAMD source code from the [NAMD website](http://www.ks.uiuc.edu/Research/namd/). This patch can then be applied to the source code to enable the new IMDv3 protocol.

## Patching the source code

To apply the patch, download the NAMD source code and navigate to the root directory of the source code. Then, apply the patch using the following command:

```
  cd /path/to/namd-3.0-source-repo
  git apply /path/to/namd-3_0-IMDv3.diff
```

Once this is done, the source code will be patched with the new IMDv3 protocol.

Then, compile and build instructions in `IMDv3-dev.md` can be followed to build the NAMD binary.