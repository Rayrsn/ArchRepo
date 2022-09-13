Add the following repo to your `/etc/pacman.conf`:

```ini
[rayr]
SigLevel = Never
Server = https://rayr.ml/repo/$arch 
Server = https://rayrsn.github.io/ArchRepo/$arch
```

* Alternatively you can copy and paste the following command into your terminal:

```bash
echo '

[rayr]
SigLevel = Never
Server = https://rayr.ml/repo/$arch 
Server = https://rayrsn.github.io/ArchRepo/$arch ' | sudo tee -a /etc/pacman.conf

sudo pacman -Syyu
```
