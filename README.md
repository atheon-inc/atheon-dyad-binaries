# atheon-dyad-binaries

This repo (https://github.com/atheon-inc/atheon-dyad-binaries) provides binary releases of Dyad's Apache 2 part with Atheon integrated into it.
It is being maintained to keep track of releases only.

In the case of any issues with dyad, please check/report at https://github.com/dyad-sh/dyad/issues.


> NOTE: Because right now our application to be part of Apple Developer Program is in progress, our version is will be blocked by macOS's Gatekeeper. To resolve this, you need remove the `quarantine attribute` from the app via:
> ```bash
> $ xattr -dr com.apple.quarantine /path/to/dyad.app
> ```
> This is a one time operation.
