# slock-sleep-unit
Screen service lock after sleep

# Install
* Add files to ```~/.config/systemd/user/```
* Enable service ``` systemctl --user enable slock-sleep.service```
* Check if service is enable (should save vendor preset: enabled) ``` systemctl --user status slock-sleep.service ```
