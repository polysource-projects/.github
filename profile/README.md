## Welcome to EPFL Tools 👋

EPFL Tools is an unofficial organization whose goal is to provide open source digital tools for EPFL students.

* [English version](https://github.com/epfl-tools/.github/blob/main/profile/README.md)
* [French version](https://github.com/epfl-tools/.github/blob/main/profile/README_fr.md)

## Service management

To keep our organization efficient, all our projects are :
- ✅ entirely open source
- ✅ deployable via a `captain-definition` file (support for Dockerfile and Docker Compose) 
- ✅ if the service is intended for undergraduate students, in French (including README and documentation)
- ✅ in English for a larger audience

If you'd like to add your service:
* 💥 create a fork of the [epfl-tools/apps repository](https://github.com/epfl-tools/apps)
* 💥 modify the `apps.json` file (add your service)
* 💥 open a Pull Request

Please also let us know if you wish to:
* 🚚 move your personal repo to the GitHub organization, and be added to the organization to continue modifying it (preferred)
* ✂️ fork your personal repo to the GitHub organization

In any case, for questions of efficiency, security and maintenance, we will only deploy repositories added in the organization GitHub account.

🔥 Once the Pull Request has been accepted, your service will be automatically deployed to an epfl.tools subdomain with an SSL certificate and automatic deployment with each commit.

If you have any questions, don't hesitate to contact us via contact@epfl.tools or by opening an issue on the [epfl-tools/apps repository](https://github.com/epfl-tools/apps).
For example, if you don't know how to create a `Dockerfile` or `captain-defition` for your project, we can probably do it for you.

## Notes

* As far as possible, try to keep as much abstraction as possible for each of your projects. For example, if your web app needs to scrape people.epfl.ch or another site, create a universal scraper that can be reused for other projects (even if it only supports the 1-2 features you need), rather than integrating the scraper code directly into your app. (you'll be glad your app keeps working even if the site changes because someone keeps updating the scraper 😉 )
