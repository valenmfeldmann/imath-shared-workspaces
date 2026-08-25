# iMath Shared Workspaces

Public host for iMath workspace files, shared by users (often via a
live Claude Code session connected to a running iMath instance) so
they can be pulled onto any machine with network access -- no git, no
Claude Code, and no access to the iMath source repo required to open
one.

Unrelated to the iMath application source code itself, and intended to
work the same way against a compiled/packaged build as it does against
a dev checkout.

## Layout

Each shared workspace is a single `.json` file under `workspaces/`,
named `<slug>-<YYYYMMDD-HHMMSS>.json`.

## Opening a shared workspace

From inside iMath: **Open Workspace → Shared** tab lists everything
here; clicking one downloads and opens it directly.

Manually: download the raw file from this repo (e.g. via the "Raw"
button on GitHub, or `curl`) and open it via iMath's normal
File → Open.
