# HD-013 - File and Folder Permissions

## Ticket Information
Category: Access / Permissins
Priority: Medium
Status: Open
User: Cameron Daniels
Department: Finance
Device: Lenovo ThinkPad T14
Operating System: Windows 11

## Issue Description
User reports that they are unable to open a folder on a shared company drive. The user can access the shared drive itself but receives an access denied message when attempting to open a specific folder.

## Troubleshooting Steps
1. Asked the user when the access issue began and whether they had previously been able to access the folder.
2. Confirmed that the user was connected to the company network.
3. Confirmed that the ser could access the shared drive.
4. Attempted to open the affected folder using the user's account.
5. Documented the access denied message displayed by Windows.
6. Comfirmed that other authorized users could access the affected folder. 
7. Confirmed that the user's company account was active.
8. Checked the user's assigned access permissions for the affected folder.
9. Compared the user's permissions with the required permissions for the folder.
10. Confirmed that the user was missing the required folder access permission.

## Findings
The user could access the shared drive but did not have the required permissions for the specific folder. Other authorized users were able to access the folder normally.

## Resolution
Submitted the appropriate access requesr and had the user's account added to the approved security group responsible for access to the folder. The user then signed out and signed back in to refresh their access permissions.

## Verification
Confirmed that the user could open the affected folder after signing back in. The user was able to browse the folder and access the files they were authorized to use.

## Final Status
**Status:** Resolved

## Technical Notes
The shared drive was functioning normally, but the user's account did not have therequired permissions for the affected folder. Access was restored through the organization's approved permission-management process. The userr's access was verified after signing back in.