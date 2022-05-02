# Privacy

Soundbort only collects a minimum amount of data it needs to be able to work. Mostly only IDs and no other metadata like names, avatars, etc. When those users, servers, roles, channels, messages, etc. are deleted from Discord, the IDs are of no more use.

### **What discord data do you store?**

User IDs, Server IDs, Role IDs, Channel IDs, Message IDs, Interaction IDs, Attachment files

### **For what purpose(s) do you store the information you collect?**

Setting an admin role for admin commands: **Role IDs** and **Server IDs** (only IDs, no names, creation dates, etc.)

To keep track of the replies to interactions and later send follow-up messages: **Interaction IDs**, **Server IDs**, **Channel IDs**, **Message IDs** (only IDs, no names, etc.)

Custom user-uploaded sound files for the soundboards: **User IDs**, **Server IDs** (only IDs, no names, creation dates, etc.), **Attachment file** (only the file, no filename, etc.). **Media attachments are stripped of all metadata.**

To log what commands have been triggered and buttons have been clicked: **Interaction IDs**, **Server IDs**, **Channel IDs**, **Channel Type** (dm, text, thread, etc.), **User IDs** (only IDs, no names, etc.)

### **For how long do you store it?**

Admin role IDs and the associated server IDs are kept for 14 days after Soundbort is removed from the server.

Sound files are kept until a user deletes them, given they were added to the soundboard successfully. Otherwise they are instantly deleted. Sound files and earned slots from the server soundboard are kept for 14 days after Soundbort is removed from the server.

Logs of commands, button presses and other interactions are kept for 30 days.

## How can I request deletion of my data?

You can text `Loneless#0983` on Discord or `lonelessart@gmail.com` with your Discord tag (but I will need to still text you on Discord to ensure it's your account) and ask for a deletion of your data or your server's data. I will go through and check if you're a server admin and delete all associated data, that will include:

* Your or your server's soundboard and all samples
* Your or your server's additional sample slots you gained by upvoting the bot or other means
* In case of server: any bot configurations like the admin role

There will be an automated way in the future.
