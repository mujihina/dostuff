**Author:** Mujihina
**Version:** v1.2014.09.29

This addon will help you do repetitive command line tasks.

# Command #

Syntax can be obtained by running the command without arguments, or with the subcommand 'help'

Current syntax is:
- 'dostuff list' : Review current settings
- 'dostuff start': Start doing stuff
- 'dostuff stop' : Stop doing stuff
- 'dostuff cmd'  : Specify command to repeat.
- 'dostuff count': Specify count (0 will loop forever, which is default)
- 'dostuff delay': Specify delay (default is 5 secs). This can be adjusted while dostuff is running if needed.


##Examples:##
- Say you want to repeat the lastsynth 24 times:

```
dostuff cmd /lastsynth
dostuff delay 24
dostart start
```

- Say you need to go AFK for a few mins while nuking a WKR
```
dostuff cmd /ma "Fire" <t>
dostuff delay 5
dostuff count 0
dostart start
```


##TODO##


##Changelog##

### v1.2014.09.29 ###
* First release.