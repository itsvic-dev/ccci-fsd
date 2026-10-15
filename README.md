# ccci-fsd

Modem NVRAM file service for the MT6739 CCCI `ccci_fs` port, used by the AGM M7 NixOS and LineageOS ports.

```
ccci-fsd /dev/ccci_fs <data dir>
```

The protocol is in [CCCI-FS.md](https://github.com/itsvic-dev/nixos-agm-m7/blob/main/docs/CCCI-FS.md).

- NixOS: `package.nix`.
- LineageOS: `Android.bp`, check out as `external/ccci-fsd`.
