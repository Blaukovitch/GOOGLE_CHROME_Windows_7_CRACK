# Google Chrome crack - Windows 7 
## 117.0.5938.63_x64
 Prevision: 114.0.5735.134 x64 , 114.0.5735.199 x86  
**SANDBOX is fixed but for hardware accelerated is still recommended:**  
`chrome.exe --no-sandbox`*  

![117_sandbox_improvements](images/Chrome_117_7_ea.png "Google Chrome Windows 7")
 
* see *!!!!!!!README_FIRST!.pdf*
![PH](images/process_hacker.png "Process Hacker Windows 7")  

## Intro  
Dirty corporations and Hindu-managers are trying to deprive the any users of all the benefits that were created by technically more advanced people than them. Windows 7 and Windows XP are the most successful and best technical creations of Microsoft ever.  
  
## How it's work?  
1) **Binary bithack (patch the assembly code):**  
* chrome.exe  
* *{ver.}*/chrome_elf.dll  
* *{ver.}*/chrome.dll  

2) **WinAPI LIFTING - Missing WINAPIs are deployed:**  
* API-MS-WIN-SHCORE-SCALING-L1-1-1  
* API-MS-WIN-POWER-BASE-L1-1-0  
* API-MS-WIN-CORE-WINRT-STRING-L1-1-0  
* API-MS-WIN-CORE-WINRT-L1-1-0  
* API-MS-WIN-CORE-WINRT-ERROR-L1-1-0  
3) **Bridged DLL (wrappers):** 
* kernel64.dll
* user64.dll
* userenx.dll
* xcryptprimitives.dll
* Xfplat.dll
* WinXttp.dll  
https://github.com/Blaukovitch/API-MS-WIN_XP 

⚠️ <u>WARNING:</u> Files not signed! I don't have a Google Inc. private key at the moment.

## How to install?
1) Download from release the merged pack; 
2) (for prevision **114 only**) Check you Microsoft Visual C++ Redistributable 2015-2019: https://learn.microsoft.com/en-US/cpp/windows/latest-supported-vc-redist?view=msvc-170 or 2015: https://www.microsoft.com/en-us/download/details.aspx?id=52685

## CVE-2023-4863 (WebP)
💊FIXED!

## WOW! WebGPU on Windows 7
May be unstable!  
Add to command line (with *--no-sandbox*) webgpu flag and **DirectX 3D 11** as webgpu render:  
`--enable-unsafe-webgpu --use-webgpu-adapter=d3d11`  
In launched Chrome 114 must set enabled those flags:  
`chrome://flags/#enable-webgpu-developer-features`  
`chrome://flags/#ignore-gpu-blocklist`  
and restart again.  


## Features table
| Critical | State |
| ------ | ------ |
| Stable | ✔️ |
| WinAPI lifting | approx. **90%** |
| Sandbox support (gpu) | ✔️/❌ | 
| DirectX Write render | ✔️ | 
| DXVAVDA | ✔️ | 
| WebGL1/2 | ✔️ | 
| WebGPU / DirectX 11 (gpu)| ❓ | 

**ELF (author of 80_PA SecuROM keygen), cracklab/exelab team, 2023**  
https://cracklab.team/index.php?threads/1037/
