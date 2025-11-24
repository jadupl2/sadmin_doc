
sdf (sadm_df.sh)

1 minute read

This is the SADMIN version of the ‘df’ command.

NAMEPermalink

sdf (sadm_df.sh)
SADMIN customize ‘df’ command

SYNOPSISPermalink

sdf (sadm_df.sh) [-d 0-9] [-h] [-n] [-t] [-v] 

$SADMIN/bin/sdf (sadm_df.sh) - v2.2
Posted 2021-06-13 - Updated 2021-06-13
Supported on Linux, Aix, MacOS
Can be executed on a client and on the SADMIN Server.

DESCRIPTIONPermalink

This is the SADMIN version of the ‘df’ command.

Back to the top

EXAMPLESPermalink

sdf output screen
Example with no temporary filesystem (option ‘-t’)Permalink

sdf -t output screen

Back to the top

OPTIONSPermalink
Options 	Description
[ -d 0-9 ] 	Set debug level from 0 to 9 (Default is 0)
[ -h ] 	Display this help and exit.
[ -v ] 	Output version information and exit.
[ -t ] 	Exclude tmpfs filesystem from output
[ -n ] 	Exclude nfs filesystem from output

ENVIRONMENTPermalink

    The “$SADMIN” environment variable must be defined and contains the root directory of the SADMIN tools (normally /opt/sadmin). It should be already done, the setup script have updated the ‘/etc/profile.d/sadmin.sh’ and the ‘/etc/environment’ files.
    The SADMIN configuration file, is needed and loaded in memory at the beginning of every scripts. This file should already exist and contains your SADMIN configuration and preference setting.
    For Shell script the Shell Library is used and for Python script the Python Library is used.

EXIT STATUSPermalink
Exit Code 	Description
0 	An exit status of zero indicates success.
1 	Failure is indicated by a nonzero value, typically ‘1’.

AUTHORPermalink

Jacques Duplessis
Any suggestions or bug report can be submitted at the support page

COPYRIGHTPermalink

Copyright © 2022 Free Software Foundation, Inc. License GPLv3+: GNU GPL version 3 or later
This is free software, you are free to change and redistribute it.
There is NO WARRANTY to the extent permitted by law.

SEE ALSOPermalink
Link to … 	Description
sview 	Command line summary of alerts and failed scripts of all your servers.
How-to update SADMIN 	How-to update to latest version of SADMIN
sadmin.cfg 	SADMIN main configuration file
sdf 	SADMIN version of the ‘df’ command.
smon 	Allow you run SysMon and see the report file

Tags: command_line

Categories: command_line

Updated: June 13, 2021
