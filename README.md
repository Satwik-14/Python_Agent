# Work Status Agent
Work Status Agent is a Python application designed to monitor user activity, detect timezone changes, and monitor system status including battery level and internet connectivity. The application runs multiple monitoring tasks concurrently using threads.


## Features

#### Activity Monitoring:
* Tracks mouse and keyboard activity and tells if the user is active or inactive.
* Captures screenshots at regular intervals and stores it in the screenshots folder.

#### Timezone Monitoring:
* Monitors changes in the system timezone.
* Logs the detected timezone changes with timestamps.

#### System Status Monitoring:
* Checks for low battery levels and logs warnings.
* Monitors internet connectivity and logs connection/disconnection events.
