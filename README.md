# CS:GO Settings
Saving my CS:GO console settings here, so I don't need to update them manually every time I switch/refresh my PC.
## Mouse / Windows
- 6/11 on Windows (with pointer precision disabled)
- 800dpi@1000hz
- Disable Xbox Game Bar / DVR
- Disable Focus Assist
- Untick CPU 0 when setting up the affinity
- Set a task to clear up RAM cache for every 3~5 minutes
## Launch Options
```-novid -console -high -freq 240 -tickrate 128 +cl_interp_ratio 1 +fps_max 300 +rate 786432```
### Crosshair
```cl_crosshairalpha 250; cl_crosshaircolor 4; cl_crosshaircolor_r 0; cl_crosshaircolor_g 255; cl_crosshaircolor_b 165; cl_crosshairdot 1; cl_crosshairgap -4; cl_crosshairsize 1; cl_crosshairstyle 4; cl_crosshairthickness 1; cl_crosshairusealpha 1;```
## Binds
```
bind "=" "toggleconsole";
bind "l" "demoui";
bind "q" "slot8";
bind "t" "slot7";
bind "v" "noclip";
bind "DEL" "disconnect";
bind "HOME" "mp_restartgame 1";
bind "MOUSE4" "+voicerecord";
bind "MOUSE5" "r_cleardecals";
```
## Other
```
sensitivity ".85";
zoom_sensitivity_ratio_mouse ".9";
m_rawinput "1";
m_mouseaccel1 "0";
m_mouseaccel2 "0";
m_mousespeed "0";
joystick "0";
joystick_force_disabled "1";
joystick_force_disabled_set_from_options "1";
```
## FACEIT AC
A shortcut, this makes FACEIT AC low priority:
```
C:\Windows\System32\cmd.exe /c start "" /Low "C:\Program Files\FACEIT AC\faceitclient.exe"
```
