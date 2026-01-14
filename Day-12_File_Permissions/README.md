## Day 12 – NTFS File Permissions & Access Control

This lab focuses on configuring NTFS permissions to control access to sensitive folders and validating that standard users are properly restricted.

### Tasks Completed
- Created a test folder to simulate shared data
- Reviewed default NTFS permissions
- Modified permissions to restrict standard user access
- Validated access control using a non-admin account
- Confirmed restricted users cannot view or access protected directories

### Tools Used
- Windows 11
- File Explorer
- NTFS Security Permissions

### Skills Demonstrated
- NTFS permission management
- Access control enforcement
- Principle of least privilege
- User access validation
- Administrative troubleshooting

### Evidence
Screenshots captured showing:
- NTFS permissions configured on the shared folder
- Standard user unable to view or access the restricted directory
- System preventing path resolution due to insufficient permissions

> Attempting to access a restricted folder path as a standard user resulted in Windows being unable to locate the directory, confirming that access restrictions were successfully enforced.
