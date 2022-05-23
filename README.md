# RAW (RISC-V Archbuild Wrapper)

- Usage:

```bash
# Run server test, then run the asp checkout and extra-riscv64-build
./raw <PKG>

# Send the local PKGBUILD to remote, and rerun the build
./raw --rebuild <PKG>

# Download PKGBUILD at local, then exit.
# Useful for fixing rotten package when using it with --rebuild.
./raw --prepare <PKG>

# Specify a server to run the script
./raw --server <SERVER> <PKG>

# Run server test only. It will overwrite the local test result buffer.
./raw --update-server
```
