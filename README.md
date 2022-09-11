# Smart-Card-Authentication-On-The-Web
This is a top-level/index repository for implementing smart-card-enabled authentication in the web application and web services.

## Introduction
This project tries to solve the global non-availability of solutions enabling the communication of web server with USB connected readers and inserted smart cards. Unfortunately, most of the current real-world solutions are proprietary or too much system-specific.

An Estonian project called [Web-eID](https://web-eid.eu), which is currently being developed to supersede currently used solution Open Electronic Identity, is enabling for Estonian public and private sector to use Estonian Electronic Identity Cards on the web.

Due to its open-source licence and modular desing, **I was able to customize this solution so a general web administrator can use this platform to implement smart card usage** (most commonly authentication and digital signature).

It is a result of my diploma thesis (URL will be added later) as well as a contribution to the Web-eID community and my local academic project.

## Where to?
These repositories are part of this project:
* [Web-eID AuthToken Validation PHP](https://github.com/Muzosh/web-eid-authtoken-validation-php) - direct extension of the official [Web-eID repository](https://github.com/web-eid) for PHP back-end servers (validation libraries for Java and .NET web applications are already part of the Web-eID repository).
* [Nextcloud Web-eID 2FA App](https://github.com/Muzosh/nextcloud_twofactor_webeid) - an installable application to Nextcloud cloud storage server enabling the usage of Web-eID for authenticating users into the web interface (can serve as an implementation example).
* [InfinitEID JavaCard applet](https://github.com/Muzosh/InfinitEID) - a modern applet and administration console that can be installed on a blank and cheap JavaCard.
* [LibElectronicID extension for InfinitEID](https://github.com/Muzosh/libelectronic-id-with-InfinitEID) - in order for Web-eID application to be able to communicate with InfinitEID, it needs to know the ATR and specific byte sequences for specific operations - these are specified in LibElectronicID interface (which is part of the Web-eID source code).
