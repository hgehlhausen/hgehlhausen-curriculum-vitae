## Projects

### Bank of America

While at Bank of America, I operated in the role of co-team-lead for the front-end part of the project. This included management over our MongoDB Database, designing its data-architecture; management over the four programs in our mono-repository; and working in React 16.8+ for the user interface as a developer.

Additionally, in my leadership role, I mentored developers, performed technical interviews of applicants, and managed the project using multiple agile frameworks ( SCRUM, Kanban, Scrumban ). Since I was also responsible for the full life-cycle of several features being implemented, from requirements gathering to design, grooming, implementation and delivery, I have strong experience in the metrics-reporting which gives management both piece of mind and the ability to course-correct when visions change.

#### BofA Cloud - Build Wizard
- Internal
- Dynamically built a form from a given data set
- Designed &amp; Implemented a custom JS validation system
- Designed &amp; Implemented a custom JS rendering selector
- Designed &amp; Implemented custom submission parsing to keep behavior generic

#### BofA Cloud - Template Driven Interface
- Leveraging Wizard, consumed a known specification type.
- Produced a configuration driven interface
- Returned data the specification's owners
- Federated model for architecture
- Assisted in design of multiple contracts and determining requirements, overall  architectural design

#### BofA Cloud - Portal Redesign
- Assisting in requirement specifications and refinement on wireframes
- Architected data-driven navigation for personalized options
- Conformed to existing Branding document and recommended updates where needed
- Preserved existing functionality where it was not replaced
- Minimized risk before release by keeping a narrow scope and communicating to prevent conflicts when main branch merged

### FuseMind LLC

#### Londen SecureApp
A Hybrid Mobile app using Sencha Touch 2.4 ( based on Ext )

Using the Apache Cordova platform and the standard plugins, including network, white-list, and camera ( to capture checks )
, and manual maintenance to have a image cropping.
the program continues to assist agents in creating and submitting applications on behalf
of their customers. Programmatic issues and bugs were caught in live-production via Rollbar.js

Since this project is compiled, dependency management was handled mainly through npm and scripts under its package.json

cordova plugin management was contained in config xml and json files ( separate from npm )

User Experience Summary - It involves structured data entry and validation, followed by payment information, and a DocuSign
session to finish the signing process on-site. The app was designed to handle all 50 states and the Washington DC's separate
insurance laws, which have alternate rules for each group of states was applied for validation and 
enabling / disabling of data collection.

[Click Here](https://appadvice.com/app/secureapp/1175083614) For the live page address of this in-production app on iOS

Released for iPad only


#### United Healthcare Student Resources
A Hybrid Mobile app using Sencha Touch, then Ionic / Angular 2+

Currently live version of this app was programmed using Sencha Touch 2 + Cordova, 
but soon a version will be released made with Ionic / Angular 2+ instead for the front end.

In the Touch version, the program successfully implemented Oauth2 as part of a Restful API controlled by the client.

In the Ionic / Angular 2 build, the api requests were handled using RxJs Observables, keeping the oauth2 key correctly
after a successful authorization request. Additional features were added as well.

User Experience Summary - allowed the download, viewing, and management of ID Cards and the ability to find the current
location of the user's phone and identify the closest Healthcare Provider. The API handled the Provider results,
given a location. The user, under who's account could be multiple dependents, could also file a claim or share the id
card via a Fax and email attachment.

A custom "show/hide" password input field was implemented quickly using the layout system supplied by Ionic's API.

[Click Here](https://play.google.com/store/apps/details?id=com.laser2mail.uhcsrmobile&hl=en) for the Google Play store listing.

Released for iOS and Android phones

#### Leadforce
A Website and Database for Sales Agent's and Office Managers to manage Leads

This legacy project has accreted multiple features. I have added a few listed here.

##### General Overview
Allows the ordering of Mail and Prospect lists. In the event of Mailings, the mail would be printed and sent-out.
Any responses went through data entry, and were entered into the system to be worked by agents.

Prospects, which have not yet responded or not yet contacted, could also be accessed by the agents via searching and reports.

Office managers could "assign" leads to be worked by agents. Agents can mark leads worked or sold in a process called "dispositioning" - a lead may change dispositions several times, until in a sold or unsellable status.

Each client had their own PostgreSQL Database to hold the responses, prospects, policy holders, orders and mailing information.

##### Features I implemented

- **Lead Input / Edit** a feature to update the personal information of a person in the system, or to add a new person into the system without developer intervention
- **Advanced Search** using jQuery DataTables and Ajax requests with a list of known filters. Could list Prospects, Leads ( responders ) and Policies. Filters included dates, formatted with Moment
- **Agent Resources Access from LeadForce Mobile** creating a pass-thru to allow the LeadForce Mobile application to authenticate and access the agent resource list for reference by the end-user
- **Lead Activities** At time of hire, there could only be 6 dispositions a response could be sorted into. This was increased using a index and history table structure, allowing for an uncapped number of possibilities.
- **Click2Dial** A custom jquery plugin allowing a text-field to gain a call button, to send a request to dial the phone number contained within the text-field.
- **Progress Bar with Page Mask** To prevent the user from making multiple form requests, implemented a page-filling mask fired when the interface should be locked.
- **Actions Column** As part of jquery DataTables, one column was added to Advanced Search to allow actions to be taken on individual records returned, including Edit, Disposition ( using Lead Activities ), and Print
- **CSV Download** Multiple CSV Download features implemented to extract data from the database in Comma separated format, for use in reporting and/or other systems.
- **Sales Goals** Developed an adaptable database structure allowing for sales goals with potentially different period-lengths and the amount of that goal, along with a name.

[Demo Website](https://leadforce.fusemind.com)

#### Fast App Medicare Advantage Admin
Support / Reporting the Fast App - Medicare Advantage mobile app, a reporting website

- Constructed front-end interface using Angular 1
- Created requests for back-end using Parse NoSQL Database solution
- Routing for pages and api using Express JS with Node, hosted on a Heroku server