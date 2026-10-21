# Requirements

## Functional requirements (what the system must DO)
1. The system shall measure water flow rate in the monitored pipe at regular intervals.
2. The system shall measure water pressure in the monitored pipe at regular intervals.
3. The system shall transmit sensor readings to a cloud platform over Wi-Fi.
4. The system shall display current sensor readings on a web dashboard.
5. The system shall flag a possible leak when readings go beyond a configurable threshold.
6. The system shall send an alert notification to maintenance staff when a possible leak is flagged.
7. The system shall store historical sensor readings for review.


## Non-functional requirements (how the system must PERFORM)
1. The system shall keep running for at least 24 hours continuously without manual restart.
2. The dashboard shall show a new reading withing 5 seconds of it being measured.
3. An alert shall be delivered within 30 seconds of a leak being flagged.
4. Only users who log in with a valid account shall be able to view the dashboard.
5. A new user shall be able to find the current pipe status within 3 clicks of logging in.


