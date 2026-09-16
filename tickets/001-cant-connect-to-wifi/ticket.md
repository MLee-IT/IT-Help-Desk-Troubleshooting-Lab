 # HD-001 - Can't Connect to Wi-fi

## Ticket Information

Category: Network / Connectivity
Priority: Medium
Status: Open
User: Jordan Smith
Department: Accounting
Device: Dell Latitiude 5420
Operating System: Windows 11

## Issue Description

User reports that their Dell Latitude 5420 cannot connect to the company's Wi-Fi network.

## Troubleshooting Steps

1. Confirmed Wi-Fi is enabled on the laptop.
2. Confirmed Airplane Mode is turned off.
3. Checked whether other devices can connect to the same Wi-Fi network.
4. Restarted the laptop.
5. Removed the saved Wi-Fi network and attempted to reconnect.
6. Verified the laptop's wireless adapter is enabled.
7. Ran Windows Network Troubleshooter.
8. Checked the IP configration using 'ipconfig'.
9. renewed the IP address using 'ipconfig /release' and 'ipconfig /renew'.
10. Tested network connectivity using 'ping'.

## Findings

The laptop was connected to the Wi-Fi network but was unable to obtain a valid IP address.

## Resolution

Released and renewed the laptop's IP address using 'ipconfig /release' and 'ipconfig /renew'. The laptop successfully obtained a valid IP address and reconnected to the Wi-Fi network.

## Verification

Confirmed the laptop received a valid IP address and was able to succesfully access the network. User confirmed that the Wi-Fi connection was working normally.

## Final Status

**Status:** Resolved

## Technician Notes

Issue was caused by the laptop not obtaining a valid IP address. Releasing and renewing the IP address restored network connectivity. No hardware failure was identified. 