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
All members who are ranked Store Supervisor+ will gain access to various commands. Ranks and their respective admin levels are shown below. 

| Rank        | Admin Level         | 
|:-------------|:------------------|
| Store Supervisor           | Moderator | 
| Assistant Manager | Moderator   | 
| Store Manager           | Moderator     | 
| Store Director          | Admin | 
| Board of Directors          | Admin | 
| Executive Assistant           | Admin | 
| Store Executive         | Admin | 
| Junior Moderator           | Super Admin | 
| Senior Moderator          | Super Admin | 
| Head Moderator           | Super Admin | 
| Store Developer          | Creator | 
| Group Owner           | Creator | 

Depending on the role, you will only be able to perform certain commands. For example, users with Moderator commands **cannot** run :pban. However, players with Super Admin may.

#### 1B - Executing Commands
{: .text-grey-dk-000 }
{: .no_toc }
When executing commands, you must take care to ensure you are doing it correctly. 

* TSA allows you to run a command by typing "/e" in front of it.
  * To run a command privately with the "/e" method, you need to first open up the chat to run a command like you usually would. Before running the command, however, you need to type "/e."
    * EX:  **_/e :m Hello!_**
  * This will make the command private. This also makes the command hidden from the chat.
* You may also use the console to carry out a command. 
  * To use the console, you need to first press ";" or "'" on your keyboard. This will result in a GUI to appear at the top of your screen. When using the console, the prefix is **not** required. 
    * EX: ; (Console Opens) 
      
      **_exploitlogs_**

      (Exploit logs GUI is then shown as expected) 
      
### Anti-Exploit
{: .text-red-300 }
As mentioned at the start of this document, TSA features a built-in anti-exploit system, which keeps out exploiters. The anti-exploit system automatically permanently bans or kicks depending on the severity. 

* All detected exploits can be viewed with the :exploitlogs command. **Please do not stay under the impression that :exploitlogs will show exploiters who are currently in the server and show what they are doing. The system cannot detect everything and only logs when an exploiter is automatically banned.** 
* If you are hosting a shift, and you notice that an exploiter gets banned, **please do not call for an SHR unless they can rejoin. It may take up to 30 seconds for them to be kicked again, as the HTTP API needs to be re-synced.** 

### Downtime
{: .text-red-300 }
Downtime is a time in which a critical error has occurred within the code, stopping all commands being run, and by extension, your admin being given.

Click [here](https://status.bloxstreet.store) to view the status of various TSA services.

* In this scenario, the Head Moderators+ kindly request that **you do not spam ping us, DM us repeatedly, or anything of the sort when this occurs.** Doing so is **_punishable_** and could get you possibly demoted. Group Developers have likely been informed of the problems and are fixing them as you worry. 
* A simple fix may just be rejoining. If a server shuts down, many people rejoining exactly at the same time can overload the system and may cause your admin loading to be delayed. For this reason, we request that you **wait a few minutes** before rejoining, or **just simply rejoin.**

### Acceptable Usage
{: .text-red-300 }
This is the main section of the document. It will outline everything you can and cannot do with your admin commands.

All major admin abuse (running :pban all, etc.) is **logged** and will result in an instant punishment! The command will be immediately canceled, and SHRs are notified. 

#### 4A - All Commands Usage
{: .text-grey-dk-000 }
{: .no_toc }

When executing commands, be sure to type at least 50% of the player's username.


| Command Name | Description |
|:-------------|:------------|
| :respawn / :res / :refresh / :ref | Use this command to respawn yourself and anybody who may request it. You may NOT do :respawn all or respawn users who do not request a respawn. |
| :kick (Store Director+) | Use this command to update in-game ranks, kick failed or passed LRs at a training session, or for any other valid reason. |
| :ban (Store Director+) | Use this command for trollers, rule violators, removing a blacklisted or permanently banned user, or for  other valid reason. |
| :unban (Store Director+) | Use this command if an HR accidentally bans the wrong person or if an invalid ban reason was put. | 
| :pban (Junior Moderator+) | Use this command to permanently ban players (valid reasons are on the Punishment Guide). | 
| :sm / :m  / :fm (Junior Moderator+) | Use this command to make announcements in the store or at training sessions. | 
| :shutdown (Junior Moderator+ & the host of a training) | Use this command to conclude a training session after everyone is finished. SHRs may use this command if several players are banned from a server as a result of an admin abuse attack, for development updates, or if a server is lagging and nonfunctional. This command is not allowed for shutting down during a training session or shutting down for no reason. |
| :slock / unslock (Host of a training session) | Use this command to lock a training session at :00. This command is not allowed for unlocking a server during a training session. |
| :tp / :bring (Store Director+) | Use this command if a player is stuck somewhere and needs to be freed. |
| :to | Use this command to be teleported to a certain situation, as well as for other valid reasons. |
| :view / :unview | Use this command to watch suspicious players (example: exploiters). Do not use this command to stalk SHRs or view shift hosts. | 
| :ff / :unff | Use this command for LRs who pass a training session and need to be taken to the ranking line. | 
| :fly (Junior Moderator+) | SHRs should use this command to supervise the store or a training session. | 



| Command Names That Can Be Used (No information needed)       |
|:-------------|
| _:cmds_ |
| _:bans_           |
| _:info_         |
| _:pm (Junior Moderator+)._           |
| _:admins_           |
| _:chatlogs_           |
| _:logs_           |
| _:exploitlogs_           | 
| _:showtools_ | 



| Command Names that CANNOT Be Used (No information needed)       |
|:-------------|
| :crash |
| :h |

### Conclusion
{: .text-red-300 }
You reached the end of the Admin Guide! Please ensure that you read **all** the information thoroughly before you use your commands. If you have any questions, please refer back to this guide or contact a Junior Moderator+.
