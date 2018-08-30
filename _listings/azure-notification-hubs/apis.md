---
name: Azure Notification Hubs
x-slug: azure-notification-hubs
description: Azure Notification Hubs provide an easy-to-use, multi-platform, scaled-out
  push engine. With a single cross-platform API call, you can easily send targeted
  and personalized push notifications to any mobile platform from any cloud or on-premises
  backend.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-notification-hubs.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Azure Notification Hubs
created: "2018-08-29"
modified: "2018-08-29"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/apis.md
specificationVersion: "0.14"
apis:
- name: NotificationHubsManagementClient - Namespaces Check Availability
  x-api-slug: subscriptionssubscriptionidprovidersmicrosoft-notificationhubschecknamespaceavailability-post
  description: Checks the availability of the given service namespace across all Azure
    subscriptions. This is useful because the domain name is created based on the
    service namespace name.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-notification-hubs.png
  humanURL: https://docs.microsoft.com/en-us/azure/notification-hubs/
  baseURL: ://management.azure.com//
  tags: Notifications, Microsoft, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidprovidersmicrosoft-notificationhubschecknamespaceavailability-post-openapi.md
- name: NotificationHubsManagementClient - Namespaces Create Or Update
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-notificationhubsnamespacesnamespacename-put
  description: Creates/Updates a service namespace. Once created, this namespace's
    resource manifest is immutable. This operation is idempotent.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-notification-hubs.png
  humanURL: https://docs.microsoft.com/en-us/azure/notification-hubs/
  baseURL: ://management.azure.com//
  tags: Notifications, Microsoft, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-notificationhubsnamespacesnamespacename-put-openapi.md
- name: NotificationHubsManagementClient - Namespaces Patch
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-notificationhubsnamespacesnamespacename-patch
  description: Patches the existing namespace
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-notification-hubs.png
  humanURL: https://docs.microsoft.com/en-us/azure/notification-hubs/
  baseURL: ://management.azure.com//
  tags: Notifications, Microsoft, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-notificationhubsnamespacesnamespacename-patch-openapi.md
- name: NotificationHubsManagementClient - Namespaces Delete
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-notificationhubsnamespacesnamespacename-delete
  description: Deletes an existing namespace. This operation also removes all associated
    notificationHubs under the namespace.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-notification-hubs.png
  humanURL: https://docs.microsoft.com/en-us/azure/notification-hubs/
  baseURL: ://management.azure.com//
  tags: Notifications, Microsoft, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-notificationhubsnamespacesnamespacename-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-notificationhubsnamespacesnamespacename-delete-openapi.md
- name: NotificationHubsManagementClient - Namespaces Get
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-notificationhubsnamespacesnamespacename-get
  description: Returns the description for the specified namespace.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-notification-hubs.png
  humanURL: https://docs.microsoft.com/en-us/azure/notification-hubs/
  baseURL: ://management.azure.com//
  tags: Notifications, Microsoft, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-notificationhubsnamespacesnamespacename-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-notificationhubsnamespacesnamespacename-get-openapi.md
- name: NotificationHubsManagementClient - Namespaces Create Or Update Authorization
    Rule
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-notificationhubsnamespacesnamespacenameauthorizationrulesauthorizationrulename-put
  description: Creates an authorization rule for a namespace
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-notification-hubs.png
  humanURL: https://docs.microsoft.com/en-us/azure/notification-hubs/
  baseURL: ://management.azure.com//
  tags: Notifications, Microsoft, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-notificationhubsnamespacesnamespacenameauthorizationrulesauthorizationrulename-put-openapi.md
- name: NotificationHubsManagementClient - Namespaces Delete Authorization Rule
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-notificationhubsnamespacesnamespacenameauthorizationrulesauthorizationrulename-delete
  description: Deletes a namespace authorization rule
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-notification-hubs.png
  humanURL: https://docs.microsoft.com/en-us/azure/notification-hubs/
  baseURL: ://management.azure.com//
  tags: Notifications, Microsoft, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-notificationhubsnamespacesnamespacenameauthorizationrulesauthorizationrulename-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-notificationhubsnamespacesnamespacenameauthorizationrulesauthorizationrulename-delete-openapi.md
- name: NotificationHubsManagementClient - Namespaces Get Authorization Rule
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-notificationhubsnamespacesnamespacenameauthorizationrulesauthorizationrulename-get
  description: Gets an authorization rule for a namespace by name.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-notification-hubs.png
  humanURL: https://docs.microsoft.com/en-us/azure/notification-hubs/
  baseURL: ://management.azure.com//
  tags: Notifications, Microsoft, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-notificationhubsnamespacesnamespacenameauthorizationrulesauthorizationrulename-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-notificationhubsnamespacesnamespacenameauthorizationrulesauthorizationrulename-get-openapi.md
- name: NotificationHubsManagementClient - Namespaces List
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-notificationhubsnamespaces-get
  description: Lists the available namespaces within a resourceGroup.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-notification-hubs.png
  humanURL: https://docs.microsoft.com/en-us/azure/notification-hubs/
  baseURL: ://management.azure.com//
  tags: Notifications, Microsoft, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-notificationhubsnamespaces-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-notificationhubsnamespaces-get-openapi.md
