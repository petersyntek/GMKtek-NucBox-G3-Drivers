This repository contains Windows 11 Drivers for GMKtek NuxBox G3 mini PC with Intel N100 CPU.

All drivers was downloaded from Microsoft Update Catalog by Device ID.

  NucBoxG3Driver.exe --> Self extracting archive created with WinRAR
  NucBoxG3Driver.zip --> Zip archive in case of Windows Defender quarantines the self extracing file.

  Package contents:
    Import.bat --> Run as Administrator from same path where Driver folder located to import drivers.
    ImportDrivers.ps1 --> Run from Administrator PowerShell from same path where Driver folder located to import drivers.
    Driver folder --> Contains device drivers

  Usage:
    1. Use NucBoxG3Driver.exe or NucBoxG3Driver.zip and extract contens to desired location.
    2/a. Right click on Import.bat and Run as Administrator
        OR
    2/b. Run a PowerShell with Administrator rights navigate to extracted folder and run ImportDrivers.ps1
    3. Script will go along on subfolders in Drivers and import drivers to Windows driver store.
    4. Reboot your NucBox (Sign in if required) and wait for Windows to install drivers for unknown devices. (You can track it in Device Manager)


  Drivers in the package:
    Intel(R) Ethernet Controller I226-V
    Intel(R) GNA Scoring Accelerator Module Driver
    Intel(R) HID Event Filter Driver Intel(R) Innovation Platform Framework
    Intel(R) Serial IO GPIO Host Controller
    Intel(R) Serial IO I2C
    Realtek 8852BE Wireless LAN WiFi 6 PCI-E NIC
    Realtek Bluetooth Adapter
