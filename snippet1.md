## Snippet #1
### /day command
```
command /day:
    trigger:
        set time to 7:00
        send "&6Set the time to &c1000 (Day)"
        loop all players:
            if loop-player has permission "*":
                if loop-player is not "%player%":
                    send "&7&o[%player%: Set the time to 1000 (Day)]" to loop-player
```
