# Wodby

[Wodby](https://wodby.com) is an applications management platform. We help developers deploy and manage their applications across any cloud. Wodby is not a hosting provider, we do not sell compute powers, instead you bring your own server/cluster from any cloud provider you want. We deploy, maintain infrastructure and stacks on your own server(s). 

The infrastructure we provide is strictly container-based and runs on Kubernetes and Docker. Our mission is to simplify the life of developers by automating most common tasks for infrastructure management and stacks maintenance. 

Wodby was founded in 2015 by [Pavel](https://github.com/PavelPrischepa) and [Chingis](https://github.com/csandanov) and backed by one of the most active Silicon Valley VCs [Plug and Play Ventures](https://www.plugandplaytechcenter.com/ventures).

## Our name

Wodby pronounced as `wɔːdbi`. Wodby is a name of a water spirit in a slavic mythology (https://en.wikipedia.org/wiki/Vodyanoy). Vodyanoy or Wodby in Upper Sorbian language.

## Documentation

Documentation for Wodby platform can be found at https://wodby.com/docs. If you're looking for a documentation of a specific stack, you can find the URL on a stack page under https://wodby.com/stacks

## Stacks

All managed and community stacks can be found at https://wodby.com/stacks

## Community

- We have a public community on [Slack](https://slack.wodby.com)
- We are [@wodbycloud](https://twitter.com/wodbycloud) on Twitter

## Platform Status

You can find current platform status at http://status.wodby.com (where you can also subscribe for email updates) or follow [@wodbystatus](https://twitter.com/wodbystatus)

## Wodby 2.0

We're actively working on Wodby 2.0, follow [us on twitter](https://twitter.com/wodbycloud) to keep with the latest updates. Among the most notable changes:
- Built-in CI. No more direct git integrations and no need to pay for third-party CI
- No more VPSs, only managed Kubernetes 
- Flexible stacks configuration and updates. Managed stack services over managed stacks, i.e. it used to be Drupal stack and now it will be separate managed services: Nginx/Apache, PHP/Ruby/Python, MariaDB/PostgreSQL/MongoDB, Solr/Elasticsearch and etc, that you can combine however you like in your own stack and still get the updates
- First-class managed databases (e.g. RDS) – spin container-based MariaDB for dev instances and RDS instance for prod
- Focus on the following cloud providers: AWS, GCP, DigitalOcean and Azure

The alpha version planned to be released in the first half of 2021

## FAQ

See https://wodby.com/docs/faq

## For developers

See https://wodby.com/docs/dev

## Our docker images

You can find our public docker images at https://hub.docker.com/r/wodby/

## Notable open-source projects

- https://github.com/wodby/docker4drupal
- https://github.com/wodby/docker4wordpress
- https://github.com/wodby/docker4php
- https://github.com/wodby/docker4ruby
- https://github.com/wodby/docker4python
