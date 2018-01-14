# Remove Microsoft® Telemetry and Annoyances

This script disables Microsoft®'s telemetry, its evil M$ updates and tasks scheduled within tasks scheduler. It additionally blocks your computer's access to Microsoft®'s telemetry servers to ensure that no data is sent to the M$ servers. Please be advised that this script is *forked from tarampampam's remove_MS_telemetry.cmd, and this is unofficially continued script as the author of the script has abandoned the script.

# Documentation

Few things to keep in mind:

- *Always* review the script first, double check the changes that it is going to make to your computer before running the script!
- This script is experimental. Please do not use this script in *any* production environment without reviewing the changes that is going to make in your Windows installation.
- You may need to disable or whitelist your HIPS (Host Intrusion Detection System) in addition to your anti-malware software prior to running this script.
- Be sure to ask or file an issue with necessary information if you need help or if the script is not functioning as expected. Please feel free to file a new issue should Microsoft release a new 'evil' update.

Download and run the script with administrator privilege.

&nbsp; | Supported Arguments
----: | :-------------
-kb (-hotfixes)  | Do NOT uninstall updates
-d  (-disable)   | Do NOT disable updates
-t  (-tasks)     | Do NOT disable tasks
-s  (-services)  | Do NOT disable services
-i  (-ip)        | Do NOT block IP addresses using route
-f  (-firewall)  | Do NOT block IP addresses using firewall
-h  (-hosts)    | Do NOT add domains to hosts file
-u  (-updates)   | Do NOT change windows update settings
-l  (-log)      | Do NOT write messages to .log file
-e  (-exit)      | Exit when done

# Disclaimer

Microsoft, Encarta, MSN, and Windows are either registered trademarks or trademarks of Microsoft Corporation in the United States and/or other countries.

# License

This script is licensed under GPL v2.1. Feel free to contribute or create a fork, but be sure to leave a link or visible connection to the original source of this script.

