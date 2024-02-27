![Logo](/.github/logo.png)

# Push-Amp-Plus (Discontinued)
This repository contains code to help you integrate the Push-Amp-Plus module of the MoEngage SDK.
Refer to the integration [documentation](https://developers.moengage.com/hc/en-us/articles/4403466194708-Configuring-Xiaomi-Push) for more details on how to use the helper methods.

## [DISCONTINUED]

### Important Notice: This module has been discontinued following Xiaomi's shutdown of MiPush services.
As a result of Xiaomi discontinuing the MiPush service, the Push-Amp-Plus module within the MoEngage SDK, which depended on this service, has also been discontinued and is no longer supported from MoEngage SDK version 13.00.00 and above.
Refer to the [help doc](https://help.moengage.com/hc/en-us/articles/23072207451540-Discontinuation-of-Mi-Push-Service) for more information

## Impact

The discontinuation of MiPush services means that this module will no longer be able to send push notifications to Xiaomi devices via MiPush. MoEngage Push via FCM will continue to function and Xiaomi devices will be targeted with FCM instead of MiPush.

## Removal of Push
We recommend all users to remove Push-Amp-Plus module & Mi Sdk dependency  from their projects.
Refer to the [documentation](https://developers.moengage.com/hc/en-us/articles/23074209085332-Steps-to-Remove-Mi-SDK-Dependency) for the necessary steps to remove Mi SDK dependency from your project.