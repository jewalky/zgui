# zgui

This is an UI system written in ZScript.
It allows for some limited abstraction from actual event sources, be it menus, statusbar, event handlers or anything.
All it requires is that you call OnDraw, OnTick, OnProcessUi and OnProcessInput methods.
