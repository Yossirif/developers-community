---
pagename: Delete Status Reason
redirect_from:
  - account-configuration-agent-status-reason-deletestatusreason.html
sitesection: Documents
categoryname: "Contact Center Management"
documentname: Agent Status Reason API
subfoldername: Methods
permalink: agent-status-reason-api-methods-delete-status-reason.html
order: 50
indicator: both
---

### Description

Delete an existing status reason.

### URI

| Method | URL |
| :-------- | :------ |
| DELETE | https://[{domain}](/agent-domain-domain-api.html)/api/account/{accountId}/configuration/le-agents/status-reasons/{statusReasonId} |

### Path Parameters

|Parameter | Description | Notes|
|--- | --- | ---|
|accountId | LP site id | Type: String |
|statusReasonId | Account Config object’s unique id. | Type: Positive long number greater than zero|

### Request

**Request Headers**

| Header | Description |
| --- | --- |
|Authorization |Contains token string to allow request authentication and authorization. See the [Authentication document](guides-authentication-introduction.html) for more details. |
|X-HTTP-Method-Override=PUT | Tells to the backend this POST request is actually PUT |
| If-Match | Contains widgets’ current revision number |

**Response Headers**

|Header | Description|
|--- | ---|
|ac-revision | Account config object type collection revision|

**Response Body**

N/A

**Response Codes**

**Response Codes**

|Code | Description |
|:----|:----|
|200 |OK|
|400 |Bad Request|
|401 |Not Authenticated|
|403 |Not Authorized|
|404 |Data not found|
|500 |Internal server error|
