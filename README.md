# Integrity Box + TrickyStore + HMA-OSS Setup Guide (April 2026)

Follow the steps **in order**. Do not skip reboots where mentioned.

---

### 1. Download the following modules
 - [Zygisk-Next](https://github.com/Dr-TSNG/ZygiskNext/releases/latest)
 - [TEESimulator](https://github.com/JingMatrix/TEESimulator/releases/latest)
 - [Tricky Addon](https://github.com/KOWX712/Tricky-Addon-Update-Target-List/releases/latest)
 - [Integrity Box](https://github.com/MeowDump/Integrity-Box/releases/latest)
 - [Lsposed-Irene](https://t.me/LSPosed/307)
 - [HMA-OSS](https://github.com/frknkrc44/HMA-OSS/releases/latest)
 - [HMA-config](https://github.com/actuallyaryaman/PIF-Guide/releases/download/v1/HMA_Config.json)
   
> **⚠️ Do not install PIF**

---

### 2. Initial Installation

Install these modules in order, reboot as mentioned:
1. Zygisk Next.
   - Reboot (Set zygisk deny list policy as unmount only and enable the two check boxes)
1. TEESim  
2. Tricky-Addon-Update-Target-List
3. Lsposed-Irene
   - Reboot
4. Integrity Box
   - Reboot
   
   
### 3. Configure TrickyStore (via WebUI)
1. Select ALL → Deselect unnecessary apps
    
2. Keybox → Valid
    
3. SAVE
   
   
### 4. Run Integrity Box Action Button
Check your integrity status.
Voila!

### 5. Configure HMA-OSS
1. Open HMA-OSS
    
2. Restore the downloaded config
3. Open Manage Apps → Configure your Banking Apps
	-  In template config: Select All presets options, Select All templates, Select all settings template, Select All settings preset.

Everything should work as intended. 
