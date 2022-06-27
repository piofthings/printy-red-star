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

3DMN - How to determine Z Endstop offset https://www.youtube.com/watch?v=y_1Kg45APko


# For BTT E3 V2.0 Board
## To flash firmware (assuming _USB support has been compiled)
- Connect to OctoPi using FileZilla
- Compile the firmware and copy `firmware.bin` to the OctoPi using FileZilla to the `OctoPrint` folder
- SSH into the Pi via a Terminal/Putty
- `cd ~/OctoPrint`
- Mount the SD Card (on the BTT board)
    - `sudo mount /dev/sda1 /mnt`
- Copy the firmware to the SD Card in the BTT board
    - `sudo cp ./firmware.bin /mnt`
- Unmount the SD Card as USB device from the Pi
    - `sudo umount /mnt`

- After this, reset the BTT Board either by pressing the reset button (this may cause issues with OctoPrint) the safest way possible. In my setup where OctoPrint controls power to the BTT board, switch the Power Off and the back On.
