---
headline: 'New Forum Account service for the Forums package'
date: May 16, 2017
service: 'Forum Account service'
official_version: 'v1'
---

Every time you release new functionality, fix issues, or make a breaking change, you must provide release notes. Provide concise but informative descriptions of the enhancements or fixes. Release notes are your chance to inform readers and to market your service, so engage your readers by describing the benefits of the changes and provide an example use case for each change. 

An engaging release note: 
* Has a headline that is:
  + Attention-grabbing but professional
  + Brief but descriptive, allowing readers to see, at a glance, what is relevant to them
  + Meets the Dev Portal's Documentation Guidelines and Style & Standards 
* Answers these questions: 
  + What changed because of this feature or resolved issue?
  + Are there changes to the UI?
  + Are there changes to the functionality?
  + Does an error message appear?
* Provides context:
  + What is the reason for the change? User feedback? An error? Continual improvements?
  + What are the benefits of the change?
  + Who should use the functionality and for what purpose?
* Explains what readers need to do to take advantage of the change.
  + Do readers need to resubscribe to the package? Migrate to a new version? Back up data files?
  + If readers do not need to take any action to use the updated functionality, say so.
* Encourages readers to dive deeper with links to:
  + The service's API Documentation 
  + Related information such as migration instructions

## Release note metadata
Use the metadata at the beginning of this file as a template. For each release note you publish, update the values of the metadata attributes as follows:

* **headline**: Provide a concise, descriptive headline that will appear as the name of your release note in the Dev Portal.
* **date**: Enter the date in Month DD, YYYY format as shown at the beginning of this template.
* **service**: Use the name of your service, and nothing else, as the value. The Dev Portal uses this information to display a path at the top of the published release note.
* **official_version**: Enter the current version of your service. Most versions are 'v1'. Services only change versions when an update breaks API compatibility. See the [API Versioning](https://devportal.yaas.io/tools/developmentguidelines/020_api_versioning.html) guidelines for more information. 

## Example content
The following example release note content begins with a descriptive H3-level heading that does not directly copy the headline metadata, but provides an additional level of insight into the change.

### Manage your online forum user accounts with the new Forum Accounts service
The new Forum Account service, now available for in the **Forums** package, allows you to manage user accounts in online forums. Use the Forum Accounts service to: 

* create user accounts
* update account details such as contact information and account status
* manually delete user accounts

This service extends the current functionality of the **Forums** package, providing a command line interface for forum moderation. You can integrate the accounts service with your existing forum user interface. 

If you are already subscribed to the **Forums** package, you can start using the new Forum Accounts service. 

For more information about this service, see the [Forum Account service API documentation](#) in the Dev Portal. 


