#  Some useful Linux Commands used Frequently

## Install package from tar.xz file

```bash
tar -xf filename.xz
cd filename
./configure
make
sudo make install
```
## Kill all user processes

```bash
pkill -u <username>

```
## New Repository Setup

``` bash
echo "# healthblock" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Aniket1298/healthblock.git
git push -u origin main
```
