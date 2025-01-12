---
layout: page
title: Publications
permalink: /pubs/
---

# ProcAID: Process Anomaly Based Intrusion Detection
I published my thesis that I completed at the George Washington University within the Masters of Science in Cybersecurity in Computer Science program in 2022. The abstract is below. 

<h3 style="text-align:center;">Abstract</h3>
Advanced Persistent Threats (APTs) prey on government entities and corporations via previously unknown attack vectors and complex techniques with overwhelming success. Though industry has attempted to engineer effective solutions to combat APTs, the solutions consistently lack the ability to quickly respond and react to novel threats. This research presents an effective, two-stage unsupervised graph anomaly-based detection algorithm called ProcAID that fills the gap of industry’s current detection and response capabilities. In general, ProcAID concentrates on anomalous process creation, inverse graph leadership, and inverse graph density to discover malicious processes on a single host. In the first stage, the solution detects anomalous host process creation events via unsupervised link prediction. In the second stage, ProcAID evaluates and assigns scores to a process based on its observed behavior. ProcAID was tested on a real-world enterprise dataset with known APT activity. This research proved proficient in distinguishing between malicious and benign host processes with options to expand to an enterprise implementation. ProcAID also out-performed other graph and machine learning anomaly detection algorithms in the detection of malicious activity. With already existing assets like Windows Security Event Logs, the implementation costs for ProcAID are minimal while the benefits are vast.  

The thesis is free to view and can be found [here](https://www.proquest.com/openview/e4ce5ff777fc5943a8b4624677b3cad1/1?pq-origsite=gscholar&cbl=18750&diss=y).   

My thesis defense presentation can be found [here](https://github.com/ajread4/procaid_presentations).   

The code for my thesis research is split based on stages. The first stage can be found [here](https://github.com/ajread4/procaid_stage1). The second stage can be found [here](https://github.com/ajread4/procaid_stage2).   