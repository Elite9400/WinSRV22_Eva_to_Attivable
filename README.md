# Windows Server 2022 Evaluation to Standard

- Open the PowerShell as Administrator.
- STANDARD:
  dism /online /set-edition:serverStandard /productkey:{key} /accepteula
- DATACENTER:
  dism /online /set-edition:serverDatacenter /productkey:{key} /accepteula

# Windows Server Keys - Generic Volume License Keys (GVLK)

- Windows Server 2022 Datacenter	                WX4NM-KYWYW-QJJR4-XV3QB-6VM33
- Windows Server 2022 Datacenter Azure Edition	  NTBV8-9K7Q8-V27C6-M2BTV-KHMXV
- Windows Server 2022 Standard	                  VDYBN-27WPP-V4HQT-9VMD4-VMK7H

# PowerShell
- dism /online /set-edition:serverStandard /productkey:VDYBN-27WPP-V4HQT-9VMD4-VMK7H /accepteula
- dism /online /set-edition:serverDatacenter /productkey:WX4NM-KYWYW-QJJR4-XV3QB-6VM33 /accepteula

# Attivazione Prodotto (Versione Datacenter)
- slmgr.vbs /ipk WX4NM-KYWYW-QJJR4-XV3QB-6VM33
- slmgr.vbs /skms {ip}
- slmgr.vbs /ato
