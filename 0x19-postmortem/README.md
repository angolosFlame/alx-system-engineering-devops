### APPMAN application systems and Server infrastructure unreachable incident report

26th January, 2024

By Courage Tsikudo

Issue summary
For 1hr:35mins and exactly from 12:25 PM - 2:00 PM GMT users were unable to access the application websites, resulting in a loss of reporting time. Approximately 10% of users were affected. A recent construction works near APPMAN office’s fibre lines resulted in fibre cut that connects the office to the internet service provider and caused an outage to internet access by the applications servers.
  
Timeline:
12:25 PM - The issue was first detected when our monitoring system alerted the monitoring team indicating that 5 of our applications servers were down.
12:30 PM - The members of the engineering team were notified of the issue and investigation began.
12:35 PM - Initial investigations suggested that the issue was related to transmissions as ping requests were not reaching the last mile.
 At 12:40 PM - Further investigations revealed that the transmission system was up and running, however, the  issue was actually related to internet service as the network availability status went dark.
12:50 PM - The team discovered a fibre cut as connectivity was not being established using fibre connection but only through a redundant means of microwave.
Furthermore, at 1:00 PM - The incident escalated to the ISP provider.
1:10 PM - The team worked with the ISP provider to identify the source of the cut issue.
2:00 PM - The issue was resolved, and users were able to access the application websites again.

Root Cause and Resolution:
The root cause of the issue was a fibre cut hindering internet accessibility of the applications servers to run the websites. To resolve the issue, the engineering team worked with the ISP provider to identify and fix the fibrecut. The fix involved fibre splicing and dicing to remove the damaged part by the construction activity.
 
Corrective and Preventative Measures:
To prevent similar incidents from occurring in the future, the following steps were taken.
The engineering team in collaboration with the ISP installed a fibre line indicator for the construction workers to note the fibre route to avoid subsequent damage during construction works. 
A review of all application websites were accessed to ensure they were up and running. A microwave link was installed as a backup. 
Monitoring and alerting systems were improved to detect and respond to similar issues more quickly in the future. 
Developing and documenting incident response procedures to ensure that issues are escalated and resolved as quickly and efficiently as possible.

Sincerely,

Courage Tsikudo.

