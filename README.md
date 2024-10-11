# "Smallest" Windows Taskbar

**Taskbar**:

Safety step:
Go to: **System properties** > **System Protection** 
And make **backup** there.

S1:
Go to **Registry Editor**
And search for: `HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer`
Change: **TabletPostureTaskbar** to `1`.

S2: 
Stay in **Registry Editor**
And search for:
 `HKLM\SYSTEM\CurrentControlSet\Control\PriorityControl`
Change: **ConvertibleSlateMode** to `1`.

Its all.

*If I can figure out how to shrink the taskbar that slides out, I'll edit it there.*

# Photos:

Hidden:![{A450477D-7589-462B-9B70-FADD81D2B967}](https://github.com/user-attachments/assets/fb98ddb3-b40a-49da-886a-2d65ec360eb0)

Unhide:![{4B8E3B3E-5E9E-4BDF-AE60-A395CEDF43C4}](https://github.com/user-attachments/assets/693e630f-603e-49ef-abff-454c8a5b2ddd)