- name: NotificationHubsManagementClient - Namespaces List All
  x-api-slug: subscriptionssubscriptionidprovidersmicrosoft-notificationhubsnamespaces-get
  description: Lists all the available namespaces within the subscription irrespective
    of the resourceGroups.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-notification-hubs.png
  humanURL: https://docs.microsoft.com/en-us/azure/notification-hubs/
  baseURL: ://management.azure.com//
  tags: Notifications, Microsoft, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidprovidersmicrosoft-notificationhubsnamespaces-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidprovidersmicrosoft-notificationhubsnamespaces-get-openapi.md
- name: NotificationHubsManagementClient - Namespaces List Authorization Rules
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-notificationhubsnamespacesnamespacenameauthorizationrules-get
  description: Gets the authorization rules for a namespace.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-notification-hubs.png
  humanURL: https://docs.microsoft.com/en-us/azure/notification-hubs/
  baseURL: ://management.azure.com//
  tags: Notifications, Microsoft, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-notificationhubsnamespacesnamespacenameauthorizationrules-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-notificationhubsnamespacesnamespacenameauthorizationrules-get-openapi.md
- name: NotificationHubsManagementClient - Namespaces List Keys
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-notificationhubsnamespacesnamespacenameauthorizationrulesauthorizationrulenamelistkeys-post
  description: Gets the Primary and Secondary ConnectionStrings to the namespace
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-notification-hubs.png
  humanURL: https://docs.microsoft.com/en-us/azure/notification-hubs/
  baseURL: ://management.azure.com//
  tags: Notifications, Microsoft, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-notificationhubsnamespacesnamespacenameauthorizationrulesauthorizationrulenamelistkeys-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-notificationhubsnamespacesnamespacenameauthorizationrulesauthorizationrulenamelistkeys-post-openapi.md
- name: NotificationHubsManagementClient - Namespaces Regenerate Keys
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-notificationhubsnamespacesnamespacenameauthorizationrulesauthorizationrulenameregeneratekeys-post
  description: Regenerates the Primary/Secondary Keys to the Namespace Authorization
    Rule
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-notification-hubs.png
  humanURL: https://docs.microsoft.com/en-us/azure/notification-hubs/
  baseURL: ://management.azure.com//
  tags: Notifications, Microsoft, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-notificationhubsnamespacesnamespacenameauthorizationrulesauthorizationrulenameregeneratekeys-post-openapi.md
- name: NotificationHubsManagementClient - Notification Hubs Check Availability
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-notificationhubsnamespacesnamespacenamechecknotificationhubavailability-post
  description: Checks the availability of the given notificationHub in a namespace.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-notification-hubs.png
  humanURL: https://docs.microsoft.com/en-us/azure/notification-hubs/
  baseURL: ://management.azure.com//
  tags: Notifications, Microsoft, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-notificationhubsnamespacesnamespacenamechecknotificationhubavailability-post-openapi.md
- name: NotificationHubsManagementClient - Notification Hubs Create Or Update
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-notificationhubsnamespacesnamespacenamenotificationhubsnotificationhubname-put
  description: Creates/Update a NotificationHub in a namespace.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-notification-hubs.png
  humanURL: https://docs.microsoft.com/en-us/azure/notification-hubs/
  baseURL: ://management.azure.com//
  tags: Notifications, Microsoft, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-notificationhubsnamespacesnamespacenamenotificationhubsnotificationhubname-put-openapi.md
- name: NotificationHubsManagementClient - Notification Hubs Delete
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-notificationhubsnamespacesnamespacenamenotificationhubsnotificationhubname-delete
  description: Deletes a notification hub associated with a namespace.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-notification-hubs.png
  humanURL: https://docs.microsoft.com/en-us/azure/notification-hubs/
  baseURL: ://management.azure.com//
  tags: Notifications, Microsoft, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-notificationhubsnamespacesnamespacenamenotificationhubsnotificationhubname-delete-openapi.md
- name: NotificationHubsManagementClient - Notification Hubs Get
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-notificationhubsnamespacesnamespacenamenotificationhubsnotificationhubname-get
  description: Lists the notification hubs associated with a namespace.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-notification-hubs.png
  humanURL: https://docs.microsoft.com/en-us/azure/notification-hubs/
  baseURL: ://management.azure.com//
  tags: Notifications, Microsoft, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-notificationhubsnamespacesnamespacenamenotificationhubsnotificationhubname-get-openapi.md
- name: NotificationHubsManagementClient - Notification Hubs Create Or Update Authorization
    Rule
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-notificationhubsnamespacesnamespacenamenotificationhubsnotificationhubnameauthorizationrulesauthorizationrulename-put
  description: Creates/Updates an authorization rule for a NotificationHub
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-notification-hubs.png
  humanURL: https://docs.microsoft.com/en-us/azure/notification-hubs/
  baseURL: ://management.azure.com//
  tags: Notifications, Microsoft, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-notificationhubsnamespacesnamespacenamenotificationhubsnotificationhubnameauthorizationrulesauthorizationrulename-put-openapi.md
