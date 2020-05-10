Crosslink video : How to setup Platform IO with Atom (slightly dated) https://www.youtube.com/watch?v=RbbzsJBpEhc

Tom's 3D : How to auto tune PID https://toms3d.org/2014/04/01/3d-printing-guides-using-marlins-pid-autotune/

https://danielstanton.co.uk/357/configuring-marlin-2-0-for-an-ender-3-pro-and-bltouch/

Run command following command to set PID

```
# For hotend
M303 S260 C10
```
```
# For Heated bed
M303 E-1 S70 C10
```


Status of Endstops

M119
