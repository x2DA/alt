# Alternative package manager wrapper for debian

# Why
Apt does not remove all packages it installs.
![Why](https://github.com/x2DA/alt/assets/why.png)
Alt also sucks, but differently.

# Usage
alt \[command\] \[parameter\]

Commands include:
  help - display usage [No param]
  list - list currently installed packages [No param]
  pkgc - list number of DPKG-installed packages [No param]
  inst - installs package [Package String]
  rem - purges package [Package String]
  up - update package list AND upgrade packages [No param]

# Dependencies
`dpkg` , `apt`
Basic system utilities (`sed`, `grep`, etc.)

