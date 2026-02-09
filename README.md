# SOC-detection-lab
Simulated SOC detection lab focused on Windows event logs, basic detection logic and incident response considerations.
## Lab scope
This lab focuses on simulating and detecting suspicious authentication-related activity on a Windows system. The primary objective is to observe how such activity appears in Windows event logs and to document basic detection logic a SOC analyst could use.
### Planned scenarios
-Multiple failed logon attempts within a short time window
-Suspicious Powershell execution 
-Basic post-detection response consideration
## Project structure
-'notes/'-environment setup, log analysis, tuning and response considerations
-'detections/'-detection logic and concepts
-'screenshots/'-evidence from simulated activity
## What i learned
This lab helped me understand how common authentication-related attacks appear in Windows security logs and how quickly failed logon events can accumulate. It also highlighted the importance of tuning detections to balance visibility and noise.
Working through the detection logic and response considerations reinforced how SOC analysts rely on context, thresholds and correlation rather than single events when making decisions.
