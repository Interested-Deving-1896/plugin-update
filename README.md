[update-readmes]   Mode: rewrite — migrating to template structure...
# plugin-update

[![Built with Ona](https://ona.com/build-with-ona.svg)](https://app.ona.com/#https://github.com/Interested-Deving-1896/plugin-update)

<!-- AI:start:what-it-does -->
_Description pending._
<!-- AI:end:what-it-does -->

## Architecture

<!-- AI:start:architecture -->
_Architecture documentation pending._
<!-- AI:end:architecture -->

## Install

<!-- Add installation instructions here. This section is yours — the AI will not modify it. -->

```bash
git clone https://github.com/Interested-Deving-1896/plugin-update.git
cd plugin-update
```

## Usage

<!-- Add usage examples here. This section is yours — the AI will not modify it. -->

## Configuration


### Update Check Interval

You can customize how often the plugin checks for updates by adding the `autoupdate.debounce` configuration to your `package.json`:

```json
{
  "oclif": {
    "update": {
      "autoupdate": {
        "debounce": 7
      }
    }
  }
}
```

The `debounce` value is the number of days between update checks for all channels. When set, it overrides the default behavior for all channels.

If not configured, the plugin defaults to:

- Stable channel: 14 days
- Other channels: 1 day

# Commands

<!-- commands -->

- [`oclif-example update [CHANNEL]`](#oclif-example-update-channel)

## CI

<!-- AI:start:ci -->
_CI documentation pending._
<!-- AI:end:ci -->

## Mirror chain

<!-- AI:start:mirror-chain -->
This repo is maintained in [`Interested-Deving-1896/plugin-update`](https://github.com/Interested-Deving-1896/plugin-update) and mirrored through:

```
Interested-Deving-1896/plugin-update  ──►  OpenOS-Project-OSP/plugin-update  ──►  OpenOS-Project-Ecosystem-OOC/plugin-update
```

Changes flow downstream automatically via the hourly mirror chain in
[`fork-sync-all`](https://github.com/Interested-Deving-1896/fork-sync-all).
Direct commits to OSP or OOC are detected and opened as PRs back to `Interested-Deving-1896`.
<!-- AI:end:mirror-chain -->

## Contributors

<!-- AI:start:contributors -->
_Contributors pending._
<!-- AI:end:contributors -->

## Origins

<!-- AI:start:origins -->
_Original project — no upstream fork._
<!-- AI:end:origins -->

## Resources

<!-- AI:start:resources -->
_No additional resource files found._
<!-- AI:end:resources -->

## License

<!-- AI:start:license -->
[MIT](https://github.com/Interested-Deving-1896/plugin-update/blob/main/LICENSE) © 2026 [Interested-Deving-1896](https://github.com/Interested-Deving-1896)
<!-- AI:end:license -->
