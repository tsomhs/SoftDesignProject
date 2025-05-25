# SoftDesignProject

![](StatechartDiagram1.jpg)
 
## Assumptions

1. Biometrics authentication is only meant for the supervisor.
2. There is an idle state which all the users can maintain and acts as the center(main component) of the statechart diagram.
3. The transition without text/data on them suppose that the user tapped on a button on the menu to get in that spot.
4. 2FA is required for all; biometric is an extra layer for supervisors only.
5. Supervisor is a unique user (one in the system).
6. If a user closes the app directly, it transitions to the App is closed state immediately.
7. Files and reports are role-dependent, ensuring access control and data integrity.