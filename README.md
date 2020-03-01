# Description

It is a virtual FUSE filesystem that replaces
`sia://...` symlinks with readonly remote files.

# Support

FUSE and MacFUSE.

# Usage
```
mkdir ~/t/mnt
python fs.py /root-dir ~/t/mnt
```
