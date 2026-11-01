<a href="https://flowhawk.dev">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="wordmark-dark.svg">
    <img src="wordmark-light.svg" alt="Flowhawk" height="40">
  </picture>
</a>

### Every alert tied to the business flow it hit

Flowhawk is observability for engineering teams without an SRE. It monitors your business flows, like sign-up and checkout. When one breaks, it shows how many customers were affected, which change most likely caused it, and the traces behind it.

An alert from Flowhawk reads like this:

> Checkout failures rose from 0.2% to 9% at 14:02, about 340 orders. It started one minute after deploy api@4f2c. Here are the three traces that show it.

**How it works**

- Point any OpenTelemetry SDK or collector at Flowhawk, or keep your Sentry SDK and change its DSN.
- Flowhawk drafts your flows from the first few hours of traffic.
- An agent investigates new incidents. Anything that touches your systems, like a rollback or a config change, runs only after someone approves it.

**Here on GitHub**

- [flowhawk-byoc](https://github.com/flowhawk-dev/flowhawk-byoc): Terraform to run Flowhawk's data storage in your own AWS, Google Cloud or Azure account.

**Elsewhere**

[Website](https://flowhawk.dev) · [Docs](https://flowhawk.dev/docs/) · [Status](https://status.flowhawk.dev) · [hello@flowhawk.dev](mailto:hello@flowhawk.dev)
