
# Site Usage Report - SharePoint Graph API

Simple demonstration of calling graph API to provide access to Site Usage Reports. Currently configured to pull only a single site - but can be easily expanded to list out all sites and provide usage data for all sharepoint sites / lists and pages / items - you can extend this as needed.

## Getting Started

Quick guide to get you started.

### Create a App Registration and Appprove Permissions

#### General

    Name: SharePoint Graph API Power Query
    Create a Client Secret

#### API Permissions

Microsoft Graph (2)

| Permission          | Type       | Description                        | Admin Consent REquired | Status |
| -------------       | ---------- | ---------------------------------- | ---------------------- | ------ |
|  Sites.Read.All     |Application | Read items in All Site Collections | Yes | Granted |
|  User.Read          |Delegated   | Sign in and read user profile      | No  | Granted |

### Copy down the following values to include in the report

1. ClientId
2. ClientSecret
3. TenantId
4. SiteId (From SharePoint)
5. ListId (From SharePoint)

Once you have this information you can update the paramters in the PowerBI and you are off to the races.