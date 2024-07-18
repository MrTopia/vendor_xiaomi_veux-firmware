# Firmware tree for `Veux`

## What is this?

A firmware tree to ship firmware with builds for the POCO X4 Pro 5G / Redmi Note 11E Pro / Redmi Note 11 Pro 5G / Redmi Note 11 Pro+ 5G (peux/veux).

# Getting started

First of all, ensure you have cloned this into
`vendor/xiaomi/veux-firmware`.

Cloning:

```bash
git clone https://gitea.com/Karan-Frost/vendor_xiaomi_veux-firmware.git vendor/xiaomi/veux-firmware -b main --depth=1
```

> These are example entries, you need to replace the relevant stuff
> with your own case.

After that, ensure your tree's BoardConfig inherits this tree's BoardConfigVendor:

```makefile
include vendor/xiaomi/veux-firmware/BoardConfigVendor.mk
```

> These kinds of includes are typically placed along with other
> inherits at the beginning of BoardConfig or at the end of
> BoardConfig, along with other includes if any.

# Additional information for geeks

## Firmware

**ROM**: HyperOS

**Version**: 1.0.5.0 TKCMIXM
