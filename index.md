# Made Tech Engineering Docs

This is the technical documentation hub for Made Tech. You can use this resource to discover and learn about applications and open source libraries we have built both for ourselves and customers.

Primarily this resource is for Made Tech software engineers but we hope it's useful for other folk too.

## Learning Resources

We have published a number of learning resources on software delivery.

<table class="table">
  <col width='30%'>

  <tr>
    <td>
      <a href="https://learn.madetech.com">
        <strong>Learn Tech</strong>
      </a>
    </td>

    <td>
      Our learning materials, workshops, code katas, and more.
    </td>
  </tr>

  <tr>
    <td>
      <a href="https://github.com/madetech/productionisation">
        <strong>Productionistion</strong>
      </a>
    </td>

    <td>
      Our application checklist for production readiness. We use this resource for ensuring applications we build are supportable over the long term.
    </td>
  </tr>

  <tr>
    <td>
      <a href="https://github.com/madetech/clean-architecture">
        <strong>Clean Architecture</strong>
      </a>
    </td>

    <td>
      A (work-in-progress) guide to the methodology behind Made Tech Flavoured Clean Architecture.
    </td>
  </tr>
</table>

## Open Source

We open source some of our work for easy reuse by our teams and often for the benefit of others outside our own organisation.

<table class="table">
  <col width='30%'>

  <tr>
    <td>
      <a href="https://frontend.madetech.com"><strong>@madetech/frontend</strong></a>

      <br />

      <a href="https://badge.fury.io/js/%40madetech%2Ffrontend">
        <img src="https://badge.fury.io/js/%40madetech%2Ffrontend.svg" alt="npm version" />
      </a>
    </td>

    <td>
      Our frontend toolkit that provides HTML components, Sass and a React component library for Made Tech branded applications.
    </td>
  </tr>

  <tr>
    <td>
      <a href="https://github.com/madetech/cf-deploy"><strong>cf-deploy</strong></a>

      <br />

      <a href="https://badge.fury.io/rb/cf-deploy">
        <img src="https://badge.fury.io/rb/cf-deploy.svg" alt="Gem version" />
      </a>
    </td>

    <td>
      Rake tasks for deploying to CloudFoundry v6+.
    </td>
  </tr>

  <tr>
    <td>
      <a href="https://github.com/madetech/jobspec"><strong>jobspec</strong></a>

      <br />

      <a href="https://badge.fury.io/rb/job_spec">
        <img src="https://badge.fury.io/rb/job_spec.svg" alt="Gem version" />
      </a>
    </td>

    <td>
      Ruby DSL for defining job specifications and role expectations.
    </td>
  </tr>
</table>

## Platform for madetech.com

madetech.com is comprised of a few applications composed with an nginx forward proxy. Below you will find links to the independent components.

<table class="table">
  <col width='30%'>

  <tr>
    <td>
      <a href="https://github.com/madetech/proxy">
        <strong>madetech/proxy</strong>
      </a>
    </td>

    <td>
      An nginx proxy that forwards www.madetech.com traffic to appropriate applications.
    </td>
  </tr>

  <tr>
    <td>
      <a href="https://github.com/madetech/made">
        <strong>madetech/made</strong>
      </a>
    </td>

    <td>
      Our original Rails application that still serves the majority of www.madetech.com, it's the default application the forward proxy serves.
    </td>
  </tr>

  <tr>
    <td>
      <a href="https://github.com/madetech/made-blog">
        <strong>madetech/made-blog</strong>
      </a>
    </td>

    <td>
      A GatsbyJS static site builder that connects to our WordPress.com blog content.
    </td>
  </tr>

  <tr>
    <td>
      <a href="https://github.com/madetech/webhooks">
        <strong>madetech/webhooks</strong>
      </a>
    </td>

    <td>
      A webhook application for automating publishing and deployment of www.madetech.com.
    </td>
  </tr>
</table>

## Made Tech Handbook

If you are interested in understanding Made Tech culture you should read our open source [Handbook](https://github.com/handbook). You can find out what it's like to work in one of our software engineering teams, read our role definitions, understand our benefits and policies, and more.
