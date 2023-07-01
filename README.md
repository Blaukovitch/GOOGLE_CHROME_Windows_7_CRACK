# Google Chrome crack - Windows 7  
## 114.0.5735.134 x64  
*Run from command line or .BAT/.LNK file:*  
`chrome.exe --no-sandbox`*  

![114](images/chrome114_main.png "Google Chrome Windows 7")
* **Yes, yes**, in this very first version (*114.0.5735.134*) **only by disabling the sandbox** - otherwise the browser will not start! **Yes**, it can be fixed - but it will take more time for a quality fix. **Yes**, perhaps hardware acceleration of **DirectX 11** after fixing the sandbox will also work perfrectly on the Windows 7.  
  
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
* msvproc  
https://github.com/Blaukovitch/API-MS-WIN_XP 

⚠️ <u>WARNING:</u> Files not signed! I don't have a Google Inc. private key at the moment.

## How to install?
1) Install the original Google Chrome browser (*114.0.5735.134 x64*) or download a already patched folder;  
2) Copy a new DLLs in to (*API-MS-... & msvproc*) into Google Chrome Install Directory;  
2a) Copy *API-MS-WIN-CORE-WINRT-ERROR-L1-1-0* in to **/{ver.}** (*114.0.5735.134*) subfolder for originial Google .exe *notification_helper.exe*;  
3) Replace the orignal DLLs (*chrome.exe, chrome_elf.dll, chrome.dll*);  
4) Run `chrome.exe --no-sandbox`\* or launch with *1NOSANDBOX!!!.bat*  

## Features table
| Critical | State |
| ------ | ------ |
| Stable | ✔️ |
| WinAPI lifting | approx. **90%** |
| Sandbox support (gpu) | ❌ | 
| DirectX Write render | ✔️ | 
| DXVAVDA | ✔️ | 
| WebGL / DirectX 11 (gpu)| ❓ | 

**ELF (author of 80_PA SecuROM keygen), cracklab/exelab team, 2023**  
https://cracklab.team/index.php?threads/1037/
