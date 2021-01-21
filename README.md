# matlab.desktop

Hey!  A .desktop file so matlab has an application launcher in Gnome.  
You'll need to the change the StartupWMClass value to whatever the terminal command

            xprop WM_CLASS
            
gives you when you click on theMatlab window yourself.
Paste it in /usr/share/applications and you're good!
