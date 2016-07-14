# Remove Microsoft® Telemetry and Annoyances

This script disables Microsoft®'s telemetry, removes the function of the telemetry, in addition to updates that are typically considered annoying for the day to day users, and ensures that least information is sent back to Microsoft® by adding Microsoft®'s telemetry servers to hosts file. This script is *forked from tarampampam's remove_MS_telemetry.cmd*, and is unofficially continued script as the author has officially claimed that he / she will no longer provide update to the script.

# Documentation

Few things to note in mind:

- *Always* to review the script first, see the changes that is going to make to your computer before running the script!
- This script is experimental is not to be used in day to day production machine without reviewing the changes that is going to make to your Windows installation.
- You may need to disable HIPS (Host Intrusion Detection System) in addition to your anti-malware software or whitelist this script to allow the changes to be made to your computer.
- Be sure to ask or file an issue if you need help or if the script is not working as it is intended to be. Please feel free to file a new issue should Microsoft release a new 'evil' update.

Download and run the script with administrator privilege.

###Script Support Arguments:                                               

 -kb ^| -hotfixes Do NOT uninstall updates                              
 -d ^| -disable   Do NOT disable updates                                
 -t ^| -tasks     Do NOT disable tasks                                  
 -s ^| -services  Do NOT disable services                               
 -i ^| -ip        Do NOT block IP addresses using route                 
 -f ^| -firewall  Do NOT block IP addresses using firewall              
 -h ^| -hosts     Do NOT add domains to hosts file                      
 -u ^| -updates   Do NOT change windows update settings                 
 -l ^| -log       Do NOT write messages to .log file                    
 -e ^| -exit      Exit when work is complete                      

# Disclaimer

Microsoft, Encarta, MSN, and Windows are either registered trademarks or trademarks of Microsoft Corporation in the United States and/or other countries.

# License

This script is licensed under GPL v2.1. Feel free to contribute or create a fork, but be sure to leave a link or visible connection to the original source of this script.
