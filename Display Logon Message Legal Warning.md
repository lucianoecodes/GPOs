# Path
Computer Configuration > Policies > Windows Settings > Security Settings > Local Policies > Security Options 

![image](https://github.com/user-attachments/assets/22778a20-ce02-4941-bf5e-2fea798aeebd)

# Set

1)  Setting Title
Interactive logon: Message title for users attempting to log on
Here could be set => "LEGAL WARNING"

2) Setting Text
Interactive logon: Message text for users attempting to log on 
Here could be set => "This computer is not for personal use!"


# Recommendation for Exception Apply users

1) Create a user group on Active Directory the like GRP-EXC- ....
2) On group policy > Delegation Tab , Add this group
3) Check the permittion "Apply group policy" on column Deny.
