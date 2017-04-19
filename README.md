![Terso Solutions Logo](https://cdn.tersosolutions.com/github/TersoHorizontal_BlackGreen.png "Terso Solutions, Inc.")

## Jetstream SDK Windows Service
[Jetstream Documentation - https://jetstreamrfid.com/documentation/applicationapi/1.5](https://jetstreamrfid.com/documentation/applicationapi/1.5)

[Jetstream Tools - https://jetstreamrfid.com/tools](https://jetstreamrfid.com/tools)

### Microsoft .NET Framework 4.5
This Windows service implementation includes the ability to leverage the [Jetstream SDK](https://github.com/tersosolutions/JetstreamSDK-.NET) to get and remove events from Jetstream. Use those events to process inventory transactions in your application.

### Windows Service
1. Git this repository.
2. Build the solution.
3. Override the public virtuals that exist in the service.
4. Process your inventory changes with the aggregate events.
5. See your device is online with heartbeat events.
6. Double-check your inventory with object events (baseline scans).

### Change History
* v1.5.2 - April 19, 2017 - Update Jetstream SDK to v1.5.2
* v1.5 - October 14, 2015 - Added to Github

### License
Copyright 2016 Terso Solutions, Inc.

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at:
[http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0).

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
