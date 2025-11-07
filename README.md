# Hostname

created with

```bash
wget  https://kojipkgs.fedoraproject.org//packages/hostname/3.23/8.fc38/src/hostname-3.23-8.fc38.src.rpm
rpmdev-extract hostname*src.rpm
cd hostname*
tar xvf hostname_3.23.tar.gz
rm hostname_3.23.tar.gz
git init
git add .
git commit -m 'init clone of the fedora hostname with sources unpacked'
git branch -M master
git remote add origin git@github.com:AlexBaranowski/hostname.git
git push -u origin master
```
