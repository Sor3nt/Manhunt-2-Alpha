

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


