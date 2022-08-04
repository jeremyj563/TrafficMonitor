# TrafficMonitor Config INI
This is the `config.ini` configuration I use for the open source [TrafficMonitor program for Windows 11](https://github.com/zhongyang219/TrafficMonitor)
- [*Windows 10 branch here*](https://github.com/jeremyj563/TrafficMonitor/tree/win10)

![traffic-monitor-example](example.png "example")

## Links
- [r/Windows11: Showing NetBalancer network speed in taskbar?](https://www.reddit.com/r/Windows11/comments/p7v07m/showing_netbalancer_network_speed_in_taskbar/)
- [Chocolatey Package: Traffic Monitor](https://community.chocolatey.org/packages/traffic-monitor)

## Install TrafficMonitor ([using Chocolatey](https://chocolatey.org/install#individual))
```
> cinst -y traffic-monitor
```

## Config (using Chocolatey and Wget)
```
> cinst -y wget
> wget https://raw.githubusercontent.com/jeremyj563/TrafficMonitor/master/config.ini -O %appdata%\TrafficMonitor\config.ini
```

## Config (using Git)
Warning: Installing the config this way will delete any history data or any other local files created in the `TrafficMonitor` folder!
```
> rd /s/q %appdata%\TrafficMonitor
> git clone https://github.com/jeremyj563/TrafficMonitor %appdata%\TrafficMonitor
```
