# hk4e-patch-universal

### Genshin Impact encryption patch that should work on 6.5 and forward for a while
### I have already removed the proxy forwarding, so I need to use another tool for proxying myself, and the connection to the server will not be abnormal due to the built-in proxy forwarding.

### Patching the game
- Install [**Rust**](https://rust-lang.org/learn/get-started/) and **Cargo** (comes with rustup)
- Go to the `patch/` folder (make sure you have cloned this repository with the `--recurse-submodules` flag)
- Run `cargo build --release` to build the DLL at `target/release`
- Inject the DLL into the game. You can do this by renaming the patch to `Astrolabe.dll` and putting it in the game folder at `GenshinImpact_Data/Plugins`. Make sure you back up the old `Astrolabe.dll` in the plugins folder.

## Credits
[xeondev](https://git.xeondev.com/reversedrooms/hk4e-patch) for the original patch and [oureveryday](https://github.com/oureveryday/) for the original hk4e-patch-universal
