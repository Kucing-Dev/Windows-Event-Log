## Windows Event Log 101  - BlueTeam.Id
![blueteam](https://github.com/user-attachments/assets/d93f9c52-5b4f-4d14-9d22-b69c0af8e805)
## 1.Event ID – An account was successfully logged on
![Screenshot 2025-07-09 094830](https://github.com/user-attachments/assets/6b50b8f2-e580-4d62-8fa0-b5a95d2b1c9f)

answer: **4624**

## 2.Event ID – An account failed to log on
answer: **4625**

## 3.Is windows event log format in plain text format?
 answer: **False**
 
 **Explanation:**
The **Windows Event Logs** format is **not** stored in plain text. They are stored in a **special binary format** with the **`.evtx`** file extension that is used by the Windows Event Viewer.

To read them, you need:

* **Event Viewer** on Windows
* Tools such as `wevtutil`, PowerShell, or a third-party program (e.g. Log Parser, EventLog Explorer)
* Or you can export them to a readable format such as `.xml` or `.txt`, but they are not actually plain text.

So, they are **not** plain text by default.

## 4.Default GUI application or Windows built-in application that can be used to view Windows event logs?
![Screenshot 2025-07-09 100633](https://github.com/user-attachments/assets/87d67f1f-28a5-4cc3-b924-cd8fcaaf0575)

answer: **Windows Event Viewer**

**Explanation:**

**Windows Event Viewer** is a default GUI application in Windows that is used to view and analyze **Windows Event Logs** such as:

* Application logs
* Security logs
* System logs
* Setup logs
* Forwarded events

You can open it by:

* Pressing `Win + R`, then type `eventvwr.msc` and press Enter.
* Or search for "Event Viewer" in the Start Menu.

 ## 5.Where is the local path windows event logs?
  answer: **C:\Windows\System32\winevt\Logs**

  Explanation:
This is the default location where Windows stores event log files in .evtx format.

Files in this folder include:

 - Security.evtx
 - System.evtx
 - Application.evtx
 - and other logs.

  ## 6.Event ID – 4625 – user is currently locked out
  answer: **0xC0000234**
 

  ## 7.Logon type - Network
### answer : 5

## 8.Who will NOT use windows event logs?
answer: **sales**
