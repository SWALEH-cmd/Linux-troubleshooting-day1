# Linux troubleshooting Day 1
## What i Did
- Created a log file
- Read logs using cat
- found errors using grep
## Scenario
Application was not working. I checked logs and found an error.
## skills
-Linux troubleshooting 
-Log analysis

# Linux troubleshooting Day 2
    -Problem: Permission denied
    -Cause: File had no permissions
    -Fix: used chmod to restore permissions
# skills
    -Linux troubleshooting
    -Permissions

# Linux troubleshooting day 3
-Service Failure {Apache}
   -Problem: Service was not running
   -cause: apache stopped
   -fix: used systemctl start apache2
-Skills:
   -service troubleshooting
   -systemctl commands
# Linux troubleshooting day 4
-Port and Service issue
   -problem: Website not loading
   -cause: Apache service stopped {port 80 not active}
   -fix: Restarted apache using systemctl
   # Skills:
      -Port troubleshooting
      -Service debugging
 # Linux troubleshooting day 5
 -Log Debugging
    -Problem: Apache failed to start
    -cause: Invalid configuration
    -fix: Used journalctl to find error and fixed it
    #skills:
      -Troubleshooting
      -Log analysis
      -system debugging
 # Linux troubleshooting day 6
 -Disk Space Troubleshooting
   -What i did:
       .Checked disk usage using df -h
       .Identified disk usage increase
       .Created large files to simulate usage
       .Removed files to free space
-Skills:
       .Disk monitoring 
       .File management
       .Troubleshooting
