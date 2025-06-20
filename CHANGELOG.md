## 0.2.0

##### ⚠️ Breaking
- Refactored `InAppMessage` constructor and all subclasses to take in an object as opposed to a large list of parameters.

##### Changed
- Updated the encoding of user ID to match the encoding of the Braze Web SDK v5.1.0+.

##### Fixed
- Fixed an issue where `setCustomUserLocationAttribute` did not set the custom location attribute properly.

## 0.1.1

##### Fixed
- Fixed an issue where In-App Message buttons were not stored in the same format as the web SDK.

## 0.1.0

- Initial release of the Braze JavaScript SDK. This release contains the following methods:
  - `addToCustomUserAttributeArray`
  - `addUserAlias`
  - `addUserToSubscriptionGroup`
  - `changeUser`
  - `deferInAppMessage`
  - `destroy`
  - `disableSdk`
  - `enableSdk`
  - `getDeferredInAppMessage`
  - `getDeviceId`
  - `getUserId`
  - `handleBrazeAction`
  - `incrementCustomUserAttribute`
  - `initialize`
  - `isDisabled`
  - `logCustomEvent`
  - `logGenericEvent`
  - `logInAppMessageButtonClick`
  - `logInAppMessageClick`
  - `logInAppMessageHtmlClick`
  - `logInAppMessageImpression`
  - `logPurchase`
  - `openSession`
  - `removeAllSubscriptions`
  - `removeFromCustomUserAttributeArray`
  - `removeSubscription`
  - `removeUserFromSubscriptionGroup`
  - `requestImmediateDataFlush`
  - `setCustomUserAttribute`
  - `setCustomUserLocationAttribute`
  - `setIdentifierToken`
  - `setLogger`
  - `setUserCountry`
  - `setUserDateOfBirth`
  - `setUserEmail`
  - `setUserEmailNotificationSubscriptionType`
  - `setUserFirstName`
  - `setUserHomeCity`
  - `setUserLanguage`
  - `setUserLastKnownLocation`
  - `setUserLastName`
  - `setUserPhoneNumber`
  - `setUserPushNotificationSubscriptionType`
  - `subscribeToInAppMessage`
  - `toggleLogging`
  - `wipeData`
