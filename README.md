# Open-Source OpenSaaS Platform

Ever® OpenSaaS™ Platform is an Open-Source solution build with TypeScript that allows to quickly set up a full featured SaaS offering.

The platform is **Headless** / **API-first** (REST & GraphQL) / **BaaS** (Backend-as-a-service), but also comes with Admin UI, Client Portal UI and prebuild SDKs.

## Use cases

- Connect with existed single or multi-tenant software to quickly setup SaaS offering. We are using it with our own platforms (https://github.com/ever-co/ever-demand, https://github.com/ever-co/ever-gauzy, https://github.com/ever-co/ever-traduora, etc) to build own SaaS solutions.

- SaaS solution boilerplate. Allows to run SaaS product in few days instead of few months.

## Features

It handles following aspects of modern SaaS solutions:

- Dashboard of SaaS operation
- Tenants (Accounts) management and Dashboard (with Metrics such as New Accounts, Active Accounts, Average Users per account, etc)
- Users / Teams (Groups) management with Roles & Permissions. User Impersonation.
- Users Invite system
- Users Profiles
- Authentication / Authorization (Sign Up, Sign In, SSO, Password Reset, Social Auth, MFA, Passwordless, etc)
- API Tokens management
- Editions (Plans) / Pricing management
- Features management
- Integrations management
- Billing, Subscriptions & Payments - monetize SaaS with billing system ([Stripe](https://stripe.com) / [Paddle](https://paddle.com) / [Chargebee](https://www.chargebee.com) / other integrations)
- Health / Alerts
- Audit Logs
- Notifications (Emails, SMS, Push, Slack, etc.)
- Webhooks (allow partners / customers to subscribe to webhooks notifications)
- Events (what happens, such as sign ups, user upgraded subscription, user closed account, etc.)
- Feedback / Announcements / Chats integrations
- Reports
- Prebuilt Components
- Environments 
- And many more...

You are welcome to check more information about our product offers that use Ever® OpenSaaS Platform™ at **<https://ever.co>**.

### Disclaimer

_A word of caution_: We are in α (alpha), i.e. Ever® OpenSaaS Platform™ is very much under development (work in progress, WIP).  
Expect _lots_ of changes and some :bug: and please be nice! :stuck_out_tongue_winking_eye:

## Technology Stack and Requirements

-   [TypeScript](https://www.typescriptlang.org) language
-   [NodeJs](https://nodejs.org) / [NestJs](https://github.com/nestjs/nest)
-   [Angular](https://angular.io)
-   [RxJS](http://reactivex.io/rxjs)
-   [TypeORM](https://github.com/typeorm/typeorm)
-   [Ngx-admin](https://github.com/akveo/ngx-admin)

For Production, we recommend:

-   [PostgreSQL](https://www.postgresql.org)
-   [PM2](https://github.com/Unitech/pm2)

#### See also README.md and CREDITS.md files in relevant folders for lists of libraries and software included in the Platform, information about licenses and other details.

## Contribute

-   Please give us :star: on Github, it **helps**!
-   You are more than welcome to submit feature requests in the [separate repo](https://github.com/ever-co/feature-requests/issues)
-   Pull requests are always welcome! Please base pull requests against the _develop_ branch and follow the [contributing guide](.github/CONTRIBUTING.md).

## Contributors

View full list of our [contributors](https://github.com/ever-co/saas/graphs/contributors).

## Contact Us

-   [Ever.co Website Contact Us page](https://ever.co/contacts)
-   [Discord Chat](https://discord.gg/msqRJ4w)
-   [Slack Community](https://join.slack.com/t/everplatform/shared_invite/enQtNzc2NzI1OTgwMjQwLTBkODI3OTU2ZDI1YTQwNWE3OGExYWUwYjE5NThkMjRiYjA0NmFiNzZhYWUzNWViNWI4Nzg2YTc3MzY2MjY0YzU)
-   [Spectrum Community](https://spectrum.chat/ever)
-   [Gitter Chat](https://gitter.im/ever-co/ever)
-   [CodeMentor](https://www.codementor.io/evereq)
-   For business inquiries: <mailto:saas@ever.co>
-   Please report security vulnerabilities to <mailto:security@ever.co>

## Security

Ever OpenSaaS Platform™ follows good security practices, but 100% security cannot be guaranteed in any software!  
Ever OpenSaaS Platform™ is provided AS IS without any warranty. Use at your own risk!  
See more details in the [LICENSE.md](LICENSE.md).

In a production setup, all client-side to server-side (backend, APIs) communications should be encrypted using HTTPS/WSS/SSL (REST APIs, GraphQL endpoint, Socket.io WebSockets, etc.).

## License

This software is available under following license:

-   [Ever OpenSaaS Platform™ Community Edition](https://github.com/ever-co/saas/blob/develop/LICENSE.md)

#### Please see [LICENSE.md](LICENSE.md) for more information on licenses.

## Trademarks

Ever OpenSaaS Platform™ is a trademark of Ever Co. LTD.  
All other brand and product names are trademarks, registered trademarks or service marks of their respective holders.

## Copyright

#### Copyright © 2021-present, Ever Co. LTD. All rights reserved.

## P.S.

-   If you interested to run on-demand (delivery) or digital marketplace business, check open-source [Ever Platform](https://github.com/ever-co/ever)
-   If you are running any business or doing freelance, check [Gauzy](https://github.com/ever-co/gauzy) - Open Business Management Platform (ERP/CRM/HRM)
-   [We are Hiring: remote TypeScript / NestJS / Angular developers](https://github.com/ever-co/jobs#available-positions)
