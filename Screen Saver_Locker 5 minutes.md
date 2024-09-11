# Screen Saver Locker 5 minutes

# Path on Computer Setting
Computer Configuration > Policies > Administrative Templates: Policy definitions (ADMX files) 
> System > Power Management > Video and Display Settings

![image](https://github.com/user-attachments/assets/78cfb38e-acd1-4ece-9b9a-f5042509f35d)

# Setting policies

1) Turn off the display (on battery):
Turn off the display (on battery) Enabled  
Turn Off the Display (seconds): 300 
 
2) Turn off the display (plugged in):
Turn off the display (plugged in) Enabled  
Turn Off the Display (seconds): 300

# User Configuration > Policies > Administrative Templates: Policy definitions (ADMX files) >
Control Panel > Personalization 

![image](https://github.com/user-attachments/assets/a674c4e4-5dec-43bb-92ba-1fb65c457fce)

1) Enable screen saver Enabled  

2) Password protect the screen saver Enabled  

3) Screen saver timeout Enabled  

4) Number of seconds to wait to enable the screen saver 
Seconds: 300 


# Recommendation for Exception Apply users

1) Create a user group on Active Directory the like GRP-EXC- ....
2) On group policy > Delegation Tab , Add this group
3) Check the permittion "Apply group policy" on column Deny.
