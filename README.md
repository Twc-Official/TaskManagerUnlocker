# TaskManagerUnlocker V2.75 -- 01/11/24

## NOTE: V2.0 DOES NOT WORK -- DO NOT USE IT!
## Alert: DO NOT USE PREVIOUS VERSIONS - USE THE ONE THAT HAS THE SAME VERSION NUMBER AS THE TITLE OF THIS README!

This .exe file will change the registry for Task Manager to enable it. 
It may not work on school devices.

## Ways It Works:
- Regristry check 1 - HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Policies\Explorer for the NoTaskMgr value.
- Regristry check 2 - HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Policies\System for the DisableTaskMgr
- Regristry check 3 - HKEY_CURRENT_USER\Software\Policies\Microsoft\Windows\System for the DisableTaskMgr value.
- Other Regristry checks, If those fail, powershell is used.

