Steam Deck Tools<br>

#### Decky Loader<br>
https://github.com/SteamDeckHomebrew/decky-loader<br>

Install<br>
```
curl -L https://github.com/SteamDeckHomebrew/decky-installer/releases/latest/download/install_release.sh | sh
```
Uninstall<br>
```
curl -L https://github.com/SteamDeckHomebrew/decky-installer/releases/latest/download/uninstall.sh | sh
```

#### Steam-Deck.Shader-Cache-Killer<br>
https://github.com/scawp/Steam-Deck.Shader-Cache-Killer<br>

Run online<br>
```
curl -sSL https://raw.githubusercontent.com/scawp/Steam-Deck.Shader-Cache-Killer/main/zShaderCacheKiller.sh | bash
```

#### SteamDeckGyroDSU<br>
https://github.com/kmicki/SteamDeckGyroDSU<br>

Install<br>
```
bash <(curl -sL https://raw.githubusercontent.com/kmicki/SteamDeckGyroDSU/master/pkg/update.sh)
```
Uninstall<br>
```
$HOME/sdgyrodsu/uninstall.sh
```

#### SFTP<br>

Enable and Start<br>
```
sudo systemctl enable sshd
```
```
sudo systemctl start sshd
```

Username: deck Port:22<br>

#### NonSteamLaunchers
https://github.com/moraroy/NonSteamLaunchers-On-Steam-Deck<br>

#### rclone<br>
https://github.com/rclone/rclone<br>

Install<br>
```
sudo -v ; curl https://rclone.org/install.sh | sudo bash
```
Update<br>
```
rclone selfupdate
```
