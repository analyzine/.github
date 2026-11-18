<div align="center">

<a href="https://analyzine.com/?utm_source=github&utm_medium=referral&utm_campaign=readme">
  <img src="./analyzine-logo-horizontal-color.svg" alt="Analyzine logo" width="96" height="96">
</a>

# Analyzine

**Know what converts on your WordPress site. Keep the data on it.**

WordPress analytics that follows each visitor from the first click to the sale, lead or booking.<br>
All of it stored in your own WordPress database.

[![WordPress 6.5+](https://img.shields.io/badge/WordPress-6.5%2B-111418?logo=wordpress&logoColor=white)][home]
[![PHP 8.2+](https://img.shields.io/badge/PHP-8.2%2B-111418?logo=php&logoColor=white)][home]
[![Status: pre-launch](https://img.shields.io/badge/status-pre--launch-FF0055)][waitlist]
[![License: commercial](https://img.shields.io/badge/license-commercial-4A505C)][eula]

[Website][home] · [Join the waitlist][waitlist] · [Compliance][compliance] · [Blog][blog] · [Contact][contact]

</div>

---

> [!NOTE]
> Analyzine is in pre-launch. We're aiming for the **first week of December 2026**. [Join the waitlist][waitlist] for early access and a launch discount.

## Table of contents

- [What is Analyzine?](#what-is-analyzine)
- [Who it's for](#who-its-for)
- [Why we built it](#why-we-built-it)
- [Features](#features)
- [Integrations](#integrations)
- [Privacy and data ownership](#privacy-and-data-ownership)
- [Numbers you can trust](#numbers-you-can-trust)
- [How it compares](#how-it-compares)
- [Requirements](#requirements)
- [Installation](#installation)
- [Roadmap](#roadmap)
- [Pricing](#pricing)
- [FAQ](#faq)
- [Support and contact](#support-and-contact)
- [License](#license)

## What is Analyzine?

Analyzine is a paid WordPress analytics plugin that answers one question: **what earned the money, and how did those customers get there?**

You already know how many people visit. The hard part is what happens after the click. Who bought, booked or signed up? Where did they come from, and what did they read before deciding?

Today that answer usually takes three tabs. An analytics tool for sessions, your shop or form plugin for orders, and a spreadsheet to join them. Analyzine puts it all in one calm screen inside wp-admin, with no separate account and no outside dashboard.

**Most tools make you pick two of these three. Analyzine gives you all of them:**

| | What it means for you |
|---|---|
| **Private** | Your analytics data stays in your WordPress database. |
| **Deep** | Journeys, paths, funnels and heatmaps, all tied to revenue. |
| **Simple** | Plain wp-admin screens that use your words, not analytics jargon. |

## Who it's for

Analyzine is for WordPress businesses that earn through their site and want to know which channels make money, not just which ones bring traffic.

- 🛒 **Online stores** and **digital product sellers**
- 📋 **Service businesses** taking leads or bookings
- 🎓 **Course and membership sites**
- 💛 **Nonprofits** taking donations
- 🤝 **Affiliate programs**
- 🧰 **Agencies** managing client sites

It's a good fit if you're wary of Google Analytics, cookie banners, or sending visitor data to someone else's servers.

## Why we built it

We wanted to know which of our own marketing channels actually worked. The tools we tried were great at watching behaviour, but the one answer we needed sat under layers of jargon. It felt like being out at sea, looking for one specific fish.

So we built the tool we were missing. Plain answers, inside the site you already run. Read the full story in [Introducing Analyzine][intro-post].

Analyzine comes from [Solvix Studio][solvix], a small team that has built commercial WordPress plugins for years.

## Features

### Everyday reports

- **Overview** with comparison to the previous period, traffic sources, conversions and top content.
- **Channels, sources, campaigns (UTM) and landing pages.** UTM tags are the bits added to a link, like `?utm_source=newsletter`, that tell you which campaign sent a visitor.
- **Visitors by location and device.**
- **Top pages** by views and by visitors.

### Going deeper

- **Journey timeline.** Open any session and see where the person came from, which pages they read, what they did and the moment they converted. See [revenue attribution][revenue].
- **Paths.** Where people go next, and where they leave.
- **Funnels.** The exact step where people drop off.
- **Heatmaps.** Clicks and scroll depth, with no third-party script.
- **Conversions by type.** Each one is a sale, a lead or another type you define. Analyzine credits it to the visit that converted, and first-touch credit is there when you want it.
- **One base currency.** Revenue shows in a single currency, even if your store sells in several.

### AI features

- **AI assistant channel.** Visitors from ChatGPT, Perplexity, Claude, Gemini and Copilot get their own channel, with their conversions. Treat these counts as a floor. A lot of assistant traffic arrives without a referrer, so the real number is often higher.
- **AI companion.** Ask your own AI assistant analytics questions in plain language, like "Which campaign brought the most bookings last month?" It's read-only and never changes your site.

## Integrations

Most analytics tools stop at the shop and the contact form. Analyzine records **orders, leads, bookings, course sales, memberships, donations and affiliate sales**, straight from the plugins that handle them.

| Conversion type | Plugins |
|---|---|
| Orders | WooCommerce, Easy Digital Downloads, SureCart, FluentCart |
| Leads | WPForms, Gravity Forms, Fluent Forms and other form builders |
| Bookings | Amelia, LatePoint, FluentBooking |
| Courses and memberships | LearnDash, MemberPress, Paid Memberships Pro |
| Donations | GiveWP |
| Affiliate sales | AffiliateWP, Fluent Affiliate |

**27 integrations at launch.** Need one that isn't here? Waitlist members get [priority integration requests][waitlist].

## Privacy and data ownership

Privacy isn't the whole pitch. It's the reason you can trust the numbers and keep using them.

- **Your database, not ours.** All analytics data lives in your site's own WordPress database. No analytics vendor, no third-party analytics service, no separate dashboard.
- **Two tracking modes.** Use [cookieless mode][cookieless], with a visitor ID that changes daily and stores nothing on the visitor's device. Or switch to cookie mode, which [waits for consent][cookie-consent].
- **No raw IP addresses.** Analyzine never stores raw IP addresses.
- **Browser signals respected.** Do Not Track and [Global Privacy Control][gpc] both work out of the box.
- **Your retention rules.** You decide how long to keep data.
- **Works with your consent banner.** Analyzine fits the banner you already use. How you set up consent for your market stays your call.

### Privacy Audit screen

The Privacy Audit screen checks your actual settings, live. It tells you in plain words what, if anything, leaves your server.

It also lists each criterion, shows whether you meet it, and names the setting that would change it.

> [!IMPORTANT]
> No software can make you compliant on its own. Analyzine gives you the controls and tells you exactly what it does. Your consent setup is your decision. Read our guides for [GDPR][gdpr], [UK GDPR][uk-gdpr], [ePrivacy][eprivacy], [CCPA][ccpa], [US state laws][us-states] and more in the [compliance hub][compliance]. They're general information, not legal advice.

## Numbers you can trust

- **Server-side conversions.** The plugin that handled the order, lead or booking records it on the server. A browser script can't fake a conversion.
- **Clean data.** Exclude bots, your own team and preview visits with a toggle.
- **Light tracker.** A small script that stays out of your page's way and works with page caching.
- **Fast dashboard.** Reports read from daily summaries, so screens stay quick as your data grows.

## How it compares

Every analytics option is a fair choice with a trade-off. Here's where Analyzine fits.

| Type of tool | What it does well | The trade-off |
|---|---|---|
| WordPress stats plugins | Private and simple | Built first to answer "how many", not the path to a sale |
| Google Analytics dashboards | Deep reporting | Visitor behaviour goes to Google |
| Hosted analytics | Private and clean | Data and reports live on someone else's servers, with a monthly bill |
| Self-hosted platforms | Ownership and depth | Often need extra setup or a separate server |
| Session-recording tools | Detailed behaviour | Not built to say which channel paid for an order |
| WooCommerce order attribution | Free order source | Orders only, no leads, bookings or full analytics |
| **Analyzine** | **Private, deep and simple** | **Paid plugin, inside the site you already run** |

## Requirements

| Requirement | Version |
|---|---|
| WordPress | 6.5 or newer |
| PHP | 8.2 or newer |
| Theme | Any theme |

## Installation

Analyzine opens in early December 2026. Once it's out:

1. Download the plugin `.zip` from your Analyzine account.
2. In wp-admin, go to **Plugins → Add New Plugin → Upload Plugin**.
3. Choose the `.zip`, then click **Install Now** and **Activate**.
4. Open **Analyzine** in the admin menu and pick cookieless or cookie mode.
5. Open the **Privacy Audit** screen to check your setup.

Waitlist members get [setup help][waitlist] if they want a hand.

## Roadmap

- [x] Everyday reports: overview, channels, campaigns, landing pages, locations, devices
- [x] Journeys, paths, funnels and heatmaps
- [x] Conversion tracking across 27 integrations
- [x] Privacy Audit screen
- [x] AI assistant channel and AI companion
- [ ] A/B test results (arrives at launch)
- [ ] CSV export (arrives at launch)
- [ ] Public launch (first week of December 2026)

## Pricing

Analyzine is a paid plugin with a [30-day refund][refund]. A lifetime option is available, so you never have to pay a subscription forever.

Pricing starts at [PRICE]. Every plan includes every privacy feature.

**Waitlist perks:**

- Early access
- Launch discount
- Priority integration requests
- Setup help

## FAQ

<details>
<summary><strong>Where does my analytics data live?</strong></summary>

In your own WordPress database. Analyzine doesn't send it to an analytics vendor or to our servers.
</details>

<details>
<summary><strong>Does Analyzine use cookies?</strong></summary>

That's up to you. Cookieless mode uses a visitor ID that changes daily and stores nothing on the visitor's device. Cookie mode is optional and waits for consent. [Learn about cookieless analytics][cookieless].
</details>

<details>
<summary><strong>Will Analyzine make my site GDPR compliant?</strong></summary>

No plugin can do that on its own. Analyzine gives you the controls, tells you exactly what it does, and works with your consent banner. Your consent setup stays your decision. See [GDPR-friendly WordPress analytics][gdpr].
</details>

<details>
<summary><strong>How accurate is the AI assistant traffic?</strong></summary>

Treat it as a minimum. Many visits from ChatGPT, Perplexity, Claude, Gemini and Copilot arrive without a referrer, so we can't spot all of them.
</details>

<details>
<summary><strong>Will it slow down my site?</strong></summary>

The tracker is small, stays out of your page's way and works with page caching. The dashboard reads from daily summaries, so it stays fast as your data grows.
</details>

<details>
<summary><strong>Does it work with my theme?</strong></summary>

Yes. Analyzine works with any theme on WordPress 6.5+ and PHP 8.2+.
</details>

<details>
<summary><strong>When can I get it?</strong></summary>

We're aiming for the first week of December 2026. [Join the waitlist][waitlist] and we'll let you know the moment it's ready.
</details>

## Support and contact

- 💬 Questions before launch? [Contact us][contact].
- 📰 Product news and guides live on the [blog][blog].
- 👋 Meet the team on the [About page][about].
- 🔐 Privacy and legal guides sit in the [compliance hub][compliance].
- 🤝 Want to promote Analyzine? See the [affiliate program][affiliates].
- 🎨 Need our logo? Grab it from [brand assets][brand].

## License

Analyzine is commercial software. Use is covered by the [End User License Agreement][eula] and [Terms of Service][terms]. See also our [Privacy Policy][privacy] and [Refund Policy][refund].

---

<div align="center">

**Find out which channels actually make you money.**

[**Join the waitlist →**][waitlist]

Made by [Solvix Studio][solvix]

</div>

<!-- Links (UTM-tagged so GitHub visits show up as their own source) -->
[home]: https://analyzine.com/?utm_source=github&utm_medium=referral&utm_campaign=readme
[waitlist]: https://analyzine.com/?utm_source=github&utm_medium=referral&utm_campaign=readme#waitlist-final
[blog]: https://analyzine.com/blog/?utm_source=github&utm_medium=referral&utm_campaign=readme
[intro-post]: https://analyzine.com/analyzine-privacy-first-wordpress-analytics/?utm_source=github&utm_medium=referral&utm_campaign=readme
[contact]: https://analyzine.com/contact/?utm_source=github&utm_medium=referral&utm_campaign=readme
[about]: https://analyzine.com/about/?utm_source=github&utm_medium=referral&utm_campaign=readme
[revenue]: https://analyzine.com/revenue-attribution/?utm_source=github&utm_medium=referral&utm_campaign=readme
[compliance]: https://analyzine.com/compliance/?utm_source=github&utm_medium=referral&utm_campaign=readme
[gdpr]: https://analyzine.com/compliance/gdpr/?utm_source=github&utm_medium=referral&utm_campaign=readme
[uk-gdpr]: https://analyzine.com/compliance/uk-gdpr/?utm_source=github&utm_medium=referral&utm_campaign=readme
[eprivacy]: https://analyzine.com/compliance/eprivacy/?utm_source=github&utm_medium=referral&utm_campaign=readme
[ccpa]: https://analyzine.com/compliance/ccpa/?utm_source=github&utm_medium=referral&utm_campaign=readme
[us-states]: https://analyzine.com/compliance/us-privacy-laws/?utm_source=github&utm_medium=referral&utm_campaign=readme
[cookieless]: https://analyzine.com/compliance/cookieless-analytics/?utm_source=github&utm_medium=referral&utm_campaign=readme
[cookie-consent]: https://analyzine.com/compliance/cookie-consent/?utm_source=github&utm_medium=referral&utm_campaign=readme
[gpc]: https://analyzine.com/compliance/global-privacy-control/?utm_source=github&utm_medium=referral&utm_campaign=readme
[affiliates]: https://analyzine.com/affiliates/?utm_source=github&utm_medium=referral&utm_campaign=readme
[brand]: https://analyzine.com/brand-assets/?utm_source=github&utm_medium=referral&utm_campaign=readme
[privacy]: https://analyzine.com/legal/privacy-policy/?utm_source=github&utm_medium=referral&utm_campaign=readme
[terms]: https://analyzine.com/legal/terms/?utm_source=github&utm_medium=referral&utm_campaign=readme
[refund]: https://analyzine.com/legal/refund-policy/?utm_source=github&utm_medium=referral&utm_campaign=readme
[eula]: https://analyzine.com/legal/eula/?utm_source=github&utm_medium=referral&utm_campaign=readme
[solvix]: https://solvixstudio.com/?utm_source=github&utm_medium=referral&utm_campaign=readme
