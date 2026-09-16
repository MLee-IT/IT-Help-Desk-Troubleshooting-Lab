# HD-004 - Computer Has No internet Access

## Ticket Information

Category: Network / Connectivity
Priority: High
Status: Open
User: Alex Carter
Department: Marketing
Device: HP Elitenook 840
Operating System: Windows 11

## Issue Description

User reports that the computer is connected to the company network but cannot access the internet. Web pages fail to load, and the user is unable to access online company resources.

## Troubleshooting Steps

1. Asked the user when the connectivity issue began and whether other users were experiencing the same problem.
2. Confirmed thr computer was connected to the company's network.
3. Confirmed Airplane mode was turned off and the network adapter was enabled.
4. Checked whether the computer could access multiple websites.
5. Opened Command Prompt and ran 'ipconfig' to revew the computer's IP onfiguration.
6. Confirmed the computer had an IP address and default gateway.
7. Used 'ping' to test connectivity to the default gateway.
8. Used 'ping 8.8.8.8' to test connectivity to an external IP address.
9. Used 'ping google.com' to determine whether DNS name resolution was working.
10. Compared the results of the gateway, external IP, and domain-name tests.
11. Flushed the DNS resolver cache using 'ipconfig /flushdns'.
12. Renewed the computer's IP configuration using 'ipconfig /release' and 'ipconfig /renew'.
13. Retested network connectivity after renewing the IP configuration.
14. Confirmed that websites and online company resources were accessible.

## Findings

The computer has a valid IP address and was able to communicate with the default gateway and an external IP address. However, the computer was unable to properly resolve domain names. This indicated a DNS resolution issue rather than a complete loss of network connectivity.

## Resolution

Flushed the computer's DNS resolver cache using 'ipconfig /flushdn'. The computer's IP configuration was the renewed using 'ipconfig /release' and 'ipconfig /renew'. After the network configuration was refreshed, DNS name resolution began working normally and the user was able to access websites and online company resources.

## Verification

Confirmed that the computer could successfully access multiple websites and online company resources. DNS name resolution was functioning normally, and the user confirmed that internet access had been restored.

## Final Status

**Status:** Resolved

## Techinician Notes

The issue was caused by a DNS resolution problem. Network connectivity to the local gateway and external IP addresses was available, but the domain names were not resolving correctly. Flushing the DNS cache and renewing the IP configuration restored normal DNS resolution and internet access. Connectivity was verified before closing the ticket.