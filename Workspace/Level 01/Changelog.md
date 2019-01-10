

#Port from PS2 Beta:

####triggerNoiseRem

Add to **levelscript.srce**

> Unknown right now
```
SetVector(pos, -13.739, 0.0, 40.7047);
SetVector(pos2, -13.3013, 2.19097, 44.1915);
CreateBoxTrigger(pos, pos2, 'triggerNoiseRem');
```

Copy Script **23#noiser.srce**



####triggerLoon3

> Jump scare script

Add to **levelscript.srce**

```
SetVector(pos, -17.1411, 6.69318, 26.8479);
CreateSphereTrigger(pos, 0.670224, 'triggerLoon3');
```

Copy Scripts **16#triggerjumpingscare**


####Chair

> Alternative Chair spawn position

Add to **levelscript.srce**

```
SetVector(pos, -9.35898, 0.238085, 2.01603);
SetVector(pos2, -9.15928, 3.68042, 4.71386);
CreateBoxTrigger(pos, pos2, 'triggerWheelchair');
```