- name: NotificationHubsManagementClient - Notification Hubs Delete Authorization
    Rule
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-notificationhubsnamespacesnamespacenamenotificationhubsnotificationhubnameauthorizationrulesauthorizationrulename-delete
  description: Deletes a notificationHub authorization rule
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-notification-hubs.png
  humanURL: https://docs.microsoft.com/en-us/azure/notification-hubs/
  baseURL: ://management.azure.com//
  tags: Notifications, Microsoft, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-notificationhubsnamespacesnamespacenamenotificationhubsnotificationhubnameauthorizationrulesauthorizationrulename-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-notificationhubsnamespacesnamespacenamenotificationhubsnotificationhubnameauthorizationrulesauthorizationrulename-delete-openapi.md
- name: NotificationHubsManagementClient - Notification Hubs Get Authorization Rule
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-notificationhubsnamespacesnamespacenamenotificationhubsnotificationhubnameauthorizationrulesauthorizationrulename-get
  description: Gets an authorization rule for a NotificationHub by name.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-notification-hubs.png
  humanURL: https://docs.microsoft.com/en-us/azure/notification-hubs/
  baseURL: ://management.azure.com//
  tags: Notifications, Microsoft, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-notificationhubsnamespacesnamespacenamenotificationhubsnotificationhubnameauthorizationrulesauthorizationrulename-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-notificationhubsnamespacesnamespacenamenotificationhubsnotificationhubnameauthorizationrulesauthorizationrulename-get-openapi.md
- name: NotificationHubsManagementClient - Notification Hubs List
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-notificationhubsnamespacesnamespacenamenotificationhubs-get
  description: Lists the notification hubs associated with a namespace.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-notification-hubs.png
  humanURL: https://docs.microsoft.com/en-us/azure/notification-hubs/
  baseURL: ://management.azure.com//
  tags: Notifications, Microsoft, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-notificationhubsnamespacesnamespacenamenotificationhubs-get-openapi.md
- name: NotificationHubsManagementClient - Notification Hubs List Authorization Rules
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-notificationhubsnamespacesnamespacenamenotificationhubsnotificationhubnameauthorizationrules-get
  description: Gets the authorization rules for a NotificationHub.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-notification-hubs.png
  humanURL: https://docs.microsoft.com/en-us/azure/notification-hubs/
  baseURL: ://management.azure.com//
  tags: Notifications, Microsoft, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-notificationhubsnamespacesnamespacenamenotificationhubsnotificationhubnameauthorizationrules-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-notificationhubsnamespacesnamespacenamenotificationhubsnotificationhubnameauthorizationrules-get-openapi.md
- name: NotificationHubsManagementClient - Notification Hubs List Keys
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-notificationhubsnamespacesnamespacenamenotificationhubsnotificationhubnameauthorizationrulesauthorizationrulenamelistkeys-post
  description: Gets the Primary and Secondary ConnectionStrings to the NotificationHub
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-notification-hubs.png
  humanURL: https://docs.microsoft.com/en-us/azure/notification-hubs/
  baseURL: ://management.azure.com//
  tags: Notifications, Microsoft, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-notificationhubsnamespacesnamespacenamenotificationhubsnotificationhubnameauthorizationrulesauthorizationrulenamelistkeys-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-notificationhubsnamespacesnamespacenamenotificationhubsnotificationhubnameauthorizationrulesauthorizationrulenamelistkeys-post-openapi.md
- name: NotificationHubsManagementClient - Notification Hubs Regenerate Keys
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-notificationhubsnamespacesnamespacenamenotificationhubsnotificationhubnameauthorizationrulesauthorizationrulenameregeneratekeys-post
  description: Regenerates the Primary/Secondary Keys to the NotificationHub Authorization
    Rule
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-notification-hubs.png
  humanURL: https://docs.microsoft.com/en-us/azure/notification-hubs/
  baseURL: ://management.azure.com//
  tags: Notifications, Microsoft, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-notificationhubsnamespacesnamespacenamenotificationhubsnotificationhubnameauthorizationrulesauthorizationrulenameregeneratekeys-post-openapi.md
- name: NotificationHubsManagementClient - Notification Hubs Get Pns Credentials
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-notificationhubsnamespacesnamespacenamenotificationhubsnotificationhubnamepnscredentials-post
  description: Lists the PNS Credentials associated with a notification hub .
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-notification-hubs.png
  humanURL: https://docs.microsoft.com/en-us/azure/notification-hubs/
  baseURL: ://management.azure.com//
  tags: Notifications, Microsoft, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-notificationhubsnamespacesnamespacenamenotificationhubsnotificationhubnamepnscredentials-post-openapi.md
x-common:
- type: x-api-gallery
  url: http://azure.monitor.api.gallery.streamdata.io
- type: x-api-stack
  url: http://azure.notification.hubs.stack.network
- type: x-documentation
  url: https://docs.microsoft.com/en-us/rest/api/notificationhubs
- type: x-website
  url: https://docs.microsoft.com/en-us/azure/notification-hubs/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---