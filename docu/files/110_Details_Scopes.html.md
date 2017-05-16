---
title: 'Scopes'
type: 'Details'
---

Scopes are strings that specify permissions to access resources and operations in your service. For example, a scope string may represent permission to write data to a data repository. If your service communicates with other YaaS services, you must provide a scopes document.

### Example content

Scopes are strings that specify permissions to access resources and operations in your service. For example, a scope string may represent permission to write data to a data repository.

<div class="panel note">
You must provide a scope that allows users to perform specified operations. Scopes are granted in an access token from the OAuth 2.0 service. For more information about the authorization and authentication used in SAP Hybris services, and also about the scopes in
general, see:

* <a href="/overview/security/index.html#Authorization">Authorization</a>
* <a href="/overview/security/index.html#Scopes">Scopes</a>
</div>

### Scopes
The Accounts service supports these scopes: 
| Scope   |   Description  | Selected examples of use  |
|---|---|
|**forum.accounts_view** | Use this scope to view an existing forum account. |  
|**forum.account_manage**| Use this scope to create or modify an existing forum account.     |   
|**forum.account_delete**| Use this scope to delete a forum account.  | 
