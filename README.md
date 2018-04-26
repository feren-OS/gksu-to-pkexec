# GKSU -> PKEXEC
A command parser to pass GKSU commands to PKEXEC.


Tests on Feren OS:
- Running a graphical app through it - PASS
- Installing a package with GDEBI - PASS
- Running a command through it - PASS

Known Issues:
- The command is always called '/usr/bin/env' by PKEXEC's dialog.
