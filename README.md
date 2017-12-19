# BlackList
Contains a list of known malicious network threats that are flagged by various entitites. For use with External Dynamic Lists.


### CiscoTalosIPBlacklist.txt
Talos’ Reputation Center provides access to expansive threat data and related information.

The IP Blacklist is automatically updated every 15 minutes and contains a list of known malicious network threats that are flagged on all Cisco Security Products. [Found Here](https://www.talosintelligence.com/documents/ip-blacklist)

### IPsum Threat Intelligence Feed
See https://github.com/stamparm/ipsum for full list of over 200,000 IPs

This list contains only those of a score of 2 and higher, great for those with limited external dynamic IP capactities.

IPsum is a threat intelligence feed based on 30+ different publicly available lists of suspicious and/or malicious IP addresses. All [lists](https://github.com/stamparm/maltrail) are automatically retrieved and parsed on a daily (24h) basis and the final result is pushed to this repository. List is made of IP addresses together with a total number of (black)list occurrence (for each). Greater the number, lesser the chance of false positive detection and/or dropping in (inbound) monitored traffic. Also, list is sorted from most (problematic) to least occurent IP addresses.
