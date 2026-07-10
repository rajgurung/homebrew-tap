# StaffOS Homebrew Tap

Homebrew tap for the [StaffOS](https://github.com/rajgurung/staffOS) CLI.

## Install

```sh
brew install rajgurung/tap/staffos
```

Or tap first, then install:

```sh
brew tap rajgurung/tap
brew install staffos
```

## Usage

```sh
staffos login     # enter your StaffOS endpoint and API token
staffos init      # connect the current project (installs Claude Code hooks)
staffos status    # show connection and recent activity
staffos help
```

The formula is generated from the source of truth in
[`packaging/homebrew/staffos.rb`](https://github.com/rajgurung/staffOS/blob/main/packaging/homebrew/staffos.rb).
