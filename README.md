# Bash Shortcuts Tearcher
This repo contains simple bash bindings that help to learn the proper bash emacs like shortcuts.
So instead of ↑ poweruser should use `CTRL`+`p`.
Current implementatation add the message to the currently edited line.

Ckurrently supported shortcuts are:
- `↑` - informs about `CTRL` + `p`
- `↓` - informs about `CTRL` + `n`
- `←` - informs about `CTRL` + `f` or `ALT` + `f`
- `→` - informs about `CTRL` + `b` or `ALT` + `b`
- `home` - informs about `CTRL` + `e`
- `end` - informs about `CTRL` + `a`

## Automatic installation
These bindings can be automatically installed with these simple scripts:
```
curl https://github.com/AlexBaranowski/bash-shortcuts-teacher/raw/master/bash-shortucts-teacher.sh | tee -a ~/.bashrc
```
## License
See LICENSE file.
