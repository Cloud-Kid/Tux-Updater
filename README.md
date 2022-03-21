# Automatic Maintainance

Automatic updater script i used in the Henkjaro concept ISO, and i also use for my daily drivers and servers.
Copy this to /usr/bin to install the script on your system (And optionally place the .desktop icon for the startmenu)

The usage is simple, and the script is easy to customize with your own update routine (for example to adapt it to other distro's).

- auto-maintainance without arguments will run the automatic maintainance routine

- auto-maintainance enable will install the systemd service that runs the maintainance every 30 minutes

- auto-maintianance disable will uninstall the systemd service that runs the maintainance every 30 minutes

- auto-maintianance gui will show a zentity based GUI, useful when bundling this kind of script with distributions

