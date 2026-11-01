# Fusion 360 model — R33, 55 mL

This is the 12-compartment R33 assembly with spring and chain joints. It is a digital concept; physical fit, dispensing and safety have not been validated.

The original Fusion 360 archive is split into two files due to the upload connection's size limit. Download both parts into the same folder, then join them in Windows PowerShell:

```powershell
cmd /c "copy /b SMC_12H_R33_55.f3d.part01+SMC_12H_R33_55.f3d.part02 SMC_12H_R33_55_SPRING_CHAIN_JOINTS_FINAL.f3d"
Get-FileHash -Algorithm SHA256 SMC_12H_R33_55_SPRING_CHAIN_JOINTS_FINAL.f3d
```

Expected size: 53745369 bytes. SHA-256: `363CEA90E00B554349E2030B3D0543B68BA510B5FD029989F92EB6529D4F9D28`. Open the restored .f3d archive in Autodesk Fusion.
