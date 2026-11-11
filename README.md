# Deimix Hub CLI — Homebrew tap

The command-line tool for the Deimix team's hub (hub.deimix.com).

```
brew tap subbutgs/tap
brew install deimix-hub
deimix-hub --version
```

Upgrade with `brew upgrade deimix-hub`. Each version is downloaded from hub.deimix.com and checked
against the SHA-256 pinned in the formula.

The tool holds no credentials. Signing in needs a Deimix hub account (`deimix-hub login`) or a key the
hub's owner has saved on that Mac. It is of no use outside the Deimix team.
