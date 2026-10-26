Prototype Test Cases

Test| Input or Condition| Expected Result
1| Normal simulated glucose reading| Reading is displayed
2| Simulated low glucose reading| Low-glucose alert is triggered
3| Simulated high glucose reading| High-glucose alert is triggered
4| Sensor disconnection| Sensor fault is reported
5| Communication failure| Communication fault is reported
6| Unsafe delivery command| Independent safety check blocks the command
7| Motor fault simulation| Motor fault alert is triggered

Test Status

These are planned prototype tests. Results must be recorded after the tests are actually performed. No test is claimed to have passed yet.

Safety

All initial tests should use simulated inputs and a safe bench setup, without delivering insulin to a person.
