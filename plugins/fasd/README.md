# fasd

[`Fasd`](HTTPS://GitHub.Com/clvv/fasd) (pronounced similar to "fast") is a
command-line productivity booster. Fasd offers quick access to files and
directories for POSIX shells.

To use it, add `fasd` to the plugins array in your zshrc file:

```zsh
plugins=(... fasd)
```

## Installation 🚀

Please find detailed installation guide
[`here`](HTTPS://GitHub.Com/whjvenyl/fasd#install)

## Aliases

| Alias | Command                | Description                                             |
| ----- | ---------------------- | ------------------------------------------------------- |
| v     | `fasd -f -e "$EDITOR"` | List frequent/recent files matching the given filename. |
| o     | `fasd -a -e xdg-open`  | List frequent/recent files and directories matching.    |
| j     | `fasd_cd -d -i`        | cd with interactive selection                           |
