# stalky106
Ever wondered "how can SCP-106 get closer to its lore?" and wished that they just dissapeared at teslas, to make them easier to lose? Well, this plugin doesn't do that, but instead gets him closer to the lore by giving him the ability to stalk random people by placing a portal at their feet!

*Idea by ConnorTheCone and RogerFK*

# Discord
## Hop on this Discord if you want to get pinged about new releases: https://discord.gg/gS5ae5q

# Command

To use, open up the console, which varies between keyboard layouts, but it's usually the key below the ESC key or else ; (in the Spanish keyboard layout it's ñ, for example)
The command is `.stalk` and can be bound to a key by putting `cmdbind <key> .stalk`. Only SCP-106 can use this command and, for now, you can't target a specific player *(note: if you really want that feature, make sure to fork the repo, code it yourself and do a Pull Request!)*


# Translations

This plugin uses the default translation method used since Smod 3.4.0. Feel free to change it in the sm_translations folder that's just below your sm_plugins folder, the file is called stalky.txt. You can change any line and even use the [UnityEngine's Rich Text Formatting](https://docs.unity3d.com/Manual/StyledText.html) 

# Extra info about SCP-106's lore

SCP-106 teleports to the victims he wants, according to its lore. He is also lured by loud sounds, which seem to be an easy victim for him. However, [SCP-106 delays himself 10-15 minutes after the femur breaker](http://www.scp-wiki.net/once-but-not-now), which makes the Femur Braker totally anti-lore. Although this remains completely out of his main idea, the point of this is to make him more friendly, fun and balanced for a multiplayer experience. With that in mind, him teleporting to random players means that it will be kept fair and that targeting one enemy is completely impossible... unless he is the last target alive. Which also made me think that I should have done an extra cooldown, but... uh don't ask me why I didn't do it, really. Will be an implemented feature in the future if I see interest in this plugin. Let me know in Discord by pinging me if you want any feature, or feel free to open an "issue" at the top of this page.
Another one, he can get to his own pocket dimensions and go through any exit to get out from it. That means you can either use the portal or just walk through a portal to leave the pocket dimension. This game is really weird so it just teleports you back to the pocket dimension, nobody will care about it but you can really fuck with people while doing it.

# Configs
| Config Option | Value Type | Default Value | Description |
|:-----------------------:|:----------:|:------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| stalky_enable | boolean | true | Enables/Disables this plugin |
| stalky_stalk | boolean | true | Enables/Disables the stalk command |
| stalky_pocket | boolean | true | Enables/Disables the pocket command |
| stalky_pocket_damage | boolean | false | Makes SCP-106 hits unable to deal damage while in the pocket dimension. People will still be scared |
| stalky_cooldown | int | 30 | The time SCP-106's have to wait before stalking another player |
| stalky_initial_cooldown | int | 120 | The time SCP-106's have to wait before stalking it's first victim |
| stalky_ignore_teams | int List | 0, 2, 6 | [Teams](https://github.com/Grover-c13/Smod2/wiki/Enum-Lists#team) that the "stalk" command will ignore. (Defaults to SCPs, Chaos and Tutorial teams) |
| stalky_ignore_roles | int List | 3, 7 | [Roles](https://github.com/Grover-c13/Smod2/wiki/Enum-Lists#role) that the "stalk" command will ignore. (Defaults to other SCP-106 and SCP-079) |
| stalky_announce_ready | bool | true | Tells all SCP-106's when are they have their stalk command ready *(Note: disabling this will avoid using C# Tasks everytime, which will save resources. If your CPU usage is high, you may want to disable this feature)*|
| stalky_auto_tp | bool | true | Teleports SCP-106 just when the portal is created below their victim's feet. Really OP, but faithful to the main lore. |
| stalky_auto_delay | float | 0.2 | Time to elapse after the portal is completely created |
| stalky_role_names | Dictionary | 0:SCP-173, 1:Class D, 3:SCP-106, 4:NTF Scientist, 5:SCP-049, 6:Scientist, 8:Chaos Insurgent, 9:SCP-096, 10:Zombie, 11:NTF Lieutenant, 12:NTF Commander, 13:NTF Cadet, 14:Tutorial, 15:Facility Guard, 16:SCP-939-53, 17:SCP-939-89 | The role name Dictionary that will get displayed at the top when Larry finds a victim (for example, it would say "teleporting to X guy with role Y"). You can give it colors, style or even funny names. Whatever you feel like, but follow the aforementioned Rich Text guide to do it. |
