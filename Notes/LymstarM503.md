
Send: M503
Recv: echo:  G21    ; Units in mm
Recv: echo:  M149 C ; Units in Celsius
Recv:
Recv: echo:Filament settings: Disabled
Recv: echo:  M200 D3.00 -- Done
Recv: echo:  M200 D0    -- Don't know
Recv: echo:Steps per unit:
Recv: echo:  M92 X80.00 Y80.00 Z400.00 E402.00 -- Done
Recv: echo:Maximum feedrates (units/s):
Recv: echo:  M203 X500.00 Y500.00 Z12.00 E120.00 -- Done
Recv: echo:Maximum Acceleration (units/s2):
Recv: echo:  M201 X9000 Y9000 Z500 E10000        -- Done
Recv: echo:Acceleration (units/s2): P<print_accel> R<retract_accel> T<travel_accel>
Recv: echo:  M204 P1500.00 R1500.00 T1500.00     -- Done
Recv: echo:Advanced: S<min_feedrate> T<min_travel_feedrate> B<min_segment_time_ms> X<max_xy_jerk> Z<max_z_jerk> E<max_e_jerk>
Recv: echo:  M205 S0.00 T0.00 B20000 X10.00 Y10.00 Z0.20 E2.50   -- Done S,T,B values in \_adv.h file
Recv: echo:Home offset:
Recv: echo:  M206 X11.20 Y14.20 Z0.00 -- Don't know
Recv: echo:Material heatup parameters:
Recv: echo:  M145 S0 H200 B60 F0 -- Done
Recv:   M145 S1 H240 B80 F0  -- Done
Recv: echo:PID settings:
Recv: echo:  M301 P20.00 I1.00 D95.00 -- Done
Recv: echo:LCD Contrast:
Recv: echo:  M250 C32
Recv: ok

---

**Bootup sequence**
Recv: echo:SD init fail
Recv: start
Changing monitoring state from "Detecting baudrate" to "Operational"
Recv: echo: External Reset
Recv: Marlin 1.1.4
Send: N0 M110 N0*125
Recv:
Recv: echo: Last Updated: 2017-07-04 12:00 | Author: (none, default config)
Recv: Compiled: Jan  8 2018
Recv: echo: Free Memory: 2153  PlannerBufferBytes: 1264
Recv: Here=0
Recv: echo:V05 stored settings retrieved (466 bytes; crc -31986)
Recv: echo:  G21    ; Units in mm
Recv: echo:  M149 C ; Units in Celsius
Recv:
Recv: echo:Filament settings: Disabled
Recv: echo:  M200 D3.00
Recv: echo:  M200 D0
Recv: echo:Steps per unit:
Recv: echo:  M92 X80.00 Y80.00 Z400.00 E408.37
Recv: echo:Maximum feedrates (units/s):
Recv: echo:  M203 X500.00 Y500.00 Z12.00 E120.00
Recv: echo:Maximum Acceleration (units/s2):
Recv: echo:  M201 X9000 Y9000 Z500 E10000
Recv: echo:Acceleration (units/s2): P<print_accel> R<retract_accel> T<travel_accel>
Recv: echo:  M204 P1500.00 R1500.00 T1500.00
Recv: echo:Advanced: S<min_feedrate> T<min_travel_feedrate> B<min_segment_time_ms> X<max_xy_jerk> Z<max_z_jerk> E<max_e_jerk>
Recv: echo:  M205 S0.00 T0.00 B20000 X10.00 Y10.00 Z0.20 E2.50
Recv: echo:Home offset:
Recv: echo:  M206 X11.20 Y14.20 Z0.00
Recv: echo:Material heatup parameters:
Recv: echo:  M145 S0 H200 B60 F0
Recv:   M145 S1 H240 B80 F0
Recv: echo:PID settings:
Recv: echo:  M301 P20.00 I1.00 D95.00
Recv: echo:LCD Contrast:
Recv: echo:  M250 C32
Recv: Error:No Line Number with checksum, Last Line: 0
Send: M115
Recv: FIRMWARE_NAME:Marlin 1.1.4 (Github) SOURCE_CODE_URL:https://github.com/MarlinFirmware/Marlin PROTOCOL_VERSION:1.0 MACHINE_TYPE:LMYSTAR-V1 EXTRUDER_COUNT:1 UUID:cede2a2f-41a2-4748-9b12-c55c62f367ff
Recv: Cap:EEPROM:1
Recv: Cap:AUTOREPORT_TEMP:1
Recv: Cap:PROGRESS:0
Recv: Cap:PRINT_JOB:1
Recv: Cap:AUTOLEVEL:0
Recv: Cap:Z_PROBE:0
Recv: Cap:LEVELING_DATA:0
Recv: Cap:SOFTWARE_POWER:0
Recv: Cap:TOGGLE_LIGHTS:0
Recv: Cap:CASE_LIGHT_BRIGHTNESS:0
Recv: Cap:EMERGENCY_PARSER:0
Recv: ok
Send: M21
Recv: echo:SD init fail
Recv: ok
Send: M155 S2
Recv: ok
