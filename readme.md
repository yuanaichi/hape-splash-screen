![hape](https://github.com/yuanaichi/hape-splash-screen/blob/main/hape-splash-screen.png?raw=true "hape splash screen")


## install

```
sudo apt install toilet

sudo apt install  neofetch

git clone https://github.com/yuanaichi/hape-splash-screen.git 

cd hape-splash-screen

chmod +x ./hape.sh
```

### Modify the weather location

In haple.sh, line 19,  Replace Beijing with your city name, GPS, etc. See: curl wttr.in/:help

curl wttr.in/Beijing?0 --silent --max-time 3 > /tmp/now-weather


### Add the below two lines to the end of.bashrc

```
alias hape='/your-path/hape-splash-screen/hape.sh'
hape
```

### Reload bashrc

```
source ~/.bashrc
```

The Hape Splash Screen is automatically displayed when you open Terminal again
