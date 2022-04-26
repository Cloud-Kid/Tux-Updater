# Tux Updater

A small utility to update a variety of package type on Arch/Debian based distributions. 

A lot of the work goes to @Henky!!, you can find the original script here https://gitlab.com/henk717/manjaro-automatic-update, since it seems not to be updated, I will continue to tweak and update it as munch as I can.

---

Copy this to /usr/bin to install the script on your system (And optionally place the .desktop icon for the startmenu)

The usage is simple, and the script is easy to customize with your own update routine (for example to adapt it to other distro's).

- auto-maintainance without arguments will run the automatic maintainance routine

- auto-maintainance enable will install the systemd service that runs the maintainance every 30 minutes

- auto-maintianance disable will uninstall the systemd service that runs the maintainance every 30 minutes

- auto-maintianance gui will show a zentity based GUI, useful when bundling this kind of script with distributions

