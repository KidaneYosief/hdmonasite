# hdmonasite
This will be my testing static site for our channel


dism /image:C:\ /cleanup-image /restorehealth /source:E:\sources\install.esd /limitaccess
DISM /Online /Cleanup-Image /RestoreHealth /Source:D:\sources\install.wim /LimitAccess
DISM /Apply-Image /ImageFile:F:\Win10_22H2_English_x64v1.iso /Index:1 /ApplyDir:C:\ISO
xcopy C:\Users\Kidane\Documents D:\Backup\Documents /E /H /C /I
wimlib-imagex split install.wim destination/source/instal.swm
rmdir /s /q E:\backup\AppData
diskpart
list disk
select disk 0
clean
convert gpt
exit


Code
OOBE\BYPASSNRO
Press Enter

The system reboots

Choose I don’t have internet

Finish setup offline

Install the Wi‑Fi driver later from inside Windows

