---
title: 'Account Status'
type: 'Details'
---

Each service must include one or more Details-type document. Details documents provide more in-depth information about the service, building on the Overview content with specifications and requirements that do not belong in Tutorials, the API Reference, or the Glossary. Examples of Details content include: 

* Diagrams of the service's execution flow
* Required subscriptions to other services, in order to use this service
* Required and available scopes, which provide access permissions to your service and others. Provide these in a separate "Scopes" Details document, provided in this template repository.
* Considerations, limitations, or workarounds that help users make the most of the service. Provide this in a separate "Considerations" Details document, also provided in this repository. 

### Details metadata
In the metadata for each Details document, you can change the 'title' to any concise, descriptive title. The 'type' must remain 'Details'. 

### Example content
Here is an example of Details-level content for the fictional Accounts service in the imaginary **Forums** package: 

Use the Accounts service to manage account statuses for your online forum users. These statuses are available by default: 

* **Active**: All user accounts with sign-in activity within the most recent 18 months are active.
* **Inactive**: The service automatically assigns the `Inactive` status to forum user accounts with no sign-ins within the most recent 18 months. Other users cannot view activity or profiles for inactive accounts.  If users of inactive accounts sign in at any time, the system assigns the `Active` status to their accounts. 
* **Deleted**: Accounts can only be deleted manually, either by the account owner or by a forum administrator. Administrators might decide to delete a user account based on violations of forum rules. Deleted accounts are not retrievable by the user or an administrator. The service archives all data for deleted accounts. 

You can create additional account statuses using the `/{tenant}accounts/status` endpoint. See the API Reference in the Accounts service documentation for details. 
