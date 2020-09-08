# email-spammer
Demo = https://www.youtube.com/watch?v=5BhjfQxAmps
Go on https://discord.com/developers/applications
Make an application - make a bot - put the bot token in the setup.ini file.
On the left - where you clicked bot - above will be something that reads OAuth2 - Click it and click "bot" on the top / 1st checkbox and then click "Administrator" on the bottom / 2nd  checkbox. Copy the link and open it. Now invite the bot to the server you want it in. It'll be offline.


Now in the file called setup.ini - make a gmail and put the username and password - as this is in python on github you can see the source code and be assured it's only for the program to email with - no one else can access this. The email will need less secure apps - 

https://myaccount.google.com/lesssecureapps
This allows my program to interact with the email. Now - if everything is done correctly , upon opening the python file, the bot should go online. Type
!spam and it'll show the format. Here's a usage demo:
!spam 20 email@email.com Hello
To email@email.com - you'll send 20 messages saying "hello" - you can check the progress as the embed will display the message count sent live, and if your the hoster of the program you can see everything like the times the emails are sent - the content , the amount and the command executor. Have fun and consider showing my github some love!
