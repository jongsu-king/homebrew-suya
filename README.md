# Homebrew tap for SUYA

[SUYA](https://github.com/jongsu-king/SUYA) collects Antarctic ocean temperature, salinity and air temperature from public APIs into SQLite and monthly Excel workbooks and shows them on a south-polar map.

```bash
brew install --cask jongsu-king/suya/suya
```

The app is not notarized, so macOS blocks the first start. Right-click SUYA in Applications and choose Open, or allow it under System Settings > Privacy & Security. SUYA updates itself after that.

`brew uninstall --cask suya` removes the app and keeps your data. `brew uninstall --zap --cask suya` also deletes the database and settings in `~/Library/Application Support/SUYA`. Excel workbooks in `~/Documents/SUYA` stay.
