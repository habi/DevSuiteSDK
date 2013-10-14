% DevSuite Software - Internal Release Notes for DevWareX
% Rel 1.0; Build date 7/1/2013
%

Aptina Imaging Corporation, Confidential and Proprietary Information. Any
duplication, reproduction, distribution, modification, or alteration is
prohibited without the express prior written permission of Aptina Imaging
Corporation.

Aptina Imaging Corporation Internal Use Only

# What Works So Far but maybe not fully (Windows)
- Startup Choices dialog, same as DevWare except only remembers most recent file
- Startup Wizard dialog, same as DevWare
- Identify and start up sensor/SOC/ISP; AP010x not supported (secondary sdats
  and ini’s still in progress)
- Show video in main window, Play/Pause/Stop buttons
- Info panel, dockable; less info than DevWare
- Register panel, dockable; no tabs, and only Add To Favorites on right-click
  menu
- Register Search dialog
- User Control Panel (a.k.a. scripted register dialog)
- Sensor Control dialog, very limited controls
- Image Control dialog (Sensor Control pages that control software colorpipe or
  otherwise not the sensor), very limited controls
- Presets dialog; only one, and only Load, Edit and Reload buttons
- Python Console, dockable; command history needs work
- ICP Debug Console, dockable; no Tail option
- Grab and Snapshot, and save to file; not all formats supported on all OS’s
- User Toolbars, including menus, tooltips, etc.
- Other toolbar buttons and menus that aren’t grayed out.
- Transport DLLs and Colorpipe Filter DLLs

# What is Not Working Yet
- Video window only shows main image, not interleaved image (postview, bubble,
  etc.).
- Full screen mode
- Video record
- Mouse selection in video window
- Menus and buttons that are grayed out, notably Register Log, Graph, Magnifier,
  Watch, Options, Captured Images (a.k.a. Filmstrip)
- Dialog plug-ins
- Zoom in/out is primitive
- Transparency doesn’t work on User Toolbar icons that are .bmp format files.

# Known Issues
- In the Register Dialog, bitfields can only be modified via the check-boxes on
  Windows. On Linux and Apple, the highlighted check-box is not in sync with the
  currently selected bitfield.
- JPEG decompress functions need to debug (compression function works fine).
- Tiff compression function causes color shift.

# Installation Instructions
Macintosh: TBD
Linux: TBD

# To Create Bug Reports and Feature Requests:
Click bug report button on DevWareX or use this
[link](http://sjca-atlassian:8080/jira/secure/CreateIssue!default.jspa).

# Known Bugs
Use this
[link](http://sjca-atlassian:8080/jira/secure/IssueNavigator.jspa?mode=hide&requestId=11511)
 to view all open DevSuite issues.

# Technical Support
Please contact bdirks@aptina.com.
