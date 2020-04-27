# vMixAudioMatrix

Online live version available here:
http://njastad.com/vMixAudioMatrix/

Download the HTML file, open it in Chrome and/or take that link and paste it into vMix as a Browser source (should start with file:///)

To configure the HTML file, add URL arguments to the URL like this:

```
file:///C:/.../vMixAudioMatrix/index.html?IP=127.0.0.1&Inputs=1,2,3&Buses=M
```

The available parameters are:


"IP" defines the target IP. 
Default: localhost
```
Syntax: IP=127.0.0.1
```

"Port" defines the target Port. 
Default: 8088
```
Syntax: Port=8089
```
"Inputs" Filters for specific inputs. 
Default: no filter, shows all inputs
```
Syntax: Inputs=1,2,4
```

"Buses" Filters for specific Buses. 
Default: no filter, shows all buses
```
Syntax: Buses=M,A,F
```

"Zoom" defines the zoom of the table. 
Default: 1
```
Syntax: Zoom=0.5
```

"Interval" defines the refresh interval in ms. 
Default: 100
```
Syntax: Interval=500
```

"Names" defines custom names for each bus.
Default: none
```
Syntax: Names=M:Live Output,B:Speakers
```
