Architecture Constraints
=======================
## UI Constraints
| Constraints | Explanation |
| --- | --- |
| Compatible Design | As the app will be deployed on both iOS and Android, the UI design needs to be compatible to both systems. This could be doe by both using Flutters tools for device-specific targetting and using common elements, like the bottom navigation bar. The UI needs to adhere both to Apples and Googles design guidelines. |
| Scaling | The UI needs to work on all device screen sizes. Therefore it is necessary to check if Flutters scaling works correctly on all implemented Elements (no yellow-black warnings) |

## Architecture Constraints
| Constraints | Explanation |
| --- | --- |
| Unified Backend | Due to the multiple deployments, the backend should be unified. Currently, the plan is to use Nine, which is developed by students and professors of FK09. |
| Different Platform Versions | As the App is targeted at different Operating systems, there will be a discrepancy about which features they support. Not all devices have the most current version. | 
