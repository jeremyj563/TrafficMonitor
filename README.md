# TrafficMonitor Config INI
This is the `config.ini` configuration I use for the open source [TrafficMonitor program for Windows](https://github.com/zhongyang219/TrafficMonitor).

![traffic-monitor-example](example.png "example")

## Install TrafficMonitor ([using Chocolatey](https://community.chocolatey.org/packages/traffic-monitor))
```
> cinst -y traffic-monitor
```

## Config (using Chocolatey and Wget)
```
> cinst -y wget
> wget https://raw.githubusercontent.com/jeremyj563/TrafficMonitor/master/config.ini -O %appdata%\TrafficMonitor\config.ini
```

## Config (using Git)
Note: Warning, installing the config this way will delete any history data or any other local files created in the `TrafficMonitor` folder!
```
> rd /s/q 
> git clone https://github.com/jeremyj563/TrafficMonitor %appdata%\TrafficMonitor
```