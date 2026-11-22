# PJOS RG34XX Cloud Backup

- **Device**: `rg34xx`
- **Last Backup**: `2026-11-22 11:22:44`
- **Game Saves**: 31 files (unencrypted under `saves/`)
- **Encrypted Configs**: `configs_encrypted/pjos_configs.tar.gz.age` (encrypted with recipient `age1pnwtvfcatd2rkyrpw2f64f50qskmddn30zzz8u35smg3h8ufq57shfls66`)

To restore encrypted configs:
```sh
age -d -i age.key configs_encrypted/pjos_configs.tar.gz.age | tar -xz
```
