# WiFiTayo

**Start small. Earn from your WiFi.**

WiFiTayo is a plug-and-play platform for running a **paid WiFi hotspot business** in the Philippines—pre-configured routers, a customer captive portal, e-wallet payments, and tools for operators to sell time, track sales, and grow their setup.

> This repository is the **public home** for WiFiTayo: overview, links, and writing about the project. Application source code is maintained in a **private** repository and is not published here.

---

## Public surfaces

| Surface            | URL                                                 | Purpose                                     |
| ------------------ | --------------------------------------------------- | ------------------------------------------- |
| **Shop**           | [shop.wifitayo.com](https://shop.wifitayo.com)      | Buy routers, packages, and accessories      |
| **Portal**         | [tara.wifitayo.com](https://tara.wifitayo.com)      | Hosted captive portal experience for guests |
| **Merchant admin** | [my.wifitayo.com](https://my.wifitayo.com)          | Operator dashboard (sign-in required)       |
| **Support**        | [support@wifitayo.com](mailto:support@wifitayo.com) | Product and order help                      |

Internal operations and router control tooling are not public; access is limited to the WiFiTayo team and authorized partners.

---

## What is WiFiTayo?

WiFiTayo helps small businesses and entrepreneurs turn an existing internet connection into **metered WiFi** that customers can pay for by the session.

At a high level, the system includes:

- **Captive portal**: Mobile-friendly flow for guests: connect, pause, and load more time (no manual username/password typing for end users).
- **Payments**: QR and e-wallet style top-ups integrated into the portal experience.
- **Merchant tools**: Dashboard for rates, load requests, transactions, and day-to-day store operations.
- **Shop**: Routers, extenders, signage, and starter packages for new operators.

The goal is to make running a WiFi business beginner-friendly for non-technical people, plug-and-play gear, plain-language operations, and support when you need it, so you can earn from WiFi without becoming a network engineer.

---

## Who is this for?

| Audience                                                             | What WiFiTayo offers                                                       |
| -------------------------------------------------------------------- | -------------------------------------------------------------------------- |
| **Sari-sari stores, cafés, boarding houses, clinics, waiting areas** | Extra income from WiFi without building networking from scratch            |
| **First-time “WiFi entrepreneurs”**                                  | Affordable starter kits and guided setup                                   |
| **Growing operators**                                                | More APs, bundles, and operational features as the business scales         |
| **Technicians & partners**                                           | Standardized router commissioning and fleet tooling (access by invitation) |

If you already have broadband or fiber, WiFiTayo equipment is designed to **share that connection** through a paid hotspot model—not to replace your ISP.

---

## How the business works

Day-to-day flow for **your customers** on your paid WiFi:

1. **Clients connect to your public network**: Guests join your hotspot WiFi at your location (store, boarding house, café, waiting area, and similar).
2. **The client portal shows upon connect**: The captive portal opens automatically on their phone or laptop. No app install required.
3. **Clients need balance to use your network**: They must have prepaid time (load) before the portal allows internet access.
4. **Clients load at your site**: They add time through:
   - **Vendo**: coins at your coin box
   - **E-wallet**: QR / mobile wallet in the portal
   - **Load request**: customer requests a load; your staff confirms payment and credits time
5. **Clients connect and consume**: With balance, they use **Connect** in the portal, browse while their quota runs down, **Pause** to stop the timer, and load again when time is low.

**Your role:** set rates, handle load requests, monitor sales, and keep router and vendo running. WiFiTayo links the portal, payments, and hotspot so you run the business—not raw router configuration.

---

## Getting started as an operator

1. **Gear up**: Choose a router, kit, or package from the [shop](https://shop.wifitayo.com).
2. **Plug in**: Connect to your existing internet; equipment is built for WiFiTayo.
3. **Go live**: Guests use the flow above; you manage rates, loads, and reports from [my.wifitayo.com](https://my.wifitayo.com).

---

## Projects in the WiFiTayo ecosystem

These are the main **products** under the WiFiTayo umbrella. Implementation lives in private repos; this list is for orientation and linking.

| Project                 | Description                                                                                                                          |
| ----------------------- | ------------------------------------------------------------------------------------------------------------------------------------ |
| **WiFiTayo Shop**       | Next.js storefront, catalog, checkout (PayMongo QRPH), shipping, and CMS-driven content including the blog.                          |
| **Captive Portal**      | Captive portal UI: session timer, connect/pause, load time, and payment handoffs; works with on-router hotspot pages where deployed. |
| **Merchant Admin**      | Single web application for managers and staff: load requests, transactions, rates, and shop-related payments.                        |
| **API & control plane** | Central API, payments ledger, router identity, and VPN-based remote management (AWS + dedicated controller).                         |
| **Ops**                 | Internal console for router inventory, templates, commissioning ZIPs, shop orders, and fleet health (team access only).              |

---

## Blog & resources

Guides for operators and customers (mostly in Filipino):

- [Blogs](https://shop.wifitayo.com/blog)

- [Paano kumita gamit ang iyong WiFi?](https://shop.wifitayo.com/blog/paano-kumita-gamit-ang-iyong-wifi)
- [Paano i-setup ng WiFiTayo router](https://shop.wifitayo.com/blog/paano-i-setup-ng-wifitayo-router)
- [Paano mag-load ng client](https://shop.wifitayo.com/blog/paano-mag-load-ng-client)
- [Paano magpalit ng rates at promos](https://shop.wifitayo.com/blog/paano-magpalit-ng-rates-at-promos)
- [Paano mag-request ng load](https://shop.wifitayo.com/blog/paano-mag-request-ng-load)
- [Paano kumonekta sa WiFi](https://shop.wifitayo.com/blog/paano-kumonekta-sa-wifi)
- [Paano mag-load gamit ang e-wallet](https://shop.wifitayo.com/blog/paano-mag-load-gamit-ang-e-wallet)

---

## Status & contributing

- **Source:** Private; not open source at this time.
- **This repo:** Documentation, roadmap notes, and links only—safe to star or watch for updates.
- **Contributing:** Not accepting drive-by code PRs on this public repo. For partnerships, reseller interest, or pilot sites, email [support@wifitayo.com](mailto:support@wifitayo.com).

---

## Maintainer

Built and maintained by **[Sam Tagalog](https://github.com/samtagalog)**. Software engineer focused on practical, user-facing systems (mobile and web).

- Personal site: [https://samtagalog.info](https://samtagalog.info)
- Contact: [mail.samtagalog@gmail.com](mailto:mail.samtagalog@gmail.com)

---

## License

Documentation in this repository is © WiFiTayo unless otherwise noted. WiFiTayo name, branding, and private application code are not licensed for redistribution.

---

<p align="center">
  <sub>WiFiTayo — WiFi business made easy.</sub>
</p>
