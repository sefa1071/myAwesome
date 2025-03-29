# Awesome CETP Learining Resources
![](https://static.wixstatic.com/media/98ad8e_09cc2d856494484c95461004eb38308e~mv2.png/v1/crop/x_3,y_0,w_1055,h_814/fill/w_610,h_471,al_c,q_85,usm_0.66_1.00_0.01,enc_avif,quality_auto/CETP.png)
## Cource Lab
![lab](https://static.wixstatic.com/media/98ad8e_8a0932f82501450caa6e4ba95de262df~mv2.png/v1/fill/w_917,h_384,al_c,q_85,usm_0.66_1.00_0.01,enc_avif,quality_auto/evasion%20lab%20diagram.png)
## Cource Syllbus
### Windows Internals
- Understand User-mode and Kernel-mode presentation of a process.
- Understand PE structure.
- Understand User-mode and Kernel-mode separation and execution flow using IDA Pro and WinDbg.

### EDR Internals
- Reversing EDR's internals using IDA Pro and WinDbg.
- Understand how EDR's telemetries are collected.

### Static Detection Bypass
- Using obfuscators & code virtualization to protect code against:
  - Static detection
  - Analyzing
  - Reverse-engineering

### Initial Access Techniques
- Signed ClickOnce Backdooring.

### Introduction to Windows Kernel Programming
- Understand how a process can communicate with a driver from userland.
- Create a user-mode code that sends and receives data from a kernel driver.

### Road to Kernel
- Reversing R/W kernel primitive vulnerable drivers and exploiting them to:
  - Load unsigned code into the kernel using IDA Pro.
- Learn methodologies to:
  - Hunt for leaked certificates.
  - Leverage outdated certificates to sign a rootkit.

### EDR Killing
- Learn methodologies to hunt for signed killer drivers.
- Reverse multiple killer drivers using IDA Pro.
- Learn how to exploit killer drivers to kill EDR processes.
- Write a custom killer rootkit.

### Attack on EDR's Kernel Callbacks
- Understanding & reversing kernel callbacks using WinDbg and IDA Pro.
- Understanding:
  - What telemetry kernel callbacks collect.
  - The purpose of collected telemetry.
- Writing a user-mode code and kernel driver toolkit to:
  - Enumerate and remove kernel callbacks.
- Exploiting R/W kernel primitive vulnerable drivers to enumerate and remove kernel callbacks.

### Attack on ETW
- Understanding & reversing ETW internals.
- Disabling ETW providers.

### PP & PPL Bypass
- Understanding & reversing process protection levels using WinDbg.
- Exploiting R/W kernel primitive vulnerable drivers to manage a process's protection level.
- Writing a user-mode code and kernel driver toolkit to:
  - Manage process protection levels.
- Dumping LSA-protected LSASS.

### Extra Offensive Rootkit Techniques
- Hiding:
  - Processes/drivers from analysts and user-mode processes.
  - Kernel functions from the Import Address Table.
- Learning efficient dynamic kernel offset resolution.

### C2 Traffic Tunneling
- Writing a data exfiltration tool that hides malicious traffic inside multiple trusted APIs, such as Slack.

### Block EDR's Traffic
- Discovering and coding multiple ways to prevent EDR processes from sending alerts to SOC management consoles.

### ASR Rules Bypass
- Reversing ASR rules and bypassing them.

### Attack on Sysmon
- Understanding & reversing Sysmon.
- Discovering and coding multiple ways to blind Sysmon.

### UAC Bypass
- Discovering multiple ways to bypass Windows User Account Control.

### Anti-Analysis
- Discovering and coding multiple techniques for:
  - Anti-Debugging
  - Anti-Disassembling
  - Anti-Virtualization
  - Anti-Sandbox
  - Anti-Code Injection
