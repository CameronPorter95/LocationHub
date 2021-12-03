# LocationHub
Track your precise location around your house in order to trigger home automations

### Basic Information
- Interface: SwiftUI
- Design Pattern: VIPER
- Minimum Deployment Version: iOS 15
- Supports MacOS: Yes
- Supports WatchOS: No
- Supports TVOS: No
- Has an AppClip: No

### Frameworks
- Nearby Interaction
- HomeKit

## How to Use
On first open the app will ask the user to first calibrate the device to their specific home.
This will require walking around the house, following the outline of the walls; the app requires a view of the layout of the home in order to have a blueprint to work off of.
Once the app has the layout of the house and the user has calibrated everywhere they wish to use LocationHub, they can then select areas of the blueprint as rooms and points of interest.
The user is asked to select distance to locations of interest before automations can be triggered.

Once distances have been set, the initial setup is complete and the user can start adding automations.
LocationHub will then trigger these automations when the user is within the distance to locations of interest previously set.
