# pkt_stats

Install this script on your pkt miners, have a influxdb server with grafana ready for nice visualizations

First change settings in pkt_stats.conf

Then run the pkts_installer.sh with following parameters: (don't use the installer - it's broken)

- s: installs the pkt_stats script
- m: installs packetcrypt_rs miner
- w: installs the pkt cli wallet
- b: installs a service that gets the balance out of your wallet and puts it into influxdb
- c: installs a service that monitors your pkt-services 
- f: installs a script to easily fold your coins

![pkt_stats](https://user-images.githubusercontent.com/11134705/152444501-d0a2280e-8f9f-48c7-9617-841ebb62ef2f.jpg)

Note: You'll need to build your own Grafana Dashboard

If you'd like to buy me a coffe: ```pkt1qk7ee80trnvpz8ekzu2mech3g0skw9p2k9w4t0s```
