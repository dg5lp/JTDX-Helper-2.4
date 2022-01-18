# JTDX-Helper-2.4.4

JTDX-Helper-2.4.4b: Supports JTDX-2.2-158 and JTDX-2.2.157. No older versions are supported 

JTDX-Helper-2.4.4a: Max. AF can be limited to 1000Hz (required for 60m band in GB)

JTDX-Helper-2.4.4: supports JTDX-2.2.157 and JTDX-2.2.156, but does not support 2.2.155 any more.

JTDX-Helper-2.4.3a: Bugfix only: Rep. Diff. works now...

News in 2.4.3 vs. 2.4.1:

- Rep. Diff. field: shows the average difference of received and transmitted reports. A positive number indicates that you receive better reports as you send.
- Repair bug ignoring stations calling CQ-DX in S/P-mode.
- Strategy selection and the status of all checkboxes are saved and restored when starting the Helper again.
- Minor fixes for non-standard callsigns

2.4.1 for JTDX was not released.  

News in 2.4.1 vs. 2.3:

- WSJT-X can be started with -rig=RIG-NAME extension (multiple instances are not supported)
- New CQ-strategy "CQ+SP". If no answer for CQ received, the Helper calls CQ-calling stations
- Calls stations sending 73 and RR73
- Optional repetition of RR73 if no 73 received at the end of the QSO. Warning if no closing 73 received.
- All "Auto Strategy" settings are working for incoming calls too.
- Filter are available to exclude and prefer specific continents.
- Counts successful and broken QSOs
- Automatic setting of the width of the Band-Activity and RX-frequency windows
- New log entry indicating missing 73 at the end of the QSOs

===============================================================

The JTDX-Helper program was developed as macro extension for the JTDX using the Quick-Macros program. Comparing to other FT8-Robot programs, the JTDX-Helper is more “intelligent”, it interprets the received messages of JTDX and acts according to the own pre-programmed QSO strategy. The delivered EXE file contains the licence for Quick-Macros.

Main Features of V2.4.3:

- Works with JTDX 2.2.155 and 2.2.156
- Automatic operation in both "CQ" and "S/P" mode.
- New mode: CQ+SP: It calls CQ and if no station answers, it calls CQ-calling stations.
- Calls stations sending 73 and RR73
- Automatic find of free frequency in CQ-mode
- Automatic changes between CQ and S/P mode with programmable intervals, dependng on band activity.
- Repeat RR73 if no closing 73 received
- Comfortable set-up of all parameter
- Easy installation
- WSJT-X can start with the -rig-name argument
- Opens the QRZ.com page of the station when starting a QSO

Various strategies in CQ- and S/P-mode, Calls stations with:

- Best Priority acording the WSJT-X "Colours" settings.
- Best S/N: If Stations with the same priority received, the one with the best S/N selected
- Only DX: Minimum DX-distance can be specified in Km and Miles.
- Prefer-DX DX stations are prefered.
- Most distance
- Prefer Wanted: prefixes, DXCC-entities and continents can be specified.
- Only Wanted: prefixes, DXCC.entities and continents can be specified
- Exclude stations, präfixes DXCC-entities and continents can be specified
- Keep-Even/Odd cycle for 6m DX-ing

Band-Hopping:

- Programmable on daily basis
- Two time ranges per day can be programmed
- Operating band, mode, and strategy can be selected.

Feedback to: dg5lp@darc.de
