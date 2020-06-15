# Centreon 20.4
minHelpCommand.php command name variable RCE (CVE-2020-12688)
Date Discovered: 30/04/2020
Date Disclosed: 15/06/2020

Command execution through unused minHelpCommand.php (removed in version 19.04).
The removed function was accessible to logged in users who could trigger remote code execution by editing the command name variable.
