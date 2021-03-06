# [Bump Buddy](https://discord.bots.gg/bots/765598792535244820) - Not updated yet
### A bot that helps your server grow, by reminding you to bump your server on Disboard!

Join the [support server](https://discord.gg/RFMkhhx) if you need help with anything!

We all want members, don't we? So it is obviously a bonus to add your server to a site like Disboard, but when you do that, you forget to bump your server all the time, loosing a couple of members every time. Invite Bump Buddy! Be reminded to bump, and gain members! Disboard.org's bot is required in order to get notified when the server can be bumped!

## New!
- Bump Buddy **should** now be able to work on all servers even though the disboard bot language is different. Not all languages has been tested! Join the support server if it doesn't work.
- Now support @here and @everyone as bump reminder roles!
- Custom reminder embed message!

## Commands:
#### Setup
**Bump Channel** The channel BB will send reminders in: "bb setchannel #CHANNEL"  
**Bump Role** A role that BB will ping when the bump is ready, if you want to set the bump role as @here or @everyone you type it in without the @: "bb setrole @ROLE" and for fx. @everyone it's "bb setrole everyone"  
**Custom Reminder Message** Create your own text in the reminder message by using this command: "bb setmsg This is the embed Title | THis is the embed Description" Using | as a splitter between title and description. If you leave it out, only the description will be changed.

#### Other
**Channel** See the current bump channel: "bb channel"  
**Test** Tests the current settings on the server, fx bump channel and role: "bb test"  
**Role** See the current bump role: "bb role"  
**Reset** Removes all data about your server (The bot will still funktion): "bb reset"  
**Help** Shows all the commands: "bb help"  
**Privacy** Shows the privacy policy, required by discord: "bb privacy"  
**Stats** Shows Bump Buddy's stats: "bb stats"  
**Reviews** Sends a link to the server reviews: "bb reviews"  
**Page** Sends a link to the servers Disboard page: "bb page"  

#### Why choose Bump Buddy?
- Everything is free, no need to pay to get a special feature!  
- Easy to set up!  
- Customizable reminder message!  
- Supports all Disboard bot languages!  
- Doesn't break Disboards ToS and Guidelines!

#### It doesn't get any easier!  

---

## Setting it up

### bb setrole \<Role>  
You can see 3 different ways to set the bump reminder role, this is the role that will be mentioned when 2 hours has passed and the server can be bumped.

![image](images/setrole.PNG)  
Ignore the bold text.

But what if you want to set @here or @everyone as the bump role? You simple type **bb setrole here** or **bb setrole everyone** without mentioning anyone, look at the image below.  

![image](images/setrole1.PNG)  

To confirm that the change has taken place, you can type **bb role** and a message from bump buddy should appear, saying what bump role you currently have set up.  
![image](images/setrole_confirmed.PNG)  

---

### bb setchannel \<Channel>  
The reminder channel will be the channel where bump reminders are sent. If you don't have it set up, it will be the channel where the bump was performed. Also the bump channel makes it possible to get messages/announcements from the support server, fx. new updates, bugs etc. The channel can only be set by mentioning the channel, as on the image below.  

![image](images/setchannel.PNG)  

To confirm that the change has taken place, you can type **bb channel** and a message from bump buddy should appear, saying what bump channel you currently have set up.  
![image](images/setchannel_confirmed.PNG)  

---

### bb setmsg \<Some Custom Message>  
This command is used to change the embedded message that is sent when you server can be bumped. By default it looks like this:  
![image](images/setmsg_default.PNG)  

How do you change this message? You simple use the commands **bb setmsg**. Lets say you want the title of the embed to be "Timer is up" and the description to be "This server can be bumped now!", then you would type: **bb setmsg Timer is up | This server can be bumped now!**, see the image below:  
![image](images/setmsg.PNG)  
