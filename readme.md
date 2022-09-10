# My Personal Arch Repo 🐧

## Instructions 📝
Add one of the following repos to your `/etc/pacman.conf`:
<details>
<summary>Github</summary>

```ini
[rayr]
SigLevel = Never
Server = https://rayrsn.github.io/ArchRepo/$arch
```

* Alternatively you can copy and paste the following command into your terminal:
```bash
echo '

[rayr]
SigLevel = Never
Server = https://rayrsn.github.io/ArchRepo/$arch ' | sudo tee -a /etc/pacman.conf

sudo pacman -Syyu
```

</details>

<details>
<summary>Self Hosted</summary>

```ini
[rayr]
SigLevel = Never
Server = https://rayr.ml/repo/$arch
```

* Alternatively you can copy and paste the following command into your terminal:
```bash
echo '

[rayr]
SigLevel = Never
Server = https://rayr.ml/repo/$arch ' | sudo tee -a /etc/pacman.conf

sudo pacman -Syyu
```

</details>

<br/>

### Programs In This Repo 📦
* currencyconverter ([Github](https://github.com/Rayrsn/currencyConverter), [AUR](https://aur.archlinux.org/packages/currencyconverter))

* discord-rpc-cli ([Github](https://github.com/Rayrsn/discord-rpc-cli), [AUR](https://aur.archlinux.org/packages/discord-rpc-cli))

* weather-cli ([Github](https://github.com/Rayrsn/weather-cli), [AUR](https://aur.archlinux.org/packages/weather-cli))

* evillimiter-patched ([Github](https://github.com/Rayrsn/evillimiter))
  * Patches include support for arrow keys running previous command and suppressing disruptive warnings.

* tuxcut ([Github](https://github.com/a-atalla/tuxcut), [ArchStrike](https://archlinux.pkgs.org/rolling/archstrike-x86_64/tuxcut-6.1-3-any.pkg.tar.xz.html))
  * This is downloaded straight from ArchStrike's repo. I just added it here for convenience.