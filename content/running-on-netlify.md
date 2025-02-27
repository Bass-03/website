# Running on Netlify

[Netlify](https://netlify.com/) provides a free hosting service which is ideal for github organizations..

In this setup, you should already have a database server running and accepting remote connections. If you don't already have a
database, you can follow the [Running on DigitalOcean](/docs/running-on-digitalocean) guide to get a database up and running. You
can also check out the **Managed databases** section under [Hosting](/docs/hosting).

## Setup [![Deploy with netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/mikecao/umami)
_Automate steps 1-5 using the button above_

1. Fork the [https://github.com/mikecao/umami](https://github.com/mikecao/umami) project to your GitHub account.
2. Create an account on [netlify](https://netlify.com/). 
3. From the dashboard page click **Import Project** then specify the URL to your fork of the project on GitHub.
4. Add the required environment variables `DATABASE_URL` and `HASH_SALT`. These values are defined in the
**Configure umami** step from [Install](/docs/install).
5. Deploy and visit your application.
6. Follow the **Getting started** guide starting from the [Login](/docs/login) step and be sure to change the default password.


