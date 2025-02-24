---
_build:
  publishResources: false
  render: never
  list: never
---

Cloudflare has several [IP address ranges](https://www.cloudflare.com/ips/) which are shared by all proxied hostnames.

Together, these IP addresses form the backbone of our [anycast network](https://www.cloudflare.com/learning/cdn/glossary/anycast-network/), helping distribute traffic amongst various edge network servers.

{{<Aside type="note">}}

Cloudflare uses other IP ranges for various products and services, but these addresses will not make connections to your origin.

{{</Aside>}}