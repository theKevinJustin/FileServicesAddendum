# FileServicesAddendum
Microsoft.Windows.Server.FileServices.2016.Addendum.xml v1.0.3.5

Download [here](https://github.com/theKevinJustin/FileServicesAddendum/blob/main/Microsoft.Windows.Server.FileServices.2016.Addendum.xml)

Blog [https://kevinjustin.com/blog/2023/08/31/file-services-addendum/](https://kevinjustin.com/blog/2023/08/31/file-services-addendum/)

Microsoft Windows Server FileServices 2016 Addendum - 
'File Services addendum' adds replication health/backlog script, seed and group classes, replication/service monitors, recovery tasks, and overrides.

# Version History
```
v1.0.3.5  21 Dec 2023 Updated Rule closure logic, whitespace audit
v1.0.3.2  11 Dec 2023 Massive change in reset monitor logic, reducing runtime gt 92%, allows Age calculation before reset
v1.0.3.1  30 Nov 2023 Removed debug detail from DS/WA which showed in Health Explorer pane
v1.0.3.0  18 Jul 2023 Updates to report and closure DS timing
v1.0.2.8  12 Jul 2023 DFS Close and Report scripts updated, timing to spread out runtimes on SCOM MS
v1.0.2.6  28 Jun 2023 Close automation update DS and WA for comments, Recovery DisplayStrings
v1.0.2.1  15 Jul 2022 DFSR DFSN SmSvc recovery, various report updates
v1.0.1.7   2 Jun 2022 Updates for report, cleanup DS,WA,Tasks,timeouts
v1.0.1.6   9 May 2022 DFS recovery task
v1.0.1.5   6 Apr 2022 Updated 5002,5008 alert messages, reorganized displayStrings
v1.0.0.14 17 Mar 2022 Updated watcher script - DFS variables
v1.0.0.12 16 Mar 2022 Updated backlog datasources for null data scenario, 5002 and 5008 repeat event monitors
v1.0.0.9  16 Apr 2021 Updated report to remove auto-closed monitors, adjusted group regexv1
v1.0.0.7  29 Mar 2021 Updated Backlog and customer specific script alerting
v1.0.0.6  19 Mar 2021 Added DFS monitors, DFSR run as for backlog, included Replication group member monitor, updated scripts, task names
v1.0.0.0  23 Feb 2021 Created Addendum for DFSR monitoring
```
