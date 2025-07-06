## Windows Event Log 101  - BlueTeam.Id
![blueteam](https://github.com/user-attachments/assets/d93f9c52-5b4f-4d14-9d22-b69c0af8e805)

## 3.Is windows event log format in plain text format?
 answer: **False**
 
 **Explanation:**
The **Windows Event Logs** format is **not** stored in plain text. They are stored in a **special binary format** with the **`.evtx`** file extension that is used by the Windows Event Viewer.

To read them, you need:

* **Event Viewer** on Windows
* Tools such as `wevtutil`, PowerShell, or a third-party program (e.g. Log Parser, EventLog Explorer)
* Or you can export them to a readable format such as `.xml` or `.txt`, but they are not actually plain text.

So, they are **not** plain text by default.


  ## 7.Logon type - Network
![Untitled design](https://github.com/user-attachments/assets/c577b2d5-ed0d-4af4-a17b-b16c9bcb2398)
### answer : 2
