---
title: Ticket Procedures
---
> [!WARNING]
> While the ticket procedures listed here are well-documented, it should be noted that they are merely a generic rule of thumb; ultimately, each ticket is handled on a case by case basis, and our approach may differ from what is noted down in these guidelines.

Generic procedures for tickets (appeals/general/reports):

---

#### **Appeals**

```
[User opens ticket]
  
- Check what Polar/TotemGuard flag user got banned for
- Ask for user's mod list
   (Optional: Ask user for logs; ping Blitical, ApplyNow or 0bi0 for this)
- Check mods/logs for prohibited mods

⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯

If no disallowed mods found:
- Unban user via either in-game or gamelink
- Run the command `/closerequest close_delay:24 reason:Appeal accepted`
  
If disallowed mods found + first time getting banned:
- Tell user to remove prohibited mods
- Unban user via other in-game or gamelink
- Run the command `/closerequest close_delay:24 reason:Appeal accepted`
- Run the command `/rename name:done-denied`
  
If disallowed mods found + not first time getting banned:
- Do not unban user
- Run the command `/closerequest close_delay:24 reason:Appeal denied`
- Run the command `/rename name:done-denied`
  
⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯

Special circumstances:
- If user modifies mod list and/or mods, extend their ban by one degree
   (e.g 14 day ban for hacks would become a 30 day ban for hacks)
```

---

### General tickets

```
[ User opens ticket ]
  
⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯

If user's inquiry is simple enough to answer:
- Refer to staff docs and respond to user
- Run the command `/closerequest close_delay:24 reason:Resolved`
  
If user's inquiry is more complicated or you do not understand:
- Ping another staff member (preferably your mentor or a Senior Mod+)
- Let them take over the ticket and handle the situation
  
If you're not allowed to handle a ticket for whatever reason:
- Pass ticket over to someone ranked Admin+ and let them handle it
  
⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯

Possible scenarios:

- Rank transfers:
  - Documented properly in [[Rank Transfers]]
    
- Bug reports:
  - Request proper bug documentation from user (e.g clips, screenshots etc.)
  - If possible, try to verify the bug's integrity yourself
  - Run the command `/rename name:🟣-bug-report`
  - Escalate ticket to Matt/Bram/OutDev and let them handle it from there

⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯

For Senior Mods:
- Refer to staff docs and reach a final decision. If still unsure of how to proceed, escalate the ticket to an Admin.

For Admins:
- Same as Senior Mods, escalate to Matt/Bram/OutDev if still unsure.
```

---

### Player reports

```
[ User opens ticket ]

- Request evidence from user (e.g clips, screenshots etc.)

⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯

If the provided evidence is sufficient, punish the user being reported:
- Punish user via either in-game or gamelink
- Run the command `/closerequest close_delay:24 reason:User punished!`
  
If the provided evidence is not sufficient, do not issue any punishment:
- Tell user that the evidence is insufficient, and a punishment can't be applied
- Ask user if they have any more evidence regarding their report:
  If they do:
    - Punish user via either in-game or gamelink
    - Run the command `/closerequest close_delay:24 reason:User punished!`
  If they don't:
    - Tell user that the evidence is insufficient
    - Run command `/closerequest: close_delay:24 reason:Insufficient evidence`
```

---