# Path
Computer Configuration > Policies > Administrative Templates: Policy definitions (ADMX files) > Windows Components > Camerahide

![image](https://github.com/user-attachments/assets/531007e3-2f24-42bf-bd43-e3fbf9e434cd)

# Set
Allow Use of Camera     Set    Disabled 

![image](https://github.com/user-attachments/assets/c3eaf7d1-e9f1-41b4-b9a4-9e1893a47243)


# Recommendation for Exception Apply users

1) Create a user group on Active Directory the like GRP-EXC- ....
2) On group policy > Delegation Tab , Add this group
3) Check the permittion "Apply group policy" on column Deny.
