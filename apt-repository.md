<h1 style="text-align:center">
    <b>APT REPOSITORYS MANAGEMENT</b>
</h1>

## **APT KEYS**
```bash
sudo apt-keys list # list all the keys
sudo apt-keys remove [keyID] # remove a key
sudo apt update # update the repository list
```

## **APT REPOSITORYS**
- Path: /etc/apt/
```bash
sudo nano sources.list # edit the main repositorys
ls sources.list.d/ # see the PPA repository added
```
