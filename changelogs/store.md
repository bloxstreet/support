---
layout: default
title: Store Changelog
parent: Changelogs
nav_order: 1
---

# Store Changelog
This page outlines all changes made to the store, displaying the build number (viewable in the client dev console, and the help section of the Roblox 'esc' menu) and release date (DD/MM/YYYY)

### Build 8676 (03/04/2022)
{:.text-blue-000}

Fixed:
- Hand to will now time out after 60 seconds of no response
- Hand to now works without resetting your character
- Repeatedly pressing H will no longer glitch out the state of the hand to GUI
- Somehow dying no longer leaves you in a state of purgatory
- The top message UI has been moved down to fit with the new UI
- The restart GUI no longer states that there is an update, just that servers are restarting

### Build 8672 (02/04/2022)
{:.text-blue-000}

Added:
- New topbar menu GUI
- New bottom-left options list
- Pet rocks.

Fixed:
- Changed the player loading logic to improve performance
- Nametags now load correctly
- Bloxbiz now loads 2D adverts 60 seconds after server start to attempt to prevent HTTP errors
- The music mute button now operates correctly
- The info section of the main menu now says BloxStreet instead of Target Store
- The Rainbow Unicorn now has a price
- Chai Latte and Cappuccino are now spelled correctly
- Self Checkouts now show BloxStreet instead of Target Store
- Mops no longer give you a higher jump power
- People no longer get kicked when going off/on duty

### Build 8619 (28/03/2022)
{:.text-blue-000}

Added:
- A neat lil' sign in the staff room

Fixed:
- TSA punishments
- Bloxbiz being greedy with HTTP
- Payouts every 5 minutes

Removed:
- Herobrine
- My dignity

### Build 8586 (14/03/2022)
{:.text-blue-000}

Fixed:
- Shift scheduling times
- In-game ranking API (Used in rank redemption)
- A few cosmetic bugs around the store

Removed:
- Scavenger hunt

### Build 8541 (21/02/2022)
{:.text-blue-000}

Fixed:
- Flaw with the cuff system, allowing exploiters to mass jail (Reported and fixed within 15 minutes.)

### Build 8532 (15/02/2022)
{:.text-blue-000}

Fixed:
- Exploiters being able to bypass TSA pbans

Removed:
- SHR join notification

### Build 8526 (13/02/2022)
{:.text-blue-000}

Added:
- More anti-exploit detections

### Build 8512 (05/02/2022)
{:.text-blue-000}

Added:
- Security call buttons
- Box carts
- New staff spawn room
- Moved Cafe, Pharmacy and Optical Center

Fixed:
- Registers now say "BloxStreet" instead of "Target Store"

### Build 8441 (24/01/2022)
{:.text-blue-000}

Fixed:
- Staff panel kick now runs with correct permissions
- Warning cooldown reduced to 15 seconds

### Build 8426 (21/01/2022)
{:.text-blue-000}

Fixed:
- Players can no longer be spam-warned via the Staff Panel.
- Players can no longer be spam-kicked via the Staff Panel.
- Players can no longer be spam-banned via the Staff Panel.
- You can no longer punish anyone that is a higher rank than yourself via the Staff Panel.
- Staff Panel kicks/bans will now display as "TSP" rather than "TSA" to differentiate them from SHR actions.
- Staff Panel kick messages will now display "BloxStreet" instead of "Target"
- Staff Panel internal logs have had some typos fixed
- The shift end webhook message has been changed to display "BloxStreet" instead of "Target"
- The shift timer will now always display two digits (e.g. 12:1 remaining => 12:01 remaining)

### Build 8384 (16/01/2022)
{:.text-blue-000}

Fixed:
- Bloxbiz ads (yay! /s)
- HR rank claiming

### Build 8347 (11/01/2022)
{:.text-blue-000}

Added:
- Two new shift times (7am & 9am EST)

Fixed:
- Cafe foods will no longer set off the security scanners
- Some vital ClickDetectors and ProximityPrompts are no longer vulnerable to exploits
- Tiramisu is now spelled correctly
- Pepperoni is now spelled correctly
- Glasses will now equip as their displayed colour
- SHRs will no longer collide with the part intended to prevent people standing on shelves

### Build 8337 (10/01/2022)
{:.text-blue-000}

Fixed:
- Money and point purchases made in Private servers will now save correctly.

### Build 8335 (09/01/2022)
{:.text-blue-000}

Changed:
- Shift pings in #session-notice will no longer ping @here. Instead, @Shift Ping will be pinged. 

### Build 8321 (08/01/2022)
{:.text-blue-000}

Fixed:
- Staff schedule board has been updated with new timings
- Chat system will get normal Roblox updates
- Donation boards now operate as normal again
- Store Intern+ will now be awarded points as expected when serving at a register
- Points will no longer be awarded in private servers
- The 'i' button on the topbar will no longer remove your chat
- The wallet button on the topbar will no longer remove your chat
- Those tools with collisions enabled have now had them disabled to prevent glitching
- Extended the hitbox for the stealing scanners to prevent bypassing
- Renamed "Expresso" to "Espresso" in the cafe

### Build 8310 (03/01/2022)
{:.text-blue-000}

Fixed:
- Hole in cafe wall
- Cafe machines

Removed:
- Ranking sticks for administrators
- Reverted new registers

### Build 8298 (02/01/2022)
{:.text-blue-000}

Added:
- New registers
- New Cash Card

Fixed:
- Register Bugs

### Build 8293 (02/01/2022)
{:.text-blue-000}

Fixed:
- Trainees can now pick up boxes
- Staff can no longer glitch multiple boxes into their inventory (We are working on something to let people take multiple - stay tuned!)

### Build 8250 (30/12/2021)
{:.text-blue-000}

Added:
- Added ranking sticks for administrators

Fixed:
- Morph button can no longer be spammed to make yourself really, really small.
- Debounce on shelf items (2 second wait between taking any item)

### Build 8236 (25/12/2021)
{:.text-blue-000}

Added:
- Character scale button & gamepass - Become small!

Fixed:
- DataStore module failing to display data for some players on join
- Morph cooldown & gamepass messages not displaying

Removed:
- Build number GUI display (Use the Esc menu > Help or the Dev Console (F9) to see the current build)

### Build 8209 (19/12/2021)
{:.text-blue-000}

Fixed:
- Sandwich shop will no longer allow players to create sandwiches
- Sandwich shop will now destroy an in-progress sandwich if the staff member making it leaves

### Build 8207 (11/12/2021)
{:.text-blue-000}

Added:
- Sandwich shop (Currently open to staff and premium only)

Fixed:
- Fixed wall issues
- Fixed light issues
- Migrated more scripts over to Apollo

### Build 8164 (05/12/2021)
{:.text-blue-000}

Added:
- Extra furnishings to premium hotel rooms

### Build 8159 (05/12/2021)
{:.text-blue-000}

Added:
- Build number display (bottom-left of the screen)

Fixed:
- Bloxbiz will now delay its load to avoid overusing HTTP requests
- Blacklisted people can no longer redeem ranks
- Webhooks will no longer cause spam issues
- Build number display will no longer overlap "Current Shift" info UI

Removed:
- Player list rank display (Couldn't see full rank)
