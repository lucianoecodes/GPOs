# Block All Removable Access by Users

# Path
User Configuration > Policies > Administrative Templates: Policy definitions (ADMX files) > System > Removable Storage Access

![image](https://github.com/user-attachments/assets/0455d7b2-c7ef-44dd-bc57-ddc372d69794)

# Recommended sets:

CD and DVD: Deny read access				Set		Enabled  
CD and DVD: Deny write access				Set		Enabled  
Floppy Drives: Deny read access			Set		Enabled  
Floppy Drives: Deny write access		Set		Enabled  
Removable Disks: Deny read access		Set		Enabled  
Removable Disks: Deny write access	Set		Enabled  
Tape Drives: Deny read access				Set		Enabled  
Tape Drives: Deny write access			Set		Enabled  
WPD Devices: Deny read access				Set		Enabled  
WPD Devices: Deny write access			Set		Enabled  


# Recommendation for Exception Apply users

1) Create a user group on Active Directory the like GRP-EXC- ....
2) On group policy > Delegation Tab , Add this group
3) Check the permittion "Apply group policy" on column Deny.
