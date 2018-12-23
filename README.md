# Made Tech Developer Docs

This is the technical documentation hub for the Made Tech platform. You can use this resource to discover and learn about applications and open source libraries we have built both for ourselves and customers.

Primarily this resource is for Made Tech software engineers but we hope it's useful for other folk too.

## Our Handbook

If you are interested in understanding Made Tech culture you should read our open source [Handbook](https://github.com/handbook). You can find out what it's like to work in one of our software engineering teams, read our role definitions, understand our benefits and policies, and more.

## Developer Resources

- [**Learn Tech**](https://learn.madetech.com) – Our learning materials, workshops, code katas, and more.
- [**Productionistion**](https://github.com/madetech/productionisation) – Our application checklist for production readiness. We use this resource for ensuring applications we build are supportable over the long term.
- [**Clean Architecture**](https://github.com/madetech/clean-architecture) – A (work-in-progress) guide to the methodology behind Made Tech Flavoured Clean Architecture.

## Open Source

We open source some of our work for easy reuse by our teams and often for the benefit of others outside our own organisation.

- [**@madetech/frontend**](https://frontend.madetech.com) [![npm version](https://badge.fury.io/js/%40madetech%2Ffrontend.svg)](https://badge.fury.io/js/%40madetech%2Ffrontend) – Our frontend toolkit that provides HTML components, Sass and a React component library for Made Tech branded applications.
- [**cf-deploy**](https://github.com/madetech/cf-deploy) [![Gem Version](https://badge.fury.io/rb/cf-deploy.svg)](https://badge.fury.io/rb/cf-deploy) – Rake tasks for deploying to CloudFoundry v6+.
- [**jobspec**](https://github.com/madetech/jobspec) [![Gem Version](https://badge.fury.io/rb/job_spec.svg)](https://badge.fury.io/rb/job_spec) – Ruby DSL for defining job specifications and role expectations.


## Platform for madetech.com

Our www.madetech.com website is comprised of a few applications composed with an nginx forward proxy. Below you will find links to the independent components.

- [**madetech/proxy**](https://github.com/madetech/proxy) – An nginx proxy that forwards www.madetech.com traffic to appropriate applications.
- [**madetech/made**](https://github.com/madetech/made) – Our original Rails application that still serves the majority of www.madetech.com, it's the default application the forward proxy serves.
- [**madetech/made-blog**](https://github.com/madetech/made-blog) – A GatsbyJS static site builder that connects to our WordPress.com blog content.
- [**madetech/webhooks**](https://github.com/madetech/webhooks) – A webhook application for automating publishing abnd deployment of www.madetech.com.
