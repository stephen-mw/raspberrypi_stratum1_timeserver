# Stratum-1 Timeserver via Raspberry Pi
These configurations allow you to run a stratum-1 timeserver from your raspberry pi. The raspberry pi will sync its time with GPS satellites and make that time available over the network via the NTP protocol.

You can install it directly via a shell-pipe:
```
curl 'https://raw.githubusercontent.com/stephen-mw/raspberrypi_stratum1_timeserver/master/install' | sudo bash
```

# Requirements
You must have a GPS chip attached to your raspberry pi. The installer assumes the GPS PPS pin is connected to GPIO18. Change this value in the installer before running it.
