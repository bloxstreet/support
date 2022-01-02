---
layout: default
title: Admin Guide
parent: Guides
nav_order: 3
---

# TSA Admin Guide
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

TSA is BloxStreet's administrative system and anti-exploit, custom developed by axcracy and TheCakeChicken. TSA takes the form of a Discord bot, Roblox module, and administrative web panel. Those with TSA permissions can utilize these to perform their duties.

### Commands
{: .text-red-300 }
#### 1A - Permission Levels
{: .text-grey-dk-000 }
{: .no_toc }
All members who are ranked Floor Supervisor+ will gain access to various commands. Ranks and their respective admin levels are shown below. 

| Rank        | Admin Level         | 
|:-------------|:------------------|
| Floor Supervisor           | Moderator | 
| Assistant Manager | Moderator   | 
| Store Manager           | Moderator     | 
| Assistant Director          | Admin | 
| Store Director           | Admin | 
| Executive Assistant           | Admin | 
| Store Executive         | Admin | 
| Junior Moderator           | Super Admin | 
| Senior Moderator          | Super Admin | 
| Head Moderator           | Super Admin | 
| Store Developer          | Creator | 
| Group Owner           | Creator | 

Depending on the role, you will only be able to perform certain commands. For example, users with Moderator commands **cannot** run ;pban, but users with Super Admin commands can. 

#### 1B - Executing Commands
{: .text-grey-dk-000 }
{: .no_toc }
When executing commands, you must take care to ensure you are doing it correctly. 

* TSA allows you to run a command by typing "/e" in front of a command. 
  * To run a command privately with the "/e" method, you need to first open up the chat to run a command like you usually would. Before running the command, however, you need to type "/e."
    * EX:  **_/e :m Hello!_**
  * This will make the command private, and this hidden from the chat. 
* You may also use the console to carry out a command. 
  * To use the console, you need to first press ";" or "'" on your keyboard. This will cause a GUI to appear at the top of your screen. When using the console, the prefix is **not** required. 
    * EX: ; (Console Opens) 
      
      **_exploit logs_**

      ( Exploit logs GUI is then shown as expected) 
      
### Anti-Exploit
{: .text-red-300 }
As mentioned at the start of this document, TSA features a built-in Anti-Exploit system, which keeps out exploiters, and automatically bans/kicks depending on the severity. 

* All detected exploits can be viewed with the :exploitlogs command. **Please do not stay under the impression that :exploitlogs will show exploiters who are currently in the server, and show what they are doing. The system cannot detect everything and only logs when an exploiter is automatically banned.** 
* If you are hosting a shift, and you notice that an exploiter gets banned, **please do not call for an SHR unless they can rejoin. It may take up to 30 seconds for them to be kicked again, as the HTTP API needs to be re-synced!** 

### Downtime
{: .text-red-300 }
Downtime is a time in which a critical error has occurred within the code, stopping all commands being run, and by extension, your admin being given.

