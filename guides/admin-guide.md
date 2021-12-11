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

## TSA Info 
A modified version of the Basic Admin Essentials command system. This system is modified to allow for HTTP actions, anti-exploit, and more. Basic Admin Essentials created by **TheFuryFish**. Modified by **Axcracy**. Assisted by **TheCakeChicken**.

### 1 - Commands
#### 1A - Permission Levels
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

Depending on the role, you will only be able to perform certain commands. For examples, users with Moderator commands **cannot** run ;pban, but users with Super Admin commands can. 

#### 1B - Executing Commands
{: .no_toc }
When executing commands, you must take care to ensure you are doing it correctly. 

* TSA allows you to run a command by typing "/e" in front of a command. 
  * To run a command privately with the "/e" method, you need to first open up chat to run a command like you usually would. Before running the command, however, you need to type "/e."
    * EX:  **_/e :m Hello!_**
  * This will make the command private, and this hidden from the chat. 
* You may also use the console to carry out a command. 
  * To use the console, you need to first press ";" or "'" on your keyboard. This will cause a GUI to appear at the top of your screen. When using the console, the prefix is **not** required. 
    * EX: ; (Console Opens) 
      
      **_exploit logs_**

      ( Exploit logs GUI is then shown as expected) 
      
### 2 - Anti-Exploit
As mentioned at the start of this document, TSA features a built in Anti-Exploit system, which keeps out exploiters, and automatically bans/kicks depending on the serverity. 

* All detected exploits can be viewed with the :exploitlogs command. **Please do not stay under the impression that :exploitlogs will show exploiters who are currently in the server, and show what they are doing. The system can not detect everything, and only logs when an exploiter is automatically banned.** 
* If you are hosting a shift, and you notice that an exploiter gets banned, **please do not call for a SHR unless they are able to rejoin. It may take up to 30 seconds for them to be kicked again, as the HTTP API needs to be re-synced!** 

### 3 - Downtime
Downtime, also known to many as, "**THE ADMIN SYSTEM IS NOT WORKING!!!!**", is a time in which a critical error has occured within the code, stopping all comands being run, and by extension, your admin being given. 

* In this scenario, the Head Moderators+ kindly request that **you do not spam ping us, dm us repeatedly or anything of the sort when this occurs.** Doing so is **_punishable,_** and could get you possibly demoted. Axcracy and TheCakeChicken are aware of the problems, and are likely fixing them as you worry. 
* A simple fix may be just be rejoining. If a server shuts down, many people rejoining exactly at the same time can overload the system, and may cause your admin loading to be delayed, or just completely aborted. For this reason, we request that you **wait a few minutes** before rejoining, or **just simply rejoin.**

### 4 - Acceptable Usage
This is the main section of the document. It will outline everything that you can and not do with your commands. 

All major admin abuse (running ;pban all etc.) is **logged** and will result in an instant punishment! The command will be immediately canceled, and developers are notified. 

#### 4A - All commands Usage
{: .no_toc }

**Arguments** = What you need to supply to run the command. 

**Allowed** = What you may use this command for. 

**Not Allowed** = What you may not use this command for. 

**Punishment** = What happens if you use it inappropriately. 

**Logs All Attempts:** Whether or not doing all as a player logs.

Commands in _italic_ do not have any consequences / information to say about them. You may use them! Commands with a ~~strikethrough~~ must not be used AT ALL! Using them could lead to severe consequences.

| Command Name        | Arguments  | Allowed | Not Allowed | Punishment | Logs All Attempts |
|:-------------|:------------------|:------|:-------------|:------------|:------------------|
| _:cmds_           | No information. | No information.  |   No information.           |     No information.        |                   |
| :respawn / :res / :refresh / :ref          | A player | You can respawn yourself and anybody who may request it.  |  You may NOT do :respawn all, or respawn users who **do not** request a resapawn.           |  Ranges from a warning to permanent ban, depending on the severity.          |  No.                 |
| _:bans / pbans_           | No information. | No information.  |   No information.           |          No information.   |       No information.            |
| _:info_         | No information. | No information.  |    No information.          |       No information.      |       No information.            |
| :kick (Assistant Director+).           | A player, a reason. | Anyone with 3 or more warnings or for a valid reason.  |  Anyone with 3 or less warnings and for an invalid reason.  | Ranges from a blacklist to a permanent ban, depending on the severity.            |    Yes.               |
| :ban (Assistant Director+).           | A player, a reason. | Anyone with a valid reason (read the Punishment Guide). | Anyone with an invalid reason.             |  Ranges from a warning to a permanent ban, depending on the severity.       |     Yes.              |
| :unban (Assistant Director+).           | A player, a reason. | Anyone with a valid reason (read the Punishment Guide). | Anyone with an invalid reason.             |  Ranges from a warning to a permanent ban, depending on the severity.       |     No.   |
| :pban (Junior Moderator+).           | A player, a reason. | Anyone with a valid reason (read the Punishment Guide).  |  Anyone with an invalid reason.            |  Ranges from a warning to a permanent ban, depending on the severity.           |   Yes.                |
| ~~:crash~~           | No information. | No information.  |      No information.        |     No information.        |        No information.           |
| ~~:h (SHOULD NOT BE USED BY ANYONE)~~           | No information. | No information.  |  No information.            |   No information.          |       No information.            |
| :sm / :m (Junior Moderator+ in-store ONLY).           | A message. | Announcements that everyone needs to see.  | Messages that are unimportant / do not need to be seen by anyone. | Ranges from a warning to a permanent ban, depending on the severity.          |  No.                 |
| _:pm (Junior Moderator+)._           | No information. | No information.  |        No information.      |   No information.          |         No information.          |
| _:admins_           | No information. | No information.  |  No information.            |    No information.         |     No information.              |
| :mod / :admin / :superadmin (DEV+).           | No information.  | No information.  |    No information.          | No information.            |    No information.               |
| :unadmin (Head Moderator+ ONLY.)           | A player. | Only users who are Head Moderator+ may use this command. This can be used for users who are undergoing admin abuse, but do not warrant for a ban.  |   Using this if you are not a Head Moderator+.           |     Permanent ban.        |        Yes.           |
| :s (DEV+ ONLY).           | No information. | No information.  |   No information.           |     No information.        |                   |
| _:chatlogs_           | No information. | No information.  |   No information.           |     No information.        |                   |
| _:logs_           | No information. | No information.  |   No information.           |     No information.        |                   |
| _:joinlogs_           | No information. | No information.  |   No information.           |     No information.        |                   |
| _:exploitlogs_           | No information. | No information.  |   No information.           |     No information.        |                   |
| _:shutdownlogs_           | No information. | No information.  |   No information.           |     No information.        |                   |
| :shutdown (Head Moderator+ ONLY).           | Only users who are Head Moderator+ may use this. Use if there is a serious scripting bug & with authorization from Developers/Group Owner. | N/A.  |   Using it if you are not a Head Moderator+.         |     N/A.       |    No.               |
