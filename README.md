# zgui

This is an UI system written in ZScript.
It allows for some limited abstraction from actual event sources, be it menus, statusbar, event handlers or anything.
All it requires is that you call OnDraw, OnTick, OnProcessUi and OnProcessInput methods.

Additionally, it provides SetHudSize/SetHudClipRect-like functionality, but with direct drawers.

The example code can be found here: https://forum.zdoom.org/viewtopic.php?p=986562#p986562

Test commit
