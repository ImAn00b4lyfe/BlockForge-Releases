# BlockForge Desktop Releases

This public repository hosts **compiled Windows installers and update metadata only**. BlockForge's source code stays in the private `ImAn00b4lyfe/Block-Forge` repository.

Once published, [download the latest Windows release](https://github.com/ImAn00b4lyfe/BlockForge-Releases/releases). The desktop updater will check this repository's releases for `latest.yml`, the Windows installer (`.exe`), and any generated `.blockmap` files.

**Status:** The public release feed is being configured. No installer has been published yet.

## Mod build workflow

`.github/workflows/build-mod.yml` compiles the Minecraft mods that BlockMod's AI generates (public repositories get free GitHub Actions minutes). Each run receives a generated project as its input, builds it with Gradle, and sends the finished jar to BlockMod's own storage; nothing is kept in GitHub. Run logs and inputs here are public.

Do not upload source code, signing keys, secrets, or credentials here.
