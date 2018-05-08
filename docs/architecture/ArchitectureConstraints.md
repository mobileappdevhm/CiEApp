Architecture Constraints
=======================
## UI Constraints
| Constraints | Explanation |
| --- | --- |
| Compatible Design | As the app will be deployed on both iOS and Android, the UI design needs to be compatible to both systems. This could be doe by both using Flutters tools for device-specific targetting and using common elements, like the bottom navigation bar. The UI needs to adhere both to Apples and Googles design guidelines. |
| Scaling | The UI needs to work on all device screen sizes. Therefore it is necessary to check if Flutters scaling works correctly on all implemented Elements (no yellow-black warnings) |

## Technical Constraints
| Constraints | Explanation |
| --- | --- |
| Unified Backend | Due to the multiple deployments, the backend should be unified. Currently, the plan is to use Nine, which is developed by students and professors of FK09. Nine delivers its API data as JSON. |
| Different Platform Versions | As the App is targeted at different operating systems, there will be a discrepancy about which features they support. Not all devices have the most current version. | 
| Usage/Documentation of native methods | Due to Flutter not offering all features that programming nativly does, it might be neccessary to use native callback methods. Please make sure to document these thoroughly. |


## Organisational Constraints
| Constraints | Explanation |
| --- | --- |
| Naming Conventions | As the app is being developed over multiple teams, it is neccessary to be able to tell which team build the app. Therefore, app binaries and the app name that is visible in the system needs to include the team number. |
| Versioning Conventions | The versioning starts at 0.1. For every major update, which is also visible to the user, increment the number in front of the decimal point. For minor updates, incement the number behind the decimal point. |
| Package Names | Please make sure that the package name for Android applications includes the HMs URL, as per naming conventions. For Team 1, the package name would be: edu.hm.cs.mobileappdev.cieapp.team1 |
| Documentation | If a team decides to implement a feature which is not described or aviable in the unified backend, the team needs to make sure that the feature is documented in their teams wiki. | 

