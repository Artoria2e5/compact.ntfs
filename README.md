# compact.ntfs
Tool and C-API library for compacting a file on ntfs-3g

## How

We feed the data to [wimlib](https://wimlib.net/) (LGPLv3). Done.

## License

GPLv2, because:
* Took the structs and the handling from https://github.com/ebiggers/ntfs-3g-system-compression
* Will link to libntfs-3g. You can write obscure macros to use xattr or something instead.
