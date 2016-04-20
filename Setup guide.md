#Setup instructions

##Pre-requisites

* All attendees must have an Apigee Edge Developer Account - [sign up here] (https://accounts2.apigee.com/accounts/sign_up?int_medium=website&int_campaign=signup&int_source=follow)
*	Create an org in BaaS. We will use BaaS as a datastore throughout the labs.
*	Provision DevJam attendees into both Edge & BaaS Orgs with Org Administrator role.

##Configure BaaS

*	Login to BaaS management UI
*	Choose your Org and application. We will use Sandbox application for the DevJam.
*	Create a new collection called “hotels”. We will use this collection our labs.
*	Load entities from the “resources/hotels.json” file. You can also create new hotel entities under the hotels collection.
* Set up the guest role with full access to the /hotels collection.

#Configure Edge
*	Login to Edge management UI
*	Choose your Org and environment (it is not recommended to use a free org as the performance of the Analytics pieces will cause problems).
*	Import the OAuth (client-credentials) proxy bundle. If you create a new account, you will get this proxy as one of the default bundles. Deploy the proxy into test environment.

##Configure Dev Portal

*	Provision a new Dev Portal
* Configure the Dev Portal to point at your organisation 
