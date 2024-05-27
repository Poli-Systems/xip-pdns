#### xip-pdns

This is the source of the [PowerDNS](http://powerdns.com/) pipe backend adapter powering [polisystems.cloud](http://polisystems.cloud/).

Install this on your system, adjust [etc/xip-pdns.conf](etc/xip-pdns.conf.example) to your liking, and configure PowerDNS as follows:

    launch=pipe
    pipe-command=/path/to/xip-pdns/bin/xip-pdns

#### Backend for polisystems.cloud

We resolve the URL's to the ip's using a PowerDNS backend `1.2.3.4.polisystems.cloud -> 1.2.3.4`
See [polisystems.cloud](http://polisystems.cloud/).
