# IDD — Ideate, Debate, Discuss

idd puts Claude Code into talk-only mode for a single message. End your message with `idd` and Claude will ideate, debate trade-offs, and plan with you, but it won't write code, edit files, or run commands that change your code.

Use it when you want to think an idea through before anything gets built. To check whether a specific design will actually hold up, see [rvr](https://github.com/ambareeshav/rvr).

## Install

Inside Claude Code:

```
/plugin marketplace add ambareeshav/claude-plugins
/plugin install idd@ambareeshav
```

This adds [all my plugins](https://github.com/ambareeshav/claude-plugins) as one marketplace. To add only this repo instead, use `/plugin marketplace add ambareeshav/idd` and `/plugin install idd@idd`.

## Use

End your message with `idd`, e.g.

> Should uploads go straight to blob storage, or through the API first so we can validate them? idd

Only messages that end with `idd` are affected. Your next message without it goes back to normal.

## Install from the terminal

```
claude plugin marketplace add ambareeshav/claude-plugins
claude plugin install idd@ambareeshav
```
