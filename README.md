# MacDisk — downloads and support

This repository is where MacDisk is distributed. It holds the downloads, the
update feed, and the issue tracker. The app's source lives in a separate,
private repository.

> **This is not the original MacDisk.** It is a fork of
> [colinvkim/MacDisk](https://github.com/colinvkim/MacDisk) by Colin Kim, used
> under the MIT License. The original is free and open source, and you can get
> it from [trymacdisk.app](https://trymacdisk.app) or with
> `brew install --cask macdisk`. That Homebrew cask installs the original, not
> this fork.

## Downloads

**There are no releases yet.** When there are, they will appear under
[Releases](../../releases) as a signed and notarized `.dmg`.

MacDisk requires macOS Sonoma 14 or later.

## What MacDisk does

A native macOS disk space analyzer. Point it at a folder or volume and it shows
where the space went — sunburst and treemap views, a searchable file browser,
comparison between scans over time, and a Discard Pile for reviewing cleanup
candidates before anything is moved to the Trash.

Scanning and reviewing the Discard Pile are free. Moving items to the Trash
requires a license.

## Privacy

MacDisk does not phone home. License keys are verified offline on your Mac,
scan results never leave the machine, and usage statistics are stored locally.

## Reporting a problem

Open an [issue](../../issues). Please include your macOS version, the MacDisk
version from **MacDisk → About MacDisk**, and what you were doing at the time.

## Automatic updates

MacDisk uses [Sparkle](https://sparkle-project.org/) for updates. The feed will
be published at `appcast.xml` from this repository once there is a release to
serve. Updates are currently disabled in the app.

## License

MacDisk is available under the [MIT License](LICENSE), which covers both the
original work and this fork.
