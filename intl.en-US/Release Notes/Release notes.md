# Release notes

This topic describes the release history of major Resource Access Management \(RAM\) features and provides the links to the relevant documentation.

## July 2020

|Feature|Description|Release date|Supported region|Documentation|
|-------|-----------|------------|----------------|-------------|
|Resource group-based authorization in the Alibaba Cloud Management Console![New feature](https://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/en-US/4244359951/p73094.png)|You can grant a RAM user, user group, or role the permissions on all the resources that belong to an Alibaba Cloud account or on a specific resource group in the RAM or Resource Management console. You can also revoke the permissions from the RAM user, user group, or role.|2020-07|All|None|

## June 2020

|Feature|Description|Release date|Supported region|Documentation|
|-------|-----------|------------|----------------|-------------|
|Alibaba Cloud services that support RAM|Time Series Database \(TSDB\) for InfluxDB supports RAM.|2020-06|N/A|[Alibaba Cloud services that support RAM](/intl.en-US/Product Introduction/Alibaba Cloud services that support RAM.md)|
|Version rotation of custom policies|If you modify a custom policy in the console and the policy already has five versions, the earliest version that is not in use is deleted and a version is created.|2020-06|All|[Manage custom policy versions](/intl.en-US/Policy Management/Custom policies/Manage custom policy versions.md)|

## May 2020

|Feature|Description|Release date|Supported region|Documentation|
|-------|-----------|------------|----------------|-------------|
|Configuration of the maximum role session duration|The maximum role session duration is configurable in the RAM console. The configuration applies when you log on to the console by using role-based SSO andwhen you use the console or call an API operation to assume a RAM role.|2020-05|All|[Set the maximum session duration for a RAM role](/intl.en-US/RAM Role Management/Set the maximum session duration for a RAM role.md)|

## March 2020

|Feature|Description|Release date|Supported region|Documentation|
|-------|-----------|------------|----------------|-------------|
|Alibaba Cloud services that support RAM|AnalyticDB for MySQL supports RAM.|2020-03|N/A|[Alibaba Cloud services that support RAM](/intl.en-US/Product Introduction/Alibaba Cloud services that support RAM.md)|
|Alibaba Cloud services that support STS|E-HPC supports STS.|2020-03|N/A|[Alibaba Cloud services that support STS](/intl.en-US/Product Introduction/Alibaba Cloud services that support STS.md)|
|Service linked role|An Alibaba Cloud service may need to access other services to implement a function. In this case, the Alibaba Cloud service must be authorized. Alibaba Cloud provides service linked roles to simplify the authorization in such scenarios.|2020-03|All|[Service linked roles](/intl.en-US/RAM Role Management/Service linked roles.md)|
|Configuration of the maximum role session duration|A new parameter named `MaxSessionDuration` is available in API operations that are used to manage RAM roles. The parameter specifies the maximum session duration of a RAM role.|2020-03|All|-   [CreateRole](/intl.en-US/API Reference (RAM)/Role management APIs/CreateRole.md)
-   [UpdateRole](/intl.en-US/API Reference (RAM)/Role management APIs/UpdateRole.md)
-   [AssumeRole](/intl.en-US/API Reference (STS)/Operation interfaces/AssumeRole.md)
-   [AssumeRoleWithSAML](/intl.en-US/API Reference (STS)/Operation interfaces/AssumeRoleWithSAML.md) |

## February 2020

|Feature|Description|Release date|Supported region|Documentation|
|-------|-----------|------------|----------------|-------------|
|Alibaba Cloud services that support STS|Dynamic Route for CDN supports STS.|2020-02|N/A|[Alibaba Cloud services that support STS](/intl.en-US/Product Introduction/Alibaba Cloud services that support STS.md)|

## January 2020

|Feature|Description|Release date|Supported region|Documentation|
|-------|-----------|------------|----------------|-------------|
|Alibaba Cloud services that support STS|ApsaraVideo Live supports STS.|2020-01|N/A|[Alibaba Cloud services that support STS](/intl.en-US/Product Introduction/Alibaba Cloud services that support STS.md)|

## December 2019

|Feature|Description|Release date|Supported region|Documentation|
|:------|:----------|:-----------|:---------------|:------------|
|Alibaba Cloud services that support RAM|Server Migration Center supports RAM.|2019-12|N/A|[Alibaba Cloud services that support RAM](/intl.en-US/Product Introduction/Alibaba Cloud services that support RAM.md)|

## November 2019

|Feature|Description|Release date|Supported region|Documentation|
|:------|:----------|:-----------|:---------------|:------------|
|User credential report|RAM provides a user credential report that contains the details of your Alibaba Cloud account and RAM users. The details in the report include logon passwords, AccessKey pairs, and multi-factor authentication \(MFA\) devices. You can generate and download the report in the RAM console.|2019-11-15|All|[Generate and download user credential reports](/intl.en-US/Security Settings/Basic security settings/Generate and download user credential reports.md)|
|Alibaba Cloud services that support STS|Hybrid Backup Recovery supports STS.|2019-11|N/A|[Alibaba Cloud services that support STS](/intl.en-US/Product Introduction/Alibaba Cloud services that support STS.md)|

## October 2019

|Feature|Description|Release date|Supported region|Documentation|
|:------|:----------|:-----------|:---------------|:------------|
|Alibaba Cloud services that support RAM|ID Verification for Financial Services supports RAM.|2019-10|N/A|[Alibaba Cloud services that support RAM](/intl.en-US/Product Introduction/Alibaba Cloud services that support RAM.md)|
|AnalyticDB supports RAM.|
|Alibaba Cloud services that support STS|Cloud Enterprise Network supports STS.|2019-10|N/A|-   [Alibaba Cloud services that support STS](/intl.en-US/Product Introduction/Alibaba Cloud services that support STS.md)
-   [RAM authentication]() |
|E-MapReduce supports STS.|[Alibaba Cloud services that support STS](/intl.en-US/Product Introduction/Alibaba Cloud services that support STS.md)|

## September 2019

|Feature|Description|Release date|Supported region|Documentation|
|-------|:----------|:-----------|----------------|-------------|
|Enable or disable console logon for RAM users|This feature enables or disables RAM user access to the RAM console. By using this feature, you can keep the password, multi-factor authentication \(MFA\), and other logon settings when you disable RAM user access to the RAM console. You can also clear console logon settings by clicking a button.|2019-09-09|All|[Manage logon settings for a RAM user](/intl.en-US/Security Settings/Basic security settings/Manage logon settings for a RAM user.md)|
|Alibaba Cloud services that support RAM|Logic Composer supports RAM.|2019-09|N/A|[Alibaba Cloud services that support RAM](/intl.en-US/Product Introduction/Alibaba Cloud services that support RAM.md)|

## June 2019

|Feature|Description|Release date|Supported region|Documentation|
|-------|:----------|:-----------|----------------|:------------|
|Auxiliary domain name for user-based single sign-on \(SSO\)|This feature simplifies the configuration of user-based SSO.|2019-06-28|All|[Overview of user-based SSO](/intl.en-US/SSO Management/User-based SSO/Overview of user-based SSO.md)|

## April 2019

|Feature|Description|Release date|Supported region|Documentation|
|-------|:----------|:-----------|----------------|:------------|
|SSO|Alibaba Cloud supports SAML 2.0-based SSO \(also known as identity federation\). SSO can be implemented between an identity provider and Alibaba Cloud.|2019-04-04|All|[SSO overview](/intl.en-US/SSO Management/SSO overview.md)|

## November 2018

|Feature|Description|Release date|Supported region|Documentation|
|-------|:----------|:-----------|----------------|:------------|
|RAM console|The RAM console is upgraded.|2018-11-15|All|[Resource Access Management](https://www.alibabacloud.com/help/product/28625.htm)|

