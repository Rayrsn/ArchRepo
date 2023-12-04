Add the following repo to your `/etc/pacman.conf`:

```ini
[rayr]
SigLevel = Never
Server = https://rayr.link/repo/$arch
```

* Alternatively you can copy and paste the following command into your terminal:

```bash
echo '

[rayr]
SigLevel = Never
Server = https://rayr.link/repo/$arch ' | sudo tee -a /etc/pacman.conf

sudo pacman -Syyu
```