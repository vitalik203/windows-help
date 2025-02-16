Windows Activating

```plaintext
irm https://massgrave.dev/get | iex
```

---

Microsoft office 2021

**[setup.exe](https://mega.nz/file/oKNAzBJJ#frWcdklZd7_iPeSIYz2DH0Dme5R12kaCWFEJTSfDGRQ)**

**[configuration-Office2021Enterprise.xml](https://mega.nz/file/QT8TXR5C#OLUCD9HjCfluVRYXFrnCW2khs3uy1EKjqyTinEP-XR4)**

---

for 64bit

```plaintext
.\setup.exe /configure .\2021_64_office2021.xml
```

for 32bit

```plaintext
.\setup.exe /configure .\2021_32_office2021.xml
```

---

Return Microsoft Store

```plaintext
Get-AppxPackage -allusers Microsoft.WindowsStore | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register “$($_.InstallLocation)\AppXManifest.xml”}
```

---

Delete all default programs

```plaintext
Get-AppxPackage | Remove-AppxPackage
```

---

Hellzerg Optimizer

**[URL on file Hellzerg](https://github.com/hellzerg/optimizer/releases/download/16.7/Optimizer-16.7.exe)**

**[URL on GitHub Repository](https://github.com/hellzerg/optimizer)**
