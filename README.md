# ![LOGO](logo.png) Azure SQL Database Backup Long Term Retention Policy **flow**ground Connector

## Description

A generated **flow**ground connector for the Azure SQL Database Backup Long Term Retention Policy API (version 2014-04-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/sql-backupLongTermRetentionPolicies/2014-04-01/swagger.json<br/>
Generated at: 2019-05-07T17:39:00+03:00

## API Description

Provides read and update functionality for Azure SQL Database backup long term retention policy

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Returns a database backup long term retention policy

*Tags:* `BackupLongTermRetentionPolicies`

#### Input Parameters
* `api-version` - _required_ - The API version to use for the request.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `databaseName` - _required_ - The name of the database.

### Returns a database backup long term retention policy

*Tags:* `BackupLongTermRetentionPolicies`

#### Input Parameters
* `api-version` - _required_ - The API version to use for the request.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `databaseName` - _required_ - The name of the database.
* `backupLongTermRetentionPolicyName` - _required_ - The name of the backup long term retention policy
    Possible values: Default.

### Creates or updates a database backup long term retention policy

*Tags:* `BackupLongTermRetentionPolicies`

#### Input Parameters
* `api-version` - _required_ - The API version to use for the request.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `databaseName` - _required_ - The name of the database
* `backupLongTermRetentionPolicyName` - _required_ - The name of the backup long term retention policy
    Possible values: Default.

## License

**flow**ground :- Telekom iPaaS / azure-com-sql-backup-long-term-retention-policies-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
