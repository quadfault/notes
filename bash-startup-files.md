# Bash startup files

This applies for my system (Arch Linux) only. Might be different elsewhere.

Startup files read for **(non-)interactive login shells**, in order:

1. /etc/profile
2. /etc/bash.bashrc (ignored if not interactive)
3. ~/.profile
4. ~/.bashrc (ignored if not interactive)

Startup files read for **interactive non-login shells**, in order:

1. /etc/bash.bashrc
2. ~/.bashrc

Non-interactive, non-login shells (used for scripts) do not source anything.
