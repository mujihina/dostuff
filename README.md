**Author:** Mujihina
**Version:** v1.2014.09.29

This addon will help you do repetitive command line tasks.

# Command #

Syntax can be obtained by running the command without arguments, or with the subcommand 'help'

Current syntax is:
- 'dos list' : Review current settings
- 'dos start': Start doing stuff
- 'dos stop' : Stop doing stuff
- 'dos cmd'  : Specify command to repeat.
- 'dos count': Specify count (0 will loop forever, which is default)
- 'dos delay': Specify delay (default is 5 secs). This can be adjusted while dostuff is running if needed.


##Examples:##
- Say you want to repeat the lastsynth 24 times:

```
dos cmd /lastsynth
dos delay 24
dos start
```

- Say you need to go AFK for a few mins while nuking a WKR
```
dostuff cmd /ma "Fire" <t>
dostuff delay 5
dostuff count 0
dostart start
```

- Say you cast a spell on a trust/alt (party member 2) all night.
```
dostuff cmd /ma "Cure" <p2>
dostuff delay 6
dostuff count 0
dostart start
```


##TODO##


##Changelog##

### v1.2014.09.29 ###
* First release.
