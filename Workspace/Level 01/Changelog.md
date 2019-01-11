#Port from Alpha:

####Enable Truck Cutscene

>  commented in some elements from **InCarParkCutScene**

Affected file **playerscript.srce**

>  commented in some elements from **EndOfLevelCutScene**

Affected file **levelscript.srce**


####Enable Truck Cutscene 2

Commented in **levelscript.srce**

```
RunScript('player(player)', 'EndOfLevelCutScene');
sleep(100);
while IsCutSceneInProgress do sleep(50);
```


####Initialize the old Monitor script

> just commented in the **InitMonitors** parts

Affected file **levelscript.srce**


#Port from PS2 Beta:

####Jump scare script

> Todo: this breaks the first tutorial because both share the same char (?)

Add to **levelscript.srce**

```
SetVector(pos, -17.1411, 6.69318, 26.8479);
CreateSphereTrigger(pos, 0.670224, 'triggerLoon3');
```

Copy Scripts **16#triggerjumpingscare**


####Beta Chair spawn position

Add to **levelscript.srce**

```
SetVector(pos, -9.35898, 0.238085, 2.01603);
SetVector(pos2, -9.15928, 3.68042, 4.71386);
CreateBoxTrigger(pos, pos2, 'triggerWheelchair');
```


