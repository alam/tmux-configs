# Overview

A easy to use tmux configuration with basic mouse and system clipboard. This
configuration aims to simplify the navigation between sessions, windows, and
panes, creation of workspaces, and copy-pasting with OS integration. It tries to
do this all minimally.

# Table of Contents

- Requirements
- Installation
- Key Bindings
- Recommendations

# Requirements

tmux version 2.9a or above

You will need to have the following items installed on your system before making
use of this configuration.

- A program to interact with the system clipboard:

    - Linux: install `xsel`
    ```plaintext
    apt-get install xsel --no-install-recommends
    ```

    - macOS: `pbcopy`

# Installation

## macOS

To enable support for the meta key and shift modifer in `Terminal.app`, you will
need to do the following.

1. Enable Meta key and scroll support
    1. Open `Terminal.app`.
    2. Select `Terminal > Preferences` from the menu bar.
    3. Select the `Profiles` tab from the preferences window.
    4. In the pane on the left, select the profile marked with the text
    "Default" under the profile name.
    5. Select the `Keyboard` tab in the from the
    6. Enable the following options from the bottom of the <>:
        - `Use Option as Meta key`
        - `Scroll alternate screen`
2. Add correct keycodes for Shift modifiers.
    1. Select the `+`.

# Key Bindings

## Prefix Keys

`C-a`: enter command mode.

`C-s`: enter copy mode.

## Session Management

`<prefix> d`: detatch from session.

`<prefix> s`: list all sessions. Can also select a session to connect to by
              navigating with the arrow keys and selecting with enter.

`<prefix> (`: previous session
`<prefix> )`: next session


## Window/Pane Management

# Recommendations

## Use `Caps Lock` as `Control`

### macOS
