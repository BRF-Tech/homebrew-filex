# filex — Homebrew tap

[filex](https://filex.sh) is a self-hosted file manager. This tap installs it
with Homebrew on macOS and Linux.

```sh
brew install brf-tech/filex/filex        # the filex CLI and server (macOS, Linux)
brew install brf-tech/filex/filex-app    # the desktop app (macOS, Apple Silicon)
```

Update with `brew upgrade`.

**First launch on macOS.** filex is not signed with an Apple Developer ID, so
macOS blocks it the first time. Open it (or run `filex`) once, then go to
System Settings → Privacy & Security and click **Open Anyway**.

The casks in `Casks/` are written by the release pipeline of
[BRF-Tech/filex](https://github.com/BRF-Tech/filex) on every release — do not
edit them here; changes belong in that repository.

License: MIT.
