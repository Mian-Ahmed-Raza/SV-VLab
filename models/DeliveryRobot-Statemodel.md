| State ID | State Name | Description | Entry Condition | Exit Condition |
| :--- | :--- | :--- | :--- | :--- |
| **S1** | IDLE | The robot is waiting for a new delivery request. | System switched on OR Warehouse Reached. | Delivery Request Received. |
| **S2** | NAVIGATING | The robot is actively moving toward the destination. | Delivery Request Received OR Obstacle Avoided. | Destination Reached OR Obstacle Detected OR Critical Battery. |
| **S3** | AVOIDING_OBSTACLE | The robot is maneuvering around a detected obstacle. | Obstacle Detected. | Obstacle Avoided. |
| **S4** | DELIVERING | The robot has reached the destination and is dropping off the package. | Destination Reached. | Delivery Successful. |
| **S5** | RETURNING | The robot is heading back to the warehouse. | Delivery Successful OR Critical Battery. | Warehouse Reached. |
