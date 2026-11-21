# t3+ Portable

A custom theme for T3 Code desktop and self-hosted web clients. It includes the blue pixel glow, translucent composer, and title-first sidebar styling.

## Install

Copy `t3plus-portable.json` and `t3plus-portable.png` into the T3 server's themes directory, usually `~/.t3/userdata/themes/`. Keep both filenames so T3 can pair the image with the theme. Select **t3+ Portable** in **Settings → Appearance** in Dark mode.

If your server has the T3 theme CLI, you can apply the theme with:

```sh
t3 theme set t3plus-portable
```

Sidebar CSS can render differently across Stable and Nightly builds. The portable theme uses T3's built-in usage display.

## Credits and license

This is a theme adaptation of [Alex Wang's t3+](https://github.com/alextyhwang/t3plus). See [LICENSE](LICENSE) for the original copyright notice and PolyForm Noncommercial 1.0.0 terms.
