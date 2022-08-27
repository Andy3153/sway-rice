# The `etc` folder

I store other stuff/configurations I use with the Sway rice in here.

## `sway@.service` -- SystemD service file to autostart Sway

This autostarts Sway on TTY1 if you, for example, already have an encrypted root and don't want to type passwords twice when booting up, or, if you just don't want to type any passwords at all (I don't recommend that).

### Installation:
After you cloned the repo, you need to copy the service file and enable it:

```bash
cd sway-rice/etc/
sudo cp sway@.service /usr/lib/systemd/system
sudo systemctl enable sway@$USER
```

Now, you can start it (make sure you're not logged into TTY1), or just `reboot` your machine and have it start automatically.
