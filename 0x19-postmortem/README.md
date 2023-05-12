On february 11th, 2023, from 2.00pm(UTC-5), Our companies web application had an outage that lasted for 4 hours, during which our users loosing acces to the site. Making it hard to clock in and out of work. The outage affected 100% of our users.

The outage was caused by a database connection issue which completely shut down the application.

Timeline:
. Our monitoring system detected the outage at 9:00Am, which alerted the   engineeering team.
. Our  engineers started investigating the issue.
. We attempted to restart our database nodes, but the issue still persists.
. ttempted to restart our database nodes, but the issue still persists.
. Upon further investigation, we discovered that recent network setup change caused the issue.
. We then escalated the matter to the networking team, who fixed the configuration issue. After the iisue was resolved we were able to restore the application by bringing the database nodes online.

Misleading debugging paths.

We initially had the impression that the issue was related to application code, and investigated the application code and server logs for some time, Then later on found out it was a database and  network configuration related issue.

Incident Escalation:
Initially, the engineering team was handling the issue but we later on escalated it to the networking team after identifying the real issue.

Resolution:
The issue was fixed by the networking team, which allowed us to bring the database nodes back and restore the application. We them perfomed a full system check to ensure everything was functioning optimally.

Corrective and Preventative measures.
To avoid similar problems in the future, we will take the following actions:

Enhance our monitoring system to detect and alert us promptly of database and networking issues.
Thoroughly review and test any network configuration changes before applying them to the production environment.
Create and implement a disaster recovery plan to recover quickly from similar problems in the future.
Boost redundancy in our database setup to minimize the impact of any future failures.
Conduct a post-mortem analysis with the whole team to identify any other areas for improvement.
