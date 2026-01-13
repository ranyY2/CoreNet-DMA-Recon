# CoreNet-DMA-Recon
Advanced DMA Cheat Detection Tool | Browser History

Run these commands once in PowerShell:
```powershell
Set-ExecutionPolicy RemoteSigned -Scope CurrentUser
Install-PackageProvider -Name NuGet -Force
Install-Module -Name PSSQLite -Scope CurrentUser -Force


Scan Instructions
Close all browsers (Chrome, Firefox, Edge)

Run as Administrator: Right-click CoreNet_DMA_Domain_scan.exe → "Run as administrator"

Wait until "SCAN REPORT" appears

Review hits (Websites, Files, Processes)

Results
dma_detections_log.json - Open in same folder or import to Core.net Dashboard

Console output shows real-time detections
