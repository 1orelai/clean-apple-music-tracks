# clean-apple-music-tracks

An AppleScript CLI tool for stripping tags, featured artists, or custom patterns from track titles in a given album using the macOS Music app.

## Requirements

- **`macOS`** (10.15 Catalina or newer)
- **`macOS Music app`**
- **`osascript`** (built into macOS)

## Usage

```text
clean-apple-music-tracks -a <ALBUM> -p <PATTERN> [-r <ARTIST>] [-d]

Options:
  -a, --album    (Required) Album title to clean up.
  -p, --pattern  (Required) Perl-compatible regex pattern to remove.
  -r, --artist   (Optional) Filter tracks by specific artist.
  -d, --dry-run  (Optional) Preview title changes without modifying the Apple Music library.
  -h, --help     Show this help message.
```
