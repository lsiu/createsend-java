# createsend-java history

## v2.3.0 - 10 Oct, 2012   (2d5178e0)

* Added support for creating campaigns from templates.
* Added support for unsuppressing an email address.

## v2.2.0 - 17 Sep, 2012   (8f9b6c45)

* Added WorldviewURL field to com.createsend.models.campaigns.CampaignSummary.
* Introduced CampaignEventWithGeoData, CampaignOpen, and CampaignClick to
support correct retrieval of open and click data.

## v2.1.0 - 30 Aug, 2012   (67981b4d)

* Added support for basic / unlimited pricing.

## v2.0.0 - 23 Aug, 2012   (97c5d167)

* Removed com.createsend.Clients.setAccess() and removed all other parts of the
library which were allowing calls to the API in a deprecated manner.

## v1.2.0 - 22 Aug, 2012   (ef867e9b)

* Added support for UnsubscribeSetting field when creating, updating and
getting list details.
* Added support for AddUnsubscribesToSuppList and ScrubActiveWithSuppList
fields when updating a list.
* Added com.createsend.Clients.listsForEmailAddress() to support finding all
client lists to which a subscriber with a specific email address belongs.

## v1.1.1 - 23 Jul, 2012   (f777ad8a)

* Added support for specifying whether subscription-based autoresponders should
be restarted when adding or updating subscribers.

## v1.1.0 - 12 Jul, 2012   (2de00dee)

* Added support for team management.
* Added Travis CI support

## 1.0.5 - 31 Oct, 2011   (a9e26af9)

* Added support for new APIs.
* Fixed field names to be consistent with fields returned by API.

## 1.0.4 - 11 Sep, 2011   (98b6c2c9)

* Fixed #3. Removed TemplateScreenshotURL from the sample for creating
a template.

## 1.0.3 - 17 Aug, 2011   (384ed6cc)

* Initial release which supports current Campaign Monitor API.