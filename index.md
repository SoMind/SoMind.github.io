## Welcome to the Society of Mind Software Project

This page documents where the various parts of the project are hosted and what access is required to be granted to use each resource.

### Links

1. [Github](https://github.com/SoMind) - all the code is Open Source
  * CICD is managed by Github [Actions](https://github.com/features/actions)
  * MIT Licensed
1. Code quality is monitored by [Codacy](https://app.codacy.com/organizations/gh/SoMind/repositories)
1. Docker images are at [Dockerhub](https://hub.docker.com/orgs/somind/repositories) (for now)
1. [UI](https://somind.tech) - will host a react.js UI for talking to DTs - currently only demo for Auth0 SSO
1. [Notebooks (Jupyterhub)](https://notebook.somind.tech) - contact Navicore to get your github ID whitelisted
1. DtLab API [Docs](https://somind.tech/dtlab-alligator/doc/dtlab/) - OpenAPI 3.0
1. DtLab API Endpoint - https://somind.tech/dtlab-alligator/(type/actor)
1. DtLab Ingest API [Docs](https://somind.tech/dtlab-alligator/doc/dtlab-ingest/) - OpenAPI 3.0
1. DtLab Ingest API Endpoint - https://somind.tech/dtlab-alligator/extractor
1. Security is Implemented by [Auth0](https://manage.auth0.com/dashboard/us/navicore/) - contact Navicore for access.

### Hosting

1. The system is currently run on Digital Ocean Managed Kubernetes.
1. TLS is implemented with Lets Encrypt.
1. DT event sourcing is persisted to Digital Ocean Managed Postgres.

### Support or Contact

Want more information or to get involved?  Open an issue [here](https://github.com/SoMind/SoMind.github.io/issues) and say hello or DM @navicore on Twitter.
