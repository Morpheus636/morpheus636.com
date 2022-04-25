---
categories: Redownload
---

# Redownload V0.1.0 Released
Good news! Redownload is no longer in alpha and is ready for it's first beta release. 

## What does this mean?
It means that our minimum viable product, the initial CLI, is at a stable point and we will begin
working to develop additional features, like support for hosts other than archive.org, and a GUI so
users don't have to use a command line at all. These additional features will be included in the first "major release",
v1.0.0.

If you didn't see the Project Announcement, or are just seeing Redownload for the first time, Redownload is an automated
tool for downloading music from Relisten. Relisten works by playing music from various other hosts, and at this time, we support
only tracks hosted on archive.org. Redownload also works for downloading stream-only tracks directly from archive.org, all you
have to do is provide an archive.org link instead of a relisten link.

The builds for this version can be found [Here](https://github.com/Morpheus636/redownload/releases/tag/v0.1.0), and usage and installation documentation can be found [Here](https://github.com/Morpheus636/redownload/blob/v0.1.0/docs/usage.md). Contact me through my [Discord Server](https://discord.morpheus636.com) or [Forums](https://morpheus636.com/forums) for help and feedback, or open a [GitHub Issue](https://github.com/Morpheus636/redownload/issues) in the repository for bugs and feature requests.

## Patch Notes for Redownload v0.1.0
The following changes were implimented between v1.1.0a2 and the current release:
- Fixed a bug which caused redownload to overwrite a file if you downloaded another with the same name - it now throws an error.
- Added a -v or --version flag to the CLI's syntax.

