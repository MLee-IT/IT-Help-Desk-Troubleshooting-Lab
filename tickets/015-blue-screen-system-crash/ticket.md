# HD-015 - Blue screen / System Crash

## Ticket Information
Category: Hardware / Operating Systems
Priority: High
Status: Open
User: Jordan Miller
Department: Operations
Device: HP EliteBook 840
Operating System: Windows 11

## Issue Description
User reports that the computer unexpectedly restarted while working and displayed a Windows blue screen error. The user states that the system has experienced the error more than once.

## Troubleshooting Steps
1. Asked the user when the blue screen errors began and whether any recent hardware or software changes were made.
2. Asked the user to provide the error message or stop code displayed on the blue screen.
3. Restarted the computer and confirmed that Windows loaded normally.
4. Checked Windows Event Viewer for recent system errors.
5. Reviewed the Windows System event logs for errors occurring around the time of the crash.
6. Checked Device Manager for devices displaying warning indicators.
7. Confirmed that Windows was up to date.
8. Checked for available driver updates for the affected device.
9. Reviewed the computer's available disk space.
10. Ran Windows Memory Diagnostic to check for potential memory-related problems.
11. Restarted the computer and allowed the memory diagnostic test to complete.
12. Reviewed the diagnostic results after Windows started.

## Findings
The system experienced an unexpected blue screen error. Windows Event Viewer showed system errors occurring around the time of the crash. No hardware warning indicators were present in Device Manager, and the memory diagnostic did not identify any problems.

## Resolution
Installed the available device driver update and restarted the computer. The system started normally after the update.

## Verification
Confirmed that Windows loaded without displaying another blue screen error. The computer remained stable during testing, and the user was able to open the application and work normally.

## Final Status
**Status:** Resolved

## Technician Notes
The blue screen issue was associated with an outdated device driver. System logs were reviewed and hardware diagnostics were performed to help rule out other potential causes. Updating the affected driver and restarting the computer resolved the issue. System stablility was verified before closing the ticket.