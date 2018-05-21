---
name: Azure Notification Hubs
x-slug: azure-notification-hubs
description: Azure Notification Hubs provide an easy-to-use, multi-platform, scaled-out
  push engine. With a single cross-platform API call, you can easily send targeted
  and personalized push notifications to any mobile platform from any cloud or on-premises
  backend.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-notification-hubs.png
x-kinRank: "10"
x-alexaRank: ""
tags: Azure Notification Hubs
created: "2018-05-21"
modified: "2018-05-21"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/apis.md
specificationVersion: "0.14"
apis:
- name: Azure Notification Hubs API Namespaces Check Availability
  x-api-slug: azure-notification-hubs-api
  description: Checks the availability of the given service namespace across all Azure
    subscriptions. This is useful because the domain name is created based on the
    service namespace name.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-notification-hubs.png
  humanURL: https://docs.microsoft.com/en-us/azure/notification-hubs/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/providers/Microsoft.NotificationHubs/checkNamespaceAvailability
  tags: Namespaces Availability
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidprovidersmicrosoftnotificationhubschecknamespaceavailability-post-openapi.md
- name: Azure Notification Hubs API Namespaces Create Or Update
  x-api-slug: azure-notification-hubs-api
  description: Creates/Updates a service namespace. Once created, this namespace's
    resource manifest is immutable. This operation is idempotent.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-notification-hubs.png
  humanURL: https://docs.microsoft.com/en-us/azure/notification-hubs/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.NotificationHubs/namespaces/{namespaceName}
  tags: Namespaces
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnotificationhubsnamespacesnamespacename-put-openapi.md
- name: Azure Notification Hubs API Namespaces Patch
  x-api-slug: azure-notification-hubs-api
  description: Patches the existing namespace
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-notification-hubs.png
  humanURL: https://docs.microsoft.com/en-us/azure/notification-hubs/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.NotificationHubs/namespaces/{namespaceName}
  tags: Namespaces
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnotificationhubsnamespacesnamespacename-patch-openapi.md
- name: Azure Notification Hubs API Namespaces Delete
  x-api-slug: azure-notification-hubs-api
  description: Deletes an existing namespace. This operation also removes all associated
    notificationHubs under the namespace.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-notification-hubs.png
  humanURL: https://docs.microsoft.com/en-us/azure/notification-hubs/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.NotificationHubs/namespaces/{namespaceName}
  tags: Namespaces
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnotificationhubsnamespacesnamespacename-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnotificationhubsnamespacesnamespacename-delete-openapi.md
- name: Azure Notification Hubs API Namespaces Get
  x-api-slug: azure-notification-hubs-api
  description: Returns the description for the specified namespace.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-notification-hubs.png
  humanURL: https://docs.microsoft.com/en-us/azure/notification-hubs/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.NotificationHubs/namespaces/{namespaceName}
  tags: Namespaces
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnotificationhubsnamespacesnamespacename-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnotificationhubsnamespacesnamespacename-get-openapi.md
- name: Azure Notification Hubs API Namespaces Create Or Update Authorization Rule
  x-api-slug: azure-notification-hubs-api
  description: Creates an authorization rule for a namespace
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-notification-hubs.png
  humanURL: https://docs.microsoft.com/en-us/azure/notification-hubs/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.NotificationHubs/namespaces/{namespaceName}/AuthorizationRules/{authorizationRuleName}
  tags: Namespaces Authorization Rule
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnotificationhubsnamespacesnamespacenameauthorizationrulesauthorizationrulename-put-openapi.md
- name: Azure Notification Hubs API Namespaces Delete Authorization Rule
  x-api-slug: azure-notification-hubs-api
  description: Deletes a namespace authorization rule
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-notification-hubs.png
  humanURL: https://docs.microsoft.com/en-us/azure/notification-hubs/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.NotificationHubs/namespaces/{namespaceName}/AuthorizationRules/{authorizationRuleName}
  tags: Namespaces Authorization Rule
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnotificationhubsnamespacesnamespacenameauthorizationrulesauthorizationrulename-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnotificationhubsnamespacesnamespacenameauthorizationrulesauthorizationrulename-delete-openapi.md
- name: Azure Notification Hubs API Namespaces Get Authorization Rule
  x-api-slug: azure-notification-hubs-api
  description: Gets an authorization rule for a namespace by name.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-notification-hubs.png
  humanURL: https://docs.microsoft.com/en-us/azure/notification-hubs/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.NotificationHubs/namespaces/{namespaceName}/AuthorizationRules/{authorizationRuleName}
  tags: Namespaces Authorization Rule
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnotificationhubsnamespacesnamespacenameauthorizationrulesauthorizationrulename-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnotificationhubsnamespacesnamespacenameauthorizationrulesauthorizationrulename-get-openapi.md
- name: Azure Notification Hubs API Namespaces List
  x-api-slug: azure-notification-hubs-api
  description: Lists the available namespaces within a resourceGroup.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-notification-hubs.png
  humanURL: https://docs.microsoft.com/en-us/azure/notification-hubs/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.NotificationHubs/namespaces
  tags: Namespaces
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnotificationhubsnamespaces-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnotificationhubsnamespaces-get-openapi.md
- name: Azure Notification Hubs API Namespaces List All
  x-api-slug: azure-notification-hubs-api
  description: Lists all the available namespaces within the subscription irrespective
    of the resourceGroups.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-notification-hubs.png
  humanURL: https://docs.microsoft.com/en-us/azure/notification-hubs/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/providers/Microsoft.NotificationHubs/namespaces
  tags: Namespaces All
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidprovidersmicrosoftnotificationhubsnamespaces-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidprovidersmicrosoftnotificationhubsnamespaces-get-openapi.md
- name: Azure Notification Hubs API Namespaces List Authorization Rules
  x-api-slug: azure-notification-hubs-api
  description: Gets the authorization rules for a namespace.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-notification-hubs.png
  humanURL: https://docs.microsoft.com/en-us/azure/notification-hubs/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.NotificationHubs/namespaces/{namespaceName}/AuthorizationRules
  tags: Namespaces Authorization Rules
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnotificationhubsnamespacesnamespacenameauthorizationrules-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnotificationhubsnamespacesnamespacenameauthorizationrules-get-openapi.md
- name: Azure Notification Hubs API Namespaces List Keys
  x-api-slug: azure-notification-hubs-api
  description: Gets the Primary and Secondary ConnectionStrings to the namespace
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-notification-hubs.png
  humanURL: https://docs.microsoft.com/en-us/azure/notification-hubs/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.NotificationHubs/namespaces/{namespaceName}/AuthorizationRules/{authorizationRuleName}/listKeys
  tags: Namespaces Keys
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnotificationhubsnamespacesnamespacenameauthorizationrulesauthorizationrulenamelistkeys-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnotificationhubsnamespacesnamespacenameauthorizationrulesauthorizationrulenamelistkeys-post-openapi.md
- name: Azure Notification Hubs API Namespaces Regenerate Keys
  x-api-slug: azure-notification-hubs-api
  description: Regenerates the Primary/Secondary Keys to the Namespace Authorization
    Rule
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-notification-hubs.png
  humanURL: https://docs.microsoft.com/en-us/azure/notification-hubs/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.NotificationHubs/namespaces/{namespaceName}/AuthorizationRules/{authorizationRuleName}/regenerateKeys
  tags: Namespaces Regenerate Keys
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnotificationhubsnamespacesnamespacenameauthorizationrulesauthorizationrulenameregeneratekeys-post-openapi.md
- name: Azure Notification Hubs API Notification Hubs Check Availability
  x-api-slug: azure-notification-hubs-api
  description: Checks the availability of the given notificationHub in a namespace.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-notification-hubs.png
  humanURL: https://docs.microsoft.com/en-us/azure/notification-hubs/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.NotificationHubs/namespaces/{namespaceName}/checkNotificationHubAvailability
  tags: Notification Hubs Availability
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnotificationhubsnamespacesnamespacenamechecknotificationhubavailability-post-openapi.md
- name: Azure Notification Hubs API Notification Hubs Create Or Update
  x-api-slug: azure-notification-hubs-api
  description: Creates/Update a NotificationHub in a namespace.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-notification-hubs.png
  humanURL: https://docs.microsoft.com/en-us/azure/notification-hubs/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.NotificationHubs/namespaces/{namespaceName}/notificationHubs/{notificationHubName}
  tags: Notification Hubs
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnotificationhubsnamespacesnamespacenamenotificationhubsnotificationhubname-put-openapi.md
- name: Azure Notification Hubs API Notification Hubs Delete
  x-api-slug: azure-notification-hubs-api
  description: Deletes a notification hub associated with a namespace.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-notification-hubs.png
  humanURL: https://docs.microsoft.com/en-us/azure/notification-hubs/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.NotificationHubs/namespaces/{namespaceName}/notificationHubs/{notificationHubName}
  tags: Notification Hubs
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnotificationhubsnamespacesnamespacenamenotificationhubsnotificationhubname-delete-openapi.md
- name: Azure Notification Hubs API Notification Hubs Get
  x-api-slug: azure-notification-hubs-api
  description: Lists the notification hubs associated with a namespace.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-notification-hubs.png
  humanURL: https://docs.microsoft.com/en-us/azure/notification-hubs/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.NotificationHubs/namespaces/{namespaceName}/notificationHubs/{notificationHubName}
  tags: Notification Hubs
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnotificationhubsnamespacesnamespacenamenotificationhubsnotificationhubname-get-openapi.md
- name: Azure Notification Hubs API Notification Hubs Create Or Update Authorization
    Rule
  x-api-slug: azure-notification-hubs-api
  description: Creates/Updates an authorization rule for a NotificationHub
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-notification-hubs.png
  humanURL: https://docs.microsoft.com/en-us/azure/notification-hubs/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.NotificationHubs/namespaces/{namespaceName}/notificationHubs/{notificationHubName}/AuthorizationRules/{authorizationRuleName}
  tags: Notification Hubs Authorization Rule
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnotificationhubsnamespacesnamespacenamenotificationhubsnotificationhubnameauthorizationrulesauthorizationrulename-put-openapi.md
- name: Azure Notification Hubs API Notification Hubs Delete Authorization Rule
  x-api-slug: azure-notification-hubs-api
  description: Deletes a notificationHub authorization rule
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-notification-hubs.png
  humanURL: https://docs.microsoft.com/en-us/azure/notification-hubs/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.NotificationHubs/namespaces/{namespaceName}/notificationHubs/{notificationHubName}/AuthorizationRules/{authorizationRuleName}
  tags: Notification Hubs Authorization Rule
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnotificationhubsnamespacesnamespacenamenotificationhubsnotificationhubnameauthorizationrulesauthorizationrulename-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnotificationhubsnamespacesnamespacenamenotificationhubsnotificationhubnameauthorizationrulesauthorizationrulename-delete-openapi.md
- name: Azure Notification Hubs API Notification Hubs Get Authorization Rule
  x-api-slug: azure-notification-hubs-api
  description: Gets an authorization rule for a NotificationHub by name.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-notification-hubs.png
  humanURL: https://docs.microsoft.com/en-us/azure/notification-hubs/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.NotificationHubs/namespaces/{namespaceName}/notificationHubs/{notificationHubName}/AuthorizationRules/{authorizationRuleName}
  tags: Notification Hubs Authorization Rule
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnotificationhubsnamespacesnamespacenamenotificationhubsnotificationhubnameauthorizationrulesauthorizationrulename-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnotificationhubsnamespacesnamespacenamenotificationhubsnotificationhubnameauthorizationrulesauthorizationrulename-get-openapi.md
- name: Azure Notification Hubs API Notification Hubs List
  x-api-slug: azure-notification-hubs-api
  description: Lists the notification hubs associated with a namespace.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-notification-hubs.png
  humanURL: https://docs.microsoft.com/en-us/azure/notification-hubs/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.NotificationHubs/namespaces/{namespaceName}/notificationHubs
  tags: Notification Hubs
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnotificationhubsnamespacesnamespacenamenotificationhubs-get-openapi.md
- name: Azure Notification Hubs API Notification Hubs List Authorization Rules
  x-api-slug: azure-notification-hubs-api
  description: Gets the authorization rules for a NotificationHub.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-notification-hubs.png
  humanURL: https://docs.microsoft.com/en-us/azure/notification-hubs/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.NotificationHubs/namespaces/{namespaceName}/notificationHubs/{notificationHubName}/AuthorizationRules
  tags: Notification Hubs Authorization Rules
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnotificationhubsnamespacesnamespacenamenotificationhubsnotificationhubnameauthorizationrules-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnotificationhubsnamespacesnamespacenamenotificationhubsnotificationhubnameauthorizationrules-get-openapi.md
- name: Azure Notification Hubs API Notification Hubs List Keys
  x-api-slug: azure-notification-hubs-api
  description: Gets the Primary and Secondary ConnectionStrings to the NotificationHub
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-notification-hubs.png
  humanURL: https://docs.microsoft.com/en-us/azure/notification-hubs/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.NotificationHubs/namespaces/{namespaceName}/notificationHubs/{notificationHubName}/AuthorizationRules/{authorizationRuleName}/listKeys
  tags: Notification Hubs Keys
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnotificationhubsnamespacesnamespacenamenotificationhubsnotificationhubnameauthorizationrulesauthorizationrulenamelistkeys-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnotificationhubsnamespacesnamespacenamenotificationhubsnotificationhubnameauthorizationrulesauthorizationrulenamelistkeys-post-openapi.md
- name: Azure Notification Hubs API Notification Hubs Regenerate Keys
  x-api-slug: azure-notification-hubs-api
  description: Regenerates the Primary/Secondary Keys to the NotificationHub Authorization
    Rule
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-notification-hubs.png
  humanURL: https://docs.microsoft.com/en-us/azure/notification-hubs/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.NotificationHubs/namespaces/{namespaceName}/notificationHubs/{notificationHubName}/AuthorizationRules/{authorizationRuleName}/regenerateKeys
  tags: Notification Hubs Regenerate Keys
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnotificationhubsnamespacesnamespacenamenotificationhubsnotificationhubnameauthorizationrulesauthorizationrulenameregeneratekeys-post-openapi.md
- name: Azure Notification Hubs API Notification Hubs Get Pns Credentials
  x-api-slug: azure-notification-hubs-api
  description: Lists the PNS Credentials associated with a notification hub .
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-notification-hubs.png
  humanURL: https://docs.microsoft.com/en-us/azure/notification-hubs/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.NotificationHubs/namespaces/{namespaceName}/notificationHubs/{notificationHubName}/pnsCredentials
  tags: Notification Hubs Pns Credentials
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftnotificationhubsnamespacesnamespacenamenotificationhubsnotificationhubnamepnscredentials-post-openapi.md
- name: Azure Notification Hubs API
  x-api-slug: azure-notification-hubs-api
  description: Azure Notification Hubs provide an easy-to-use, multi-platform, scaled-out
    push engine. With a single cross-platform API call, you can easily send targeted
    and personalized push notifications to any mobile platform from any cloud or on-premises
    backend.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-notification-hubs.png
  humanURL: https://docs.microsoft.com/en-us/azure/notification-hubs/
  baseURL: ://management.azure.com//
  tags: Azure Notification Hubs
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-notification-hubs/master/_listings/azure-notification-hubs/openapi.md
x-common:
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