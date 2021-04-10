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
## Give File Root access

```
sudo chown root:root <file name>
```

## Remove root access from a file

```
sudo chown -R $USER <file name>
```

##  Virtual Environment
```
1.Create 
	virtualenv <virtualenvname>
2.Activate
	 source <virtualenvname>/bin/activate
3.Deactivate
	deactivate
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
