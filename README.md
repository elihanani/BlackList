# BlackList
Contains a list of known malicious network threats that are flagged by various entitites. For use with External Dynamic Lists.


### CiscoTalosIPBlacklist.txt
Talos’ Reputation Center provides access to expansive threat data and related information.

The IP Blacklist is automatically updated every 15 minutes and contains a list of known malicious network threats that are flagged on all Cisco Security Products. [Found Here](https://talos-intelligence-site.s3.amazonaws.com/production/document_files/files/000/017/921/original/ip_filter.blf?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAIXACIED2SPMSC7GA%2F20171114%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20171114T192359Z&X-Amz-Expires=3600&X-Amz-SignedHeaders=host&X-Amz-Signature=7656f6e48229fe56395ff47f1bca071985ee55d9b21e506b8a870d071b19add5)

### IPsum Threat Intelligence Feed
See https://github.com/stamparm/ipsum for full list of over 200,000 IPs

This list contains only those of a score of 2 and higher, greate for those with limited external dynamic IP capactities.

IPsum is a threat intelligence feed based on 30+ different publicly available lists of suspicious and/or malicious IP addresses. All [lists](https://github.com/stamparm/maltrail) are automatically retrieved and parsed on a daily (24h) basis and the final result is pushed to this repository. List is made of IP addresses together with a total number of (black)list occurrence (for each). Greater the number, lesser the chance of false positive detection and/or dropping in (inbound) monitored traffic. Also, list is sorted from most (problematic) to least occurent IP addresses.
