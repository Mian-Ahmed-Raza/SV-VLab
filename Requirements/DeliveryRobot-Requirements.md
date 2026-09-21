| Req ID | Description | Priority |
| :--- | :--- | :--- |
| **R1** | The system shall initialize in an idle state upon startup and wait for a delivery request. | High |
| **R2** | The robot shall begin navigating towards the destination immediately upon receiving a valid delivery request. | High |
| **R3** | The robot shall continuously monitor its surroundings for obstacles while in the navigating state. | High |
| **R4** | The robot shall temporarily suspend normal navigation and enter obstacle-avoidance mode upon detecting an obstacle. | High |
| **R5** | The robot shall resume normal navigation towards the destination once the obstacle has been successfully avoided. | High |
| **R6** | The robot shall initiate the package delivery process only upon successfully reaching the destination. | High |
| **R7** | The robot shall begin navigating back to the warehouse immediately after a package has been successfully delivered. | High |
| **R8** | The robot shall continuously monitor its battery level during navigation and immediately return to the warehouse if a critical battery level is detected. | High |
| **R9** | The robot shall revert to the idle state upon successfully reaching the warehouse. | High |
| **R10** | The system must prevent the robot from initiating the delivery process directly from the idle state or while in obstacle-avoidance mode. | High |
