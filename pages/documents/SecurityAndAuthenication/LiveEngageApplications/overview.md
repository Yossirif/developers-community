---
pagename: What Is a LivePerson Application?
redirect_from:
  - guides-le-applications-what-is.html
Keywords:
sitesection: Documents
categoryname: "Security & Authentication"
documentname: LivePerson Applications
level-order: 13
order: 10
permalink: livePerson-applications-what-is-a-livePerson-application.html
root-link: true
indicator: both
---

LivePerson Applications are a code layer developed on top of LiveEngage APIs which include an `App_Install_Id` parameter. This parameter is received when registering a dedicated configuration manifest that defines its scope and components.

There are two different types of LiveEngage Applications:

### Global LivePerson Applications

This type of Applications can be published in a Marketplace by a Developer and will be available for all LivePerson customers to install (use/onboard) and manage within LivePerson eco-system.

It is also possible to build a Global application but define that it will not be visible in the App Management Screen. This means that it won't be visible in a Marketplace-type environment but it will be possible to use it on all accounts.

### Private LivePerson Applications

A customer will be able to develop and use their own private LivePerson Applications. These Apps won’t be published in any Marketplace-type environments. In addition, the application can be used only on a specific list of accounts defined in its Manifest.

This type of LivePerson Applications will be installed in a self-serve way through the Applications dashboard, or manually by uploading a Manifest JSON based on the [LivePerson Application Installation schema](guides-le-applications-installing.html).
