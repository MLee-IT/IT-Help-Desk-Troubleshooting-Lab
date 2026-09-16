# HD-003 - Printer Not Printing

Category: Hardware / Printing
Priority: Medium
Status: Open
User: Morgan Davis
Department: Finance
Device: Dell Latitude 5430
Operating System: Windows 11

## Issue Description

User reports that they are unable to print documents to the department printer. The user states that the printer appears to be available, but the document remain in the print queue and do not print.

## troubleshooting Steps

1. Asked the user whether the issue affected all documents or only a specific document.
2. Confirmed the printer was powered on and displayed no error messages.
3. Checked thr printer for paper, toner, and any visible paper jams.
4. Confirmed the computer was connected to the company network.
5. Confirmed the correct department printer was selected as the default printer.
6. Checked the Windows print queue for stuck or failed print jobs.
7. Attempted to cancel the stuck print job from the print queue.
8. Restarted the Print Spooler service.
9. Confirmed the printer was still available after restarting the Print Spooler service.
10. Sent a test document to the printer.
11. Confirmed the test document printed successfully.

## Findings

The Windows print queue contained a stuc print job that was preventing new documents from being processed. The printer itself was powered on, connected to the network, and did not display any hardware errors.

## Resolution

Cleared the stuck print job from the Windows print queue and restarted the Print Spooler service. After the service restarted, the printer became responsive and successfully processed a test document.

## Verification

Confirmed that the test document printed successfully without errors. The print queue remained clear after testing, and the user confirmed that they were able to print documents normally.

## Final Status

**Status:** Resolved

## Technician Notes

The issue was caysed by a stuck print job in the Windows print queue. The printer was powered on and connected to the network, with no hardware errors identified. Clearing the print queue and restarting the Print Spooler service restored normal printing. The printer was tested successfully before closing the ticket.