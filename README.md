# chpy :snake:
How to change your default python version.

1) Make sure python 3 is installed and up to date:
``` shell
sudo apt-get update && sudo apt-get upgrade -y
```

2) Set up the alternative versions (Debian or Ubuntu):
```shell
sudo update-alternatives --install /usr/bin/python python /user/bin/python2.7 1
```
```shell
sudo update-alternatives --install /usr/bin/python python /user/bin/python3.7 2
```

3) To change versions use:
```shell
sudo update-alternatives --config python
```

#### If you want a simple command to swap versions use [this](https://github.com/librarysteve/chpy/blob/master/chpy) little bash script!
Place it on your path for easy execution! 
