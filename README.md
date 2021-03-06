# moca-guide
A guide to MOCA's commands

![MOC Logo](https://cdn.discordapp.com/attachments/965384850116837396/967849487747932170/Untitled265_20220419052546.png)

## What is MOCA?
MOCA stand for *Mystic Oaks Cafe Administration*, a play off the word "mocha", and will soon be the main way to handle interactions while training and other useful game functions. **To be clear, MOCA is *not* a guide on how to handle social interactions**, but it is instead a tool you can use to perform essential game functions and take actions against rule-breaking users. DM [lanjt#2129](https://discord.com/users/498984530968051713/) on Discord for any questions you may have.

## How do I use MOCA?
MOCA's current prefix is ``moc/``, but this may change in the future and will be posted in staff chats. Simply chat the prefix followed by the command and then command arguments, like so (example): ``moc/ban 12345 Exploiting and being rude towards players``. Command docs for MOCA will be given at the end of this page.

## Something is not working right, what do I do?
Upon startup, MOCA will dump a log of actions into the console. If a command is unresponsive or you think there are other issues, always check the developer console (F9) and click the ``Server`` tab and scroll all the way to the top. Here's an example of what you might see:
```
Loaded Command #1: kick            | Loaded in 0.20719480514526367    ms
Loaded Command #2: teleport        | Loaded in 0.016520977020263672   ms
Loaded Command #3: ban             | Loaded in 0.09710001945495605    ms
```
If an error has occured, some red text will appear. Always report these to my Discord! 

## Important argument notice
When specifying a ``Player`` argument, you can optionally use ``me`` or ``all`` to specify yourself or all players connected to the server, instead of specifying a player's name.

## Command documentation
| CommandName | Description | Arguments | Aliases | Rank |
| ----------- | ----------- | --------- | ------- | ---- |
| Teleport    | Teleport either yourself or another player to some player | <Player1: Player> ?<Player2: Player> | tp | Trainer+(11) |
| Kick        | Kick a player from the server | <Player1: Player> | boot | Trainer+(11) |
| Ban         | Ban a player from the experience | <Player1: Player> ?<Reason: string> | banana | Head Director+(20) |
| Refresh     | Reload a player's character and put them in the same spot they were before | ?<Player1: Player> | reset, loadcharacter | Trainer+(11) |
| Lock        | Lock a player in place | <Player1: Player> | | Trainer+(11) |
| Unlock      | Unlock a player out of plaace | <Player1: Player> | | Trainer+(11) |
