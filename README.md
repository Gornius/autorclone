# Autorclone - mount your defined remote drives in one command!

It's a mini-tool written by me to save me 2 second every time I mount a drive on average.

Uses config file (see `arcl.conf.default` for more details) in `$HOME/.conf/arcl.conf` to define remotes and their mountpoints, mounting them to `$HOME/MountedDrives/`

The only dependency you need is working `rclone`, obviously.

# Usage

1. To make it more convenient, put `arcl` somewhere in your path.

2. Define your remotes using `rclone config`

3. Create a new file in your `$HOME/.config/arcl.conf` or copy `arcl.conf.default` (see `arcl.conf.default` for example config).

4. To mount a drive type `arcl ALIAS`, to unmount a drive type `arcl ALIAS u`

5. Your drive should appear in `$HOME/MountedDrives/MountName`
