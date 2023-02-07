# Windows Shut Down Script

## Description 
Windows bat file for turning of your pc.

Made with batch:

## Code explaind
```
shutdown.exe -s -t 10 -c "Removing all your files in T-10 seconds"
```
> Calls shutdown.exe using -s "self" \
> Sets the -t "time" in this case 10 seconds \
> Sets the -c "caption" to in this case "Removing all your files in T-10 seconds"

```
shutdown.exe -s will shut the pc down instantly.
```
```
-t and -c are optinal.
-t requiers a interger: x
-c requiers a string: "y"
```

### Note
###### You can change the code to your liking. 
###### Change x and "y" to what ever you like :smile:
