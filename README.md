# TrafficMonitor Config INI
This is the `config.ini` configuration I use for the open source [TrafficMonitor program for Windows](https://github.com/zhongyang219/TrafficMonitor).

## Installation (using Chocolatey and Wget)
```
> cinst -y wget
> wget https://raw.githubusercontent.com/jeremyj563/TrafficMonitor/master/config.ini %appdata%\TrafficMonitor
```

## Installation (using Git)
Note: warning, installing the config this way will delete any history data or any other local files created in the `TrafficMonitor` folder!
```
> rd /s/q 
> git clone https://github.com/jeremyj563/TrafficMonitor %appdata%\TrafficMonitor
```