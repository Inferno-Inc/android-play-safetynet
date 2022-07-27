SafetyNet Samples
===================================

These samples demonstrate the end-to-end use of the SafetyNet API.
SafetyNet provides services for analyzing the configuration of a particular device to verify that it passes the Android compatibility test.

This repository consists of one client and two server components:

* [client/java](client/java/SafetyNetSample): Android sample app in Java, showing the use of Google Play Services for the SafetyNet API on a device.
* [server/java](server/java): Two samples, showing how to verify a SafetyNet API response on a server in Java, including offline and online via the Android Device Verification API.
* [server/csharp](server/csharp): Two samples, showing how to verify a SafetyNet API response on a server in C#, including offline and online via the Android Device Verification API.

For more details, see the documentation for each and component and the guide at https://developer.android.com/training/safetynet/index.html .


Running the Samples
------------------
* Build and run the [Android component](client/java/SafetyNetSample) of this sample from the  [client/java](client/java) directory.
* Retrieve a signed statement from the Android app and copy it to your machine. (You can use the "Share Result" option.)
* Build the [java server component](server/java) or [C# server component](server/csharp).
* Run the `OfflineVerify` or `OnlineVerify` checks and provide the signed statement from the app as input.


Support
-------

If you've found an error in this sample, please file an issue:
https://github.com/googlesamples/android-play-safetynet

Patches are encouraged, and may be submitted by forking this project and
submitting a pull request through GitHub. Please see CONTRIBUTING.md for more details.

License
-------

Copyright 2017 Google Inc.

Licensed to the Apache Software Foundation (ASF) under one or more contributor
license agreements.  See the NOTICE file distributed with this work for
additional information regarding copyright ownership.  The ASF licenses this
file to you under the Apache License, Version 2.0 (the "License"); you may not
use this file except in compliance with the License.  You may obtain a copy of
the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.  See the
License for the specific language governing permissions and limitations under
the License.