Click [here](https://status.bloxstreet.store) to view the status of various TSA services.

* In this scenario, the Head Moderators+ kindly request that **you do not spam ping us, DM us repeatedly, or anything of the sort when this occurs.** Doing so is **_punishable,_** and could get you possibly demoted. Axcracy and TheCakeChicken are aware of the problems and are likely fixing them as you worry. 
* A simple fix may be just be rejoining. If a server shuts down, many people rejoining exactly at the same time can overload the system and may cause your admin loading to be delayed, or just completely aborted. For this reason, we request that you **wait a few minutes** before rejoining, or **just simply rejoin.**

### Acceptable Usage
{: .text-red-300 }
This is the main section of the document. It will outline everything that you can and not do with your commands. 

All major admin abuse (running ;pban all etc.) is **logged** and will result in an instant punishment! The command will be immediately canceled, and developers are notified. 

#### 4A - All commands Usage
{: .text-grey-dk-000 }
{: .no_toc }

**Arguments** = What you need to supply to run the command. 

**Allowed** = What you may use this command for. 

**Not Allowed** = What you may not use this command for. 

**Punishment** = What happens if you use it inappropriately. 

**Logs All Attempts:** Whether or not doing all as a player logs.

Commands in _italic_ do not have any consequences/information to say about them. You may use them! Commands with a ~~strikethrough~~ must not be used AT ALL! Using them could lead to severe consequences.

| Command Name        | Arguments  | Allowed | Not Allowed | Punishment | Logs All Attempts |
|:-------------|:------------------|:------|:-------------|:------------|:------------------|
| :respawn / :res / :refresh / :ref          | A player | You can respawn yourself and anybody who may request it.  |  You may NOT do :respawn all, or respawn users who **do not** request a resapawn.           |  Ranges from a warning to permanent ban, depending on the severity.          |  No.                 |
| :kick (Assistant Director+).           | A player, a reason. | Anyone with 3 or more warnings or for a valid reason.  |  Anyone with 3 or less warnings and for an invalid reason.  | Ranges from a blacklist to a permanent ban, depending on the severity.            |    Yes.               |
| :ban (Assistant Director+).           | A player, a reason. | Anyone with a valid reason (read the Punishment Guide). | Anyone with an invalid reason.             |  Ranges from a warning to a permanent ban, depending on the severity.       |     Yes.              |
| :unban (Assistant Director+).           | A player, a reason. | Anyone with a valid reason (read the Punishment Guide). | Anyone with an invalid reason.             |  Ranges from a warning to a permanent ban, depending on the severity.       |     No.   |
| :pban (Junior Moderator+).           | A player, a reason. | Anyone with a valid reason (read the Punishment Guide).  |  Anyone with an invalid reason.            |  Ranges from a warning to a permanent ban, depending on the severity.           |   Yes.                |
| :sm / :m (Junior Moderator+ in-store ONLY).           | A message. | Announcements that everyone needs to see.  | Messages that are unimportant / do not need to be seen by anyone. | Ranges from a warning to a permanent ban, depending on the severity.          |  No.                 |
| :mod / :admin / :superadmin (DEV+).           | N/A.  | N/A.  |    N/A.          | N/A.            |    N/A.               |
| :unadmin (Head Moderator+ ONLY.)           | A player. | Only users who are Head Moderator+ may use this command. This can be used for users who are undergoing admin abuse, but do not warrant for a ban.  |   Using this if you are not a Head Moderator+.           |     Permanent ban.        |        Yes.           |
| :s (DEV+ ONLY).           | N/A. | N/A.  |   N/A.           |     N/A.        |                   |
| :shutdown (Head Moderator+ ONLY & Host/Co-Host in trainings).           | Only users who are Head Moderator+ may use this in-store. Use if there is a serious scripting bug & with authorization from Developers/Group Owner. | N/A.  |   Using it if you are not a Head Moderator+ in-store.         |     N/A.       |    N/A.               |
| :slock / unslock (Not to be used at the store. May be used at trainings.        | N.A. | N/A.  |   N/A.           |     N/A.        |       N/A            |
| :time (DEV+ ONLY).           | N/A. | N/A.  |   N/A.           |     N/A.        |       N/A.            |
| :tp / :bring (Assistant Director+). | Player(s) | Only if a player is stuck somewhere and needs to be freed. | Any other invalid reason. | Warning. If continued, may lead to a demotion. | Yes. 
| :to | Player. | Needing to be teleported to a certain situation, and any other valid reason. | Unnecessary reasons. | Demotion. | Yes. | 
| :btools (DEV+ ONLY). | Player. | N/A. | N/A. | Instant termination if used by a user who is not a Developer. | Yes. | 
| :view / :unview | Player. | To watch suspicious players (Ex: exploiters). | Stalking SHRs (Junior Moderator+). | Warning. | Yes. |
| :ff / :unff | Player. | To be used for Low Ranks at training. | Any other reason. | Warning. | Yes. | 
| :jump (Junior Moderator+). | Player. | If a player is stuck in a seat and can not get out. | Any other reason. | Warning. | Yes. | 
| :fly (Junior Moderator+). | Player. | If a Junior Moderator needs to supervise. | Any other player using the command. | Warning. | Yes. | 



| Command Names That Can Be Used (No information needed)       |
|:-------------|
| _:cmds_ |
| _:bans / pbans_           |
| _:info_         |
| _:pm (Junior Moderator+)._           |
| _:admins_           |
| _:chatlogs_           |
| _:logs_           |
| _:joinlogs_           | 
| _:exploitlogs_           | 
| _:shutdownlogs_           |
| _:viewtools_ | 


| Command Names that CAN NOT Be Used (No information needed)       |
|:-------------|
| ~~:crash~~           |
| ~~:h (SHOULD NOT BE USED BY ANYONE AT THE STORE, NON-HOSTS AND CO-HOSTS AT TRAINING)~~           | 
| ~~:change~~  |
| ~~:ws / :speed~~ |
| ~~:jumppower~~ | 
| ~~:god / :ungod / :heal~~ | 
| ~~:sit~~ | 
| ~~:team~~ | 
| ~~:insert~~ |
| ~~:clear / :clr~~ | 
| ~~:tools~~ | 
| ~~:removetools~~ | 
| ~~:startergear / :clearstartergear~~ |

### Conclusion
{: .text-red-300 }
You reached the end of the Admin Guide! Please ensure that you read **all** the information thoroughly before you use your commands. If you have any questions, please refer back to this guide or contact a Junior Moderator+.
