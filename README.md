# ga-claude-code-marketplace (DEPRECATED)

> **This repository is deprecated and will no longer be updated.** The marketplace has been merged into [cc-ga-plugins](https://github.com/FriendsOfGlobalAuth/cc-ga-plugins). Go there for up-to-date installation instructions (Claude Code, Qwen Code, and other platforms).
>
> To migrate, remove the old marketplace and follow the instructions in the new repository:
> ```bash
> claude plugin marketplace remove FriendsOfGlobalAuth/claude-code-marketplace
> ```

---

Global Auth Claude Code plugins collection for TxGlobalAuth integration workflows.

## Installation

```bash
claude plugin marketplace add FriendsOfGlobalAuth/claude-code-marketplace
```

## Available Plugins

| Plugin | Skills | Description |
|--------|--------|-------------|
| **global-auth** | `global-auth:frontend` | TxGlobalAuth widget integration — initialization, auth flows, token management, UI embedding |

## Installing Plugins

```bash
# Install global-auth plugin (includes all global-auth:* skills)
claude plugin install global-auth@ga-claude-code-marketplace --scope user
```

## Skills Reference

### global-auth:frontend

TxGlobalAuth widget integration expertise — initialization, authentication flows, token management, and UI embedding patterns.

```bash
/global-auth:frontend   # Invoke frontend integration skill
```

## Authors

Dmitry Vorobyev — [github.com/VoDmAl](https://github.com/VoDmAl)
