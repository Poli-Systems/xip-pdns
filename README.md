#### xip-pdns

This is the source of the [PowerDNS](http://powerdns.com/) pipe backend adapter powering [xip.io](http://xip.io/).

Install this on your system, adjust [etc/xip-pdns.conf](etc/xip-pdns.conf.example) to your liking, and configure PowerDNS as follows:

    launch=pipe
    pipe-command=/path/to/xip-pdns/bin/xip-pdns

#### Backend for polisystems.cloud

We resolve the URL's to the ip's using a PowerDNS backend `1.2.3.4.polisystems.cloud -> 1.2.3.4` `anything.1.2.3.4.polisystems.cloud -> 1.2.3.4`
