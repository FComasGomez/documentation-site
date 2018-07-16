{
	"title": "GraphQL Schema breaking changes",
	"pagetitle": "GraphQL Schema breaking changes",
	"description": "Changes history of deprecated notes previously announced",
	"weight": 5,
	"icon": "fa-eraser",
	"alwaysopen": false,
	"tags": [
		"reaking-changes"
	],
	"hideGithubLink": true
}

{{% alert theme="info" %}}Changes history of deprecated notes previously announced{{% /alert %}}

### Unreleased
{{% release-notes-container type="u"%}}
- Unreleased removal of `distribute` from `AddOns`. Reason: You can find it in distribution AddOn.  .
- Unreleased removal of `hotel` from `Booking`. Reason: You can find it in query at HotelX.  .
- Unreleased removal of `hotel` from `Quote`. Reason: You can find it in query at HotelX.  .
- Unreleased removal of `hotel` from `Search`. Reason: You can find it in query at HotelX.  .
- Unreleased removal of `useContext` from `HotelSettingsInput`. Reason: Redundant..  .
- Unreleased removal of `connectUser` from `HotelSettingsInput`. Reason: Redundant..  .
- Unreleased removal of `organization` from `PaymentXBookingInfoFilterInput`. Reason: Please use PaymentXBookingInfoCriteriaInput.  .
- Unreleased removal of `pointOfSaleCode` from `PaymentXBookingInfoFilterInput`. Reason: Please use PaymentXBookingInfoCriteriaInput.  .
- Unreleased removal of `bookingReference` from `PaymentXBookingInfoFilterInput`. Reason: Please use PaymentXBookingInfoCriteriaInput.  .
{{% / release-notes-container %}}
### 2018-08-03
{{% release-notes-container type="d"%}}
- Deprecated `organization` from `PaymentXBookingInfoFilterInput`. Reason: Please use PaymentXBookingInfoCriteriaInput. Expected deprecation on 2018-08-03 .
- Deprecated `pointOfSaleCode` from `PaymentXBookingInfoFilterInput`. Reason: Please use PaymentXBookingInfoCriteriaInput. Expected deprecation on 2018-08-03 .
- Deprecated `bookingReference` from `PaymentXBookingInfoFilterInput`. Reason: Please use PaymentXBookingInfoCriteriaInput. Expected deprecation on 2018-08-03 .
- Deprecated `undefined` from `undefined`. Reason: undefined. Expected deprecation on undefined .
{{% / release-notes-container %}}
### 2018-07-09
{{% release-notes-container type="r"%}}
- Removed `quote` from `Query`. Reason: You can find it in query at HotelX. Deprecated on 2017-11-21 .
- Removed `deleteDefaultSettings` from `Mutation`. Reason: You can find it in query at Admin. Deprecated on 2017-11-21 .
- Removed `updateDefaultSettings` from `Mutation`. Reason: You can find it in query at Admin. Deprecated on 2017-11-21 .
- Removed `createDefaultSettings` from `Mutation`. Reason: You can find it in query at Admin. Deprecated on 2017-11-21 .
- Removed `loadFile` from `Mutation`. Reason: You can find it in query at Admin. Deprecated on 2017-11-21 .
- Removed `hotelCancel` from `Mutation`. Reason: You can find it in query at HotelX. Deprecated on 2017-11-21 .
- Removed `hotelBook` from `Mutation`. Reason: You can find it in query at HotelX. Deprecated on 2017-11-21 .
- Removed `search` from `Query`. Reason: You can find it in query at HotelX. Deprecated on 2017-11-21 .
- Removed `booking` from `Query`. Reason: You can find it in query at HotelX. Deprecated on 2017-11-21 .
- Removed `defaultSettings` from `Query`. Reason: You can find it in query at HotelX. Deprecated on 2017-11-21 .
- Removed `mapping` from `Query`. Reason: You can find it in query at HotelX. Deprecated on 2017-11-21 .
{{% / release-notes-container %}}
### 2018-05-21
{{% release-notes-container type="d"%}}
- Deprecated `distribute` from `AddOns`. Reason: You can find it in distribution AddOn. Expected deprecation on 2018-05-21 .
- Deprecated `undefined` from `undefined`. Reason: undefined. Expected deprecation on undefined .
{{% / release-notes-container %}}
### 2018-03-19
{{% release-notes-container type="d"%}}
- Deprecated `connectUser` from `HotelSettingsInput`. Reason: Redundant.. Expected deprecation on 2018-03-19 .
- Deprecated `undefined` from `undefined`. Reason: undefined. Expected deprecation on undefined .
{{% / release-notes-container %}}
### 2017-12-12
{{% release-notes-container type="d"%}}
- Deprecated `useContext` from `HotelSettingsInput`. Reason: Redundant.. Expected deprecation on 2017-12-12 .
- Deprecated `undefined` from `undefined`. Reason: undefined. Expected deprecation on undefined .
{{% / release-notes-container %}}
### 2017-11-21
{{% release-notes-container type="d"%}}
- Deprecated `quote` from `Query`. Reason: You can find it in query at HotelX. Finally removed on 2018-07-09 .
- Deprecated `deleteDefaultSettings` from `Mutation`. Reason: You can find it in query at Admin. Finally removed on 2018-07-09 .
- Deprecated `updateDefaultSettings` from `Mutation`. Reason: You can find it in query at Admin. Finally removed on 2018-07-09 .
- Deprecated `createDefaultSettings` from `Mutation`. Reason: You can find it in query at Admin. Finally removed on 2018-07-09 .
- Deprecated `loadFile` from `Mutation`. Reason: You can find it in query at Admin. Finally removed on 2018-07-09 .
- Deprecated `hotelCancel` from `Mutation`. Reason: You can find it in query at HotelX. Finally removed on 2018-07-09 .
- Deprecated `hotelBook` from `Mutation`. Reason: You can find it in query at HotelX. Finally removed on 2018-07-09 .
- Deprecated `search` from `Query`. Reason: You can find it in query at HotelX. Finally removed on 2018-07-09 .
- Deprecated `booking` from `Query`. Reason: You can find it in query at HotelX. Finally removed on 2018-07-09 .
- Deprecated `defaultSettings` from `Query`. Reason: You can find it in query at HotelX. Finally removed on 2018-07-09 .
- Deprecated `mapping` from `Query`. Reason: You can find it in query at HotelX. Finally removed on 2018-07-09 .
- Deprecated `hotel` from `Booking`. Reason: You can find it in query at HotelX. Expected deprecation on 2017-11-21 .
- Deprecated `hotel` from `Quote`. Reason: You can find it in query at HotelX. Expected deprecation on 2017-11-21 .
- Deprecated `hotel` from `Search`. Reason: You can find it in query at HotelX. Expected deprecation on 2017-11-21 .
- Deprecated `undefined` from `undefined`. Reason: undefined. Expected deprecation on undefined .
{{% / release-notes-container %}}