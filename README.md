# kinesis-ad2-keymap
設定を反映
sudo systemd-hwdb update && sudo udevadm trigger

反映されたのを確認するl.
udevadm info /dev/input/by-path/* | grep KEYBOARD_KEY

/etc/udev/hwdb.d/keymap.hwdb  にファイルを置く