# How To Run
```bash
systemctl --user enable /home/aqua/auto/autosync-repos.service
systemctl --user enable /home/aqua/auto/autosync-repos.timer

systemctl --user start autosync-repos.service
systemctl --user status autosync-repos.service
```
