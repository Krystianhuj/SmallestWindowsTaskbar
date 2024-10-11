# "Smallest" Windows Taskbar

**Taskbar**:

Safety step:
Go to: **System properties** > **System Restore** >  **System Restore**
And make **backup** there.

S1:
Go to **Registry Editor**
And search for: `HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer`
Change: **TabletPostureTaskbar** to `1`.

S2: 
Stay in **Registry Editor**
And search for:
 `HKLM\SYSTEM\CurrentControlSet\Control\PriorityControl`
Change: ConvertibleSlateMode to `1`.

Its all.

*If I can figure out how to shrink the taskbar that slides out, I'll edit it there.*
