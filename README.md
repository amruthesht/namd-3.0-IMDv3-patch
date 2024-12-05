# NAMD-3.0 IMDv3 patch

This repository contains the diff file required to apply a pathc to the source code of NAMD to enable the new IMDv3 protocol. The patch has been designed for and tested on the [NAMD 3.0](https://www.ks.uiuc.edu/Research/namd/3.0/announce.html) source code.

We encourage the user to register for and download the NAMD 3.0 source code from the [NAMD website](https://www.ks.uiuc.edu/Development/Download/download.cgi?UserID=&AccessCode=&ArchiveID=1712). This patch can then be applied to the source code to enable the new IMDv3 protocol.

More information about NAMD and how to use it can be found [here](https://www.ks.uiuc.edu/Research/namd/). Information on the IMDv3 protocol can be found [here](https://imdclient.readthedocs.io/en/latest/protocol_v3.html).

## Patching the source code

To apply the patch, download the NAMD source code and navigate to the root directory of the source code. Then, apply the patch using the following command:

```
  cd /path/to/namd-3.0-source-repo
  patch -p1 < /path/to/namd-3_0-IMDv3.diff
```

Once this is done, the source code will be patched with the new IMDv3 protocol.

The compile and build instructions in `IMDv3-dev.md` can then be followed to build the NAMD binary.