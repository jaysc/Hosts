# Personal hosts files for Samsung Knox-based ad blockers.

## Host aggregator script
 * This script aggregates the following hosts files , processes them into a Samsung Knox friendly format, and removes any duplicate and redundant hosts.
   - AdHell original package
   - Dan Pollock
   - Peter Lowe
   - Bjorn Stormberg
   - mmotti manual additions
   - StevenBlack Unified hosts
   - AdGuard Simplified domain names filter

## Main lists

* Link: https://raw.githubusercontent.com/CitizenXVIL/Hosts/master/Expanded_hosts_list.txt
   - Ran original mmotti script with default domains plus adguard's simplified host list
   - Short link: https://bit.ly/2KhySZ3
   
* Link: https://raw.githubusercontent.com/CitizenXVIL/Hosts/master/Optimized_hosts_list.txt
   - Ran modified script to reduce the size of the list by eliminating redundant domains from Expanded_hosts_list. Additional wildcards and regex removals were also added.
   - Short link: https://bit.ly/2s5KMxC

## Add-on Lists
* Link: https://raw.githubusercontent.com/CitizenXVIL/Hosts/master/Youtube%20hosts.txt
   - Experimental list to attempt to block YouTube video ads. This is based on information from Pi-Hole discussion boards about YouTube ad blocking. This is highly unlikely to work because YouTube uses continuously changing subdomains, and blocking all the subdomains can affect mobile playbcack.
   - Short link: https://bit.ly/2KvfXKS

* Link: https://raw.githubusercontent.com/CitizenXVIL/Hosts/master/mobile%20domains.txt
   - Mobile ad/tracker list based on AdGuard's mobile domain list.
   - This was list is automatically processed by a script.
   - Short link: https://bit.ly/2w2ac4j

## Credit

Original Powershell script is by mmotti on Github.
